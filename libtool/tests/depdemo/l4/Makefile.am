## Makefile.am -- Process this file with automake to produce Makefile.in
##
##   Copyright (C) 2003 Free Software Foundation
##   Written by Gary V. Vaughan, 2003
##
##   This file is part of GNU Libtool.
##
## GNU Libtool is free software; you can redistribute it and/or
## modify it under the terms of the GNU General Public License as
## published by the Free Software Foundation; either version 2 of
## the License, or (at your option) any later version.
##
## GNU Libtool is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with GNU Libtool; see the file COPYING.  If not, a copy
## can be downloaded from  http://www.gnu.org/licenses/gpl.html,
## or obtained by writing to the Free Software Foundation, Inc.,
## 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.
#####

top_distdir = ../..

AUTOMAKE_OPTIONS = no-dependencies foreign

AM_CPPFLAGS = -I$(top_srcdir)

lib_LTLIBRARIES = libl4.la
libl4_la_SOURCES = l4.c l4.h
libl4_la_LDFLAGS = -no-undefined
libl4_la_LIBADD = $(top_builddir)/l3/libl3.la $(LIBM)
