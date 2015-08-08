
EXTRA_DIST = # hashcash.def

include_HEADERS = hashcash.h sdb.h

lib_LTLIBRARIES=libhashcash.la

libhashcash_la_SOURCES = \
	fastmint_ansi_ultracompact_1.c  libsha1.c \
	fastmint_altivec_compact_2.c   fastmint_library.c              lock.c \
	fastmint_altivec_standard_1.c  fastmint_mmx_compact_1.c        random.c \
	fastmint_altivec_standard_2.c  fastmint_mmx_standard_1.c       sdb.c \
	fastmint_ansi_compact_1.c       \
	fastmint_ansi_compact_2.c \
	fastmint_ansi_standard_1.c     libfastmint.c                   sstring.c \
	fastmint_ansi_standard_2.c     libhc.c                         utct.c \
	lock.h    sdb.h   sstring.h  utct.h \
	libfastmint.h  random.h   types.h sha1.h

libhashcash_la_LDFLAGS = \
	-no-undefined \
	-shared \
	-export-symbols-regex '^(hashcash|sdb_|db_|SHA1_)' \
	-version-info 0:0:0 # https://www.gnu.org/software/libtool/manual/html_node/Updating-version-info.html
