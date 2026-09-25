# Xournalpp-bookmarks-plugin

Forked from https://github.com/TamadoIchikai/xournalConfig & https://github.com/daisydaisyyy/xournalpp-bookmarks-plugin.

Reason being that `lua-lgi` doesn't seem to export `LuaGObject` anymore (fedora 44, installed through `dnf`), and exports `lgi` instead.

It's a bit confusing considering Xournal++'s [flatpak's manifest](https://github.com/flathub/com.github.xournalpp.xournalpp/blob/master/com.github.xournalpp.xournalpp.yaml) includes `LuaGObject`.
So if this version doesn't work on your system, try one of the repos listed above.

## Usage

Hit `B` to add a bookmark, `shift+B` to view bookmarks.

## Requirements

`lua-lgi` installed (`$ dnf install lua-lgi` for example).
