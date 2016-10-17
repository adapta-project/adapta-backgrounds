backgroundsdir  = $(datadir)/backgrounds
adaptadir = $(DESTDIR)$(backgroundsdir)/adapta

SUBDIRS = \
	backgrounds

EXTRA_DIST = \
	AUTHORS \
	COPYING \
	LICENSE_CC_BY_SA3

install-data-hook:
	cp -Rv $(EXTRA_DIST) $(adaptadir)

uninstall-hook:
	test -e $(adaptadir) && rm -rfv $(adaptadir)
