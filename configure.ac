
AC_PREREQ(2.61)
AC_INIT([hashcash], [1.22], [], [hashcash],
        [https://github.com/jbboehr/hashcash])

AC_CONFIG_HEADERS([config.h])
AC_CONFIG_SRCDIR([src])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_AUX_DIR([build])

AM_INIT_AUTOMAKE([foreign -Wall])

AM_CONDITIONAL([GCC], [test x$GCC = xyes])

# Checks for programs
AC_PROG_CC
AC_PROG_CC_STDC
AC_PROG_LIBTOOL

# Checks for header files
AC_HEADER_STDC
AC_FUNC_MALLOC
AC_HEADER_DIRENT
AC_CHECK_HEADERS(ctype.h, , AC_MSG_ERROR([ctype.h is required]))
AC_CHECK_HEADERS(errno.h, , AC_MSG_ERROR([errno.h is required]))
AC_CHECK_HEADERS(memory.h, , AC_MSG_ERROR([memory.h is required]))
AC_CHECK_HEADERS(stdio.h, , AC_MSG_ERROR([stdio.h is required]))
AC_CHECK_HEADERS(stdint.h, , AC_MSG_ERROR([stdint.h is required]))
# AC_CHECK_HEADERS(uthash.h, , AC_MSG_ERROR([uthash.h is required]))

# Checks for typedefs, structures, and compiler characteristics
AC_TYPE_SIZE_T

# Checks for system
AC_EXEEXT


AC_CONFIG_FILES([
  hashcash.pc
  Makefile
  src/Makefile
  bin/Makefile
  doc/Doxyfile
  doc/Makefile
  test/Makefile
])
AC_OUTPUT
