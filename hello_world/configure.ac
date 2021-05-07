#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([hello world], [1.0.0], [huangxiaobo@brigates.com])
AC_CONFIG_SRCDIR([main.c])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC

AC_SUBST([gcc_version],[4.88])
subst_file=$srcdir/subst
AC_SUBST_FILE(subst_file)

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADER(stdio.h,
				AC_DEFINE(HAVE_STDIO_H, 1, 
				[DEFINE to 1 if you have <stdio.h>.]), 
				[AC_MSG_ERROR([sorry, can't do anything for you])])
				
# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile test])
AC_OUTPUT
