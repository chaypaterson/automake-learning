AUTOMAKE_OPTIONS = subdir-objects foreign
AM_CPPFLAGS = -I$(src_topdir)../include

lib_LTLIBRARIES = libecho.la
libecho_la_CPPFLAGS = $(AM_CPPFLAGS)
libecho_la_SOURCES = src/echo.c
libecho_la_LDFLAGS = -version-info 0:0:0

bin_PROGRAMS = hello
hello_CPPFLAGS = $(AM_CPPFLAGS)
hello_SOURCES = src/hello.c include/echo.h
hello_LDADD = libecho.la
