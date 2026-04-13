PREFIX ?= /usr/local
BINDIR ?= $(PREFIX)/bin
NAME   ?= power_maintenance
SRC    ?= power_maintenance

.PHONY: install uninstall

install:
	install -d $(BINDIR)
	install -m 755 $(SRC) $(BINDIR)/$(NAME)

uninstall:
	rm -f $(BINDIR)/$(NAME)
