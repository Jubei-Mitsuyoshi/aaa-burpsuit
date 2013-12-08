VER=1

	

install:
	
	install -dm755 $(DESTDIR)/usr/bin
	install -dm755 $(DESTDIR)/usr/share/burpsuite
	install -m755 burpsuite_free_v1.5.jar $(DESTDIR)/usr/share/burpsuite
	ln -s $(DESTDIR)/usr/share/burpsuite/burpsuite_free_v1.5.jar $(DESTDIR)/usr/bin/burpsuite.jar
	
	

uninstall:
	rm -rf $(DESTDIR)/usr/share/burpsuite
	rm -f $(DESTDIR)/usr/bin/burpsuite.jar

.PHONY: install uninstall
