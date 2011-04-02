AC_PREREQ([2.67])
AC_INIT([gtkeditor], [1.0], [mbrush@leftclick.ca])
AC_CONFIG_MACRO_DIR([m4])
AM_INIT_AUTOMAKE([foreign silent-rules])
AM_SILENT_RULES([yes])
LT_INIT

AC_PROG_CC
AC_PROG_CXX
AM_PROG_CC_C_O
AC_PROG_INSTALL
AC_PROG_LIBTOOL

PKG_CHECK_MODULES([GTK], [gtk+-2.0])

GTK_DOC_CHECK([1.14], [--flavour no-tmpl])

GOBJECT_INTROSPECTION_CHECK([0.6.7])


AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
					gtkscintilla-1.0.pc 
					Makefile 
					build/Makefile 
					demo/Makefile
					docs/reference/Makefile])
AC_OUTPUT