backgrounddir = $(datadir)/backgrounds/adapta

background_DATA = \
	tri-fadeno.jpg \
	tealized.jpg \
	suna.jpg \
	poly.jpg \
	kahelo.jpg

metadata_in_files = adapta-backgrounds.xml.in
metadata_DATA = $(metadata_in_files:.xml.in=.xml)
metadatadir = $(datadir)/gnome-background-properties

metadata_cinnamon_DATA = $(metadata_DATA)
metadata_cinnamondir = $(datadir)/cinnamon-background-properties
metadata_mate_DATA = $(metadata_DATA)
metadata_matedir = $(datadir)/mate-background-properties

noinst_DATA = adapta-backgrounds.xml.in

EXTRA_DIST = $(background_DATA)

edit = sed -e 's|@BACKGROUNDDIR[@]|$(backgrounddir)|g'

adapta-backgrounds.xml: adapta-backgrounds.xml.in
	$(edit) $< >$@

CLEANFILES = $(srcdir)/adapta-backgrounds.xml

DISTCLEANFILES = \
	$(CLEANFILES)
