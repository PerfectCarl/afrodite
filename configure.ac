AC_PREREQ([2.65])
AC_INIT([afrodite], [0.1], [inizan.yannick@gmail.com], [libafrodite])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE
AC_CONFIG_FILES([Makefile
		src/Makefile
		src/libafrodite-0.28.pc])

AM_PROG_AR
LT_INIT
AC_PROG_CC
AM_PROG_VALAC

PKG_CHECK_MODULES(AFRODITE, [libvala-0.28)])
AC_SUBST(AFRODITE_CFLAGS)
AC_SUBST(AFRODITE_LIBS)

AC_OUTPUT
