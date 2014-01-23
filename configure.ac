
AC_INIT([mate-university],
        [1.7.0],
        [https://github.com/mate-desktop/mate-university/issues],
        [mate-university],
        [http://www.mate-desktop.org])

AC_CONFIG_HEADERS(config.h)
AC_PROG_CC
AC_PROG_INSTALL
AM_INIT_AUTOMAKE([1.9 no-dist-gzip dist-xz tar-ustar -Wno-portability])


# applet-c
PKG_CHECK_MODULES(APPLET, libmatepanelapplet-4.0 >= 1.7.0)
AC_SUBST(APPLET_CFLAGS)
AC_SUBST(APPLET_LIBS)

AC_OUTPUT([
Makefile
applet-c/Makefile
applet-python/Makefile
])
