#
# Copyright (c) 2016 Fabio Belavenuto
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY#  without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.
#

_OBJS = crt0.rel msxdos.rel conio.rel mem.rel heap.rel spi.rel main.rel
DESTNAME = MSX1UPD
CODELOC = 0x0180
DATALOC = 0


all: $(ODIR) updater

.PHONY: updater

updater: $(DESTNAME).COM
	$(CP) $< ../../Support/SD/UTIL

include ../makefile.inc
