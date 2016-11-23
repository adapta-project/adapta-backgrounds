backgrounddir = $(datadir)/backgrounds/adapta

background_DATA =\
	tri-fadeno.jpg \
	tealized.jpg \
	suna.jpg \
	poly.jpg

metadata_in_files = adapta-backgrounds.xml.in
metadatadir = $(datadir)/gnome-background-properties
metadata_DATA = $(metadata_in_files:.xml.in=.xml)

noinst_DATA = adapta-backgrounds.xml.in

EXTRA_DIST = $(background_DATA)

edit = sed -e 's|@BACKGROUNDDIR[@]|$(backgrounddir)|g'

adapta-backgrounds.xml: adapta-backgrounds.xml.in
	$(edit) $< >$@

CLEANFILES = $(srcdir)/adapta-backgrounds.xml

DISTCLEANFILES = \
	$(CLEANFILES)
