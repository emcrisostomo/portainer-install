#                                               -*- Autoconf -*-
# Copyright (C) 2020 Enrico M. Crisostomo
#
# This program is free software; you can redistribute it and/or modify it under
# the terms of the GNU General Public License as published by the Free Software
# Foundation; either version 3, or (at your option) any later version.
#
# This program is distributed in the hope that it will be useful, but WITHOUT
# ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more
# details.
#
# You should have received a copy of the GNU General Public License along with
# this program.  If not, see <http://www.gnu.org/licenses/>.
#
# Process this file with autoconf to produce a configure script.
#
dnl Copyright (C) 2020 Enrico M. Crisostomo
AC_PREREQ([2.69])
AC_INIT([portainer-install], [0.2.0], [enrico.m.crisostomo@gmail.com])
AC_COPYRIGHT([2020 (C) Enrico M. Crisostomo])
AC_REVISION([$Revision: 1.0.0$])
AC_CONFIG_SRCDIR([scripts/portainer-install.in])
AC_CONFIG_AUX_DIR([config])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile])
AC_CONFIG_FILES([scripts/portainer-install])
AC_CONFIG_MACRO_DIRS([m4])
AC_CONFIG_MACRO_DIR([m4])

# Initialize Automake
AM_INIT_AUTOMAKE([-Wall -Werror gnu subdir-objects])
AM_SILENT_RULES([yes])

# Checks for programs.
AC_PATH_PROG([CURL_CMD],   [curl],  [no])

AS_VAR_IF([CURL_CMD],   [no], [AC_MSG_ERROR([curl is required.])],   [])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_OUTPUT
