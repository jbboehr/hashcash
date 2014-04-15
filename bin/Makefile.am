
bin_PROGRAMS = hashcash

hashcash_SOURCES = hashcash.c getopt.c getopt.h

AM_CPPFLAGS = -I$(top_builddir)/src -I$(top_srcdir)/src
AM_LDFLAGS = -static  # for speed and Valgrind
LDADD = $(top_builddir)/src/libhashcash.la
