AC_PREREQ([2.69])
AC_INIT([oscilloscoper], [0.0.0])
#AC_CONFIG_HEADERS([config.h])

AC_CONFIG_SRCDIR([src/Main.cpp])
AM_INIT_AUTOMAKE([foreign])
#AC_CONFIG_MACRO_DIRS([m4])

#AX_ASAN
#AX_DEBUG
#AX_GPROF
AC_PROG_RANLIB

AC_SUBST(SDL2_CFLAGS, `pkg-config --cflags sdl2`)
AC_SUBST(SDL2_LIBS, `pkg-config --libs sdl2`)

AC_PROG_CXX

AC_CONFIG_FILES([Makefile src/DspFilters/Makefile src/Makefile])
AC_OUTPUT

