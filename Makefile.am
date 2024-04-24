AUTOMAKE_OPTIONS = subdir-objects

bin_PROGRAMS = hello
hello_SOURCES = src/hello.c src/echo.c

clean-local:
	@rm config.status configure config.log
	@rm Makefile
	@rm -r autom4te.cache/
	@rm aclocal.m4
	@rm compile install-sh missing Makefile.in
