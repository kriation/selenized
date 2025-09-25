# SPDX-FileCopyrightText: 2025 Luca Kredel <luca.kredel@web.de>
#
# SPDX-License-Identifier: AGPL-3.0-only

DESTDIR ?=
PREFIX ?= /usr

.PHONY: install-alacritty-theme
install-alacritty-theme:
	install -Dm644 -t $(DESTDIR)/$(PREFIX)/share/selenized/alacritty/ \
		terminals/alacritty/*.toml
