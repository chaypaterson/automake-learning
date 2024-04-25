AC_INIT([automaketest], [0.0], [chay.paterson@manchester.ac.uk])

AC_SEARCH_LIBS([printf], [c], [], [
    AC_MSG_ERROR([printf not found in libc!])
])
AM_INIT_AUTOMAKE
AC_PROG_CC
AC_CONFIG_FILES([Makefile])
AC_ENABLE_SHARED
LT_INIT
AC_OUTPUT
