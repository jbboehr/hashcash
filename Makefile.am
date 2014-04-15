
EXTRA_DIST = Readme.md
SUBDIRS = doc src bin test

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = hashcash.pc

ACLOCAL_AMFLAGS = -I m4

if GCC
# These flags are gcc specific
export AM_CFLAGS = -Wall -Wextra -Wdeclaration-after-statement  \
    -Wmissing-prototypes -Wstrict-prototypes -Wold-style-definition
endif


# Alias for test (old habits die hard)
test: check
