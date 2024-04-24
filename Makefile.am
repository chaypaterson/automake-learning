AUTOMAKE_OPTIONS = subdir-objects

lib_LTLIBRARIES = libecho.la
libecho_la_SOURCES = src/echo.c
libecho_la_LDFLAGS = -version-info 0:0:0

bin_PROGRAMS = hello
hello_SOURCES = src/hello.c
hello_LDADD = libecho.la

clean-local:
	@rm config.status configure config.log
	@rm Makefile
	@rm -r autom4te.cache/
	@rm aclocal.m4
	@rm compile install-sh missing Makefile.in
