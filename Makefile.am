SUBDIRS = data src 
uninstall-hook:
	if test -d $(DESTDIR)$(pkgdatadir); then \
	  find $(DESTDIR)$(pkgdatadir) -depth -type d -exec rmdir {} \; ; \
	fi
