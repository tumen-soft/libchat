#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([0.11])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AC_CONFIG_SRCDIR([peer.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

AM_INIT_AUTOMAKE
AC_PROG_MAKE_SET

AC_PROG_RANLIB


# Checks for libraries.
# FIXME: Replace 'main' with a function in '-lchat':
AC_CHECK_LIB([chat], [main])

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.
AC_CHECK_FUNCS([memset select socket])

AC_CONFIG_FILES([Makefile
                 tests/Makefile])
AC_OUTPUT
