## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LIB_DIR=\""$(libdir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	-I$(top_srcdir)/src \
	$(PACKAGE_CFLAGS)

noinst_LIBRARIES = libliparsers.a

libliparsers_a_CFLAGS = $(PACKAGE_FLAGS)
libliparsers_a_SOURCES = \
	atom10.c atom10.h \
	html5_feed.c html5_feed.h \
	ns_admin.c ns_admin.h \
	ns_ag.c ns_ag.h \
	ns_cC.c ns_cC.h \
	ns_content.c ns_content.h \
	ns_dc.c ns_dc.h \
	ns_georss.c ns_georss.h \
	ns_itunes.c ns_itunes.h \
	ns_media.c ns_media.h \
	ns_slash.c ns_slash.h \
	ns_syn.c ns_syn.h \
	ns_trackback.c ns_trackback.h \
	ns_wfw.c ns_wfw.h \
	rss_channel.c rss_channel.h \
	rss_item.c rss_item.h 
