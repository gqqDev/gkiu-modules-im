plugindir = $(libdir)/gkiu/modules/keyring

INCLUDES = \
	$(GKIU_CFLAGS)

plugin_LTLIBRARIES = libkeyring.la

libkeyring_la_SOURCES = \
		keyring.c\
		keyring.h

libkeyring_la_LDFLAGS = $(PLUGIN_LIBTOOL_FLAGS)
libkeyring_la_LIBADD = $(GKIU_LIBS)

plugin_DATA = keyring.plugin

EXTRA_DIST = $(plugin_DATA)

