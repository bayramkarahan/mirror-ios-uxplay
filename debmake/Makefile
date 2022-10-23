DESTDIR=/
build:
	: please run Make install
install:
	mkdir -p $(DESTDIR)/usr/bin || true
	mkdir -p $(DESTDIR)/usr/share/applications/ || true
	mkdir -p $(DESTDIR)/usr/share/icons/ || true
	install uxplay $(DESTDIR)/usr/bin/
	install data/uxplay.desktop $(DESTDIR)/usr/share/applications/
	install data/uxplay.svg $(DESTDIR)/usr/share/icons/uxplay.svg