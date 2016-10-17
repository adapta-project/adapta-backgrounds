backgrounddir = $(DESTDIR)$(datadir)/backgrounds/adapta

background_DATA =\
	tri-fadeno.jpg

metadata_in_files = adapta-backgrounds.xml.in
metadatadir = $(DESTDIR)$(datadir)/gnome-background-properties
metadata_DATA = $(metadata_in_files:.xml.in=.xml)

noinst_DATA = adapta-backgrounds.xml.in

EXTRA_DIST = $(background_DATA)

edit = sed -e 's|@BACKGROUNDDIR[@]|$(backgrounddir)|g'

adapta-backgrounds.xml: adapta-backgrounds.xml.in Makefile
	$(edit) $< >$@

CLEANFILES = $(srcdir)/backgrounds/adapta-backgrounds.xml

DISTCLEANFILES = \
	$(CLEANFILES)
