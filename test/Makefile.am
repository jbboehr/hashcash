
check_PROGRAMS = sha1
	
sha1_SOURCES = sha1.c sha1.h

TESTS = test.sh
TESTS_ENVIRONMENT = \
	top_srcdir=$(top_srcdir) \
	top_builddir=$(top_builddir)

AM_CPPFLAGS = -I$(top_builddir)/src -I$(top_srcdir)/src -I$(top_srcdir)/test
LDADD = $(top_builddir)/src/libhashcash.la

clean-local:
	rm -f stamp.*
