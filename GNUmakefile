# SPDX-FileCopyrightText: 2025 Luca Kredel <luca.kredel@web.de>
#
# SPDX-License-Identifier: AGPL-3.0-only

DESTDIR ?=
PREFIX ?= /usr

.PHONY: all
all: install-alacritty-theme install-vim-colors

.PHONY: install-alacritty-theme
install-alacritty-theme:
	install -Dm644 -t $(DESTDIR)/$(PREFIX)/share/selenized/alacritty/ \
		terminals/alacritty/*.toml

.PHONY: install-vim-colors
install-vim-colors:
	install -Dm644 -t $(DESTDIR)/$(PREFIX)/share/vim/vimfiles/colors/ \
		editors/vim/colors/*.vim
