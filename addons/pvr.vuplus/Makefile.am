#
# Makefile for the VuPlus add-on for XBMC PVR
#
# See the README for copyright information and
# how to reach the author.
#

ADDONBINNAME    = Kodi_vuplus
ADDONNAME       = pvr.vuplus
LIBNAME         = libvuplus-addon
lib_LTLIBRARIES = libvuplus-addon.la

LIBS            = @abs_top_srcdir@/lib/tinyxml/libtinyxml.la

include ../Makefile.include.am

libvuplus_addon_la_SOURCES = src/client.cpp \
                             src/VuData.cpp 
libvuplus_addon_la_LDFLAGS = @TARGET_LDFLAGS@

