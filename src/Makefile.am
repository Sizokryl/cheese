INCLUDES = 						\
	-DBINDIR=\"$(bindir)\"			 	\
	-DDATADIR=\"$(datadir)\"			\
	-DPREFIX=\""$(prefix)"\" 			\
	-DSYSCONFDIR=\""$(sysconfdir)"\" 		\
	-DLIBDIR=\""$(libdir)"\" 			\
	-DPACKAGE_DATADIR=\""$(datadir)/cheese"\"	\
	-DPACKAGE_LOCALEDIR=\""$(datadir)/locale"\"	\
	$(CHEESE_CFLAGS)

bin_PROGRAMS = cheese

cheese_SOURCES = \
	cheese.c \
	cheese-effect-chooser.c \
	cheese-effect-chooser.h \
	cheese-fileutil.c \
	cheese-fileutil.h \
	cheese-gconf.c \
	cheese-gconf.h \
	cheese-thumb-view.c \
	cheese-thumb-view.h \
	cheese-webcam.c \
	cheese-webcam.h \
	cheese-window.c \
	cheese-window.h \
	eog-thumb-shadow.c \
	eog-thumb-shadow.h

cheese_LDADD = \
	$(CHEESE_LIBS)		
