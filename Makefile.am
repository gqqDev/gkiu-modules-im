## Process this file with automake to produce Makefile.in

SUBDIRS = modules

gkiudocdir = ${prefix}/doc/gkiu

gkiudoc_DATA = \
	README \
	INSTALL

EXTRA_DIST = $(gkiudoc_DATA) \
	$(INTLTOOL_FILES)

DISTCLEANFILES = intltool-extract \
	intltool-merge \
	intltool-update \
	po/.intltool-merge-cache


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(gkiudocdir)

