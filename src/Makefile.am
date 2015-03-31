lib_LTLIBRARIES = libafrodite-0.28.la

libafrodite_0_28_la_SOURCES = \
	astmerger.vala \
	astdumper.vala \
	parser.vala \
	parseresult.vala \
	symbol.vala \
	symbolresolver.vala \
	datatype.vala \
	voidtype.vala \
	sourcereference.vala \
	sourcefile.vala \
	codedom.vala \
	utils.vala \
	completionengine.vala \
	ellipsistype.vala \
	queryoptions.vala \
	queryresult.vala \
	resultitem.vala \
	constants.vala \
	sourceitem.vala
	
libafrodite_0_28_la_CFLAGS = $(AFRODITE_CFLAGS)

libafrodite_0_28_la_LIBADD = $(AFRODITE_LIBS)

libafrodite_0_28_la_VALAFLAGS = --library libafrodite-0.28 --vapi libafrodite-0.28.vapi --target-glib=2.32 --header afrodite.h \
	--vapidir ./vapi --pkg gio-2.0 --pkg libvala-0.28

vapidir = $(datadir)/vala/vapi
dist_vapi_DATA = libafrodite-0.28.vapi libafrodite-0.28.deps

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libafrodite-0.28.pc

afroditeincludedir = $(includedir)/libafrodite-0.28
afroditeinclude_HEADERS = afrodite.h

CLEANFILES = *.c *.o *.la *.stamp

DISTCLEANFILES = $(CLEANFILES) Makefile.in *.pc
