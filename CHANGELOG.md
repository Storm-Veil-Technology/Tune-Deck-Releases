# Changelog

All notable changes to Storm Veil Tune Deck. Newest first.

## 0.2.13 (2026-09-17)

Playlists, repeat and shuffle. A new Playlists page holds your songs in your own order (create, reorder, play or shuffle-play), and songs, albums and artists on the Music page can be added with Add to Playlist. Add a playlist to a Set and its songs go to your player, where the playlist also shows up in the Playlists menu as its own playlist, in your order. The now-playing bar gains shuffle and a repeat button (off, everything, this album, this song). Picking several songs, albums or artists to add to a Set works again (only one could be ticked). Rockbox players, now including the Surfans F20 and Eros Q, get playlists that work with accented song names, and their bookmarks are kept during syncs.

## 0.2.12 (2026-09-16)

Make Tune Deck yours. Settings → Appearance now lets you pick the theme (dark, light or match Windows), an accent colour (ten presets, your Windows accent colour, or any colour code, with shades adjusted so text stays readable), text and icon size from 90% to 150%, the font, which page Tune Deck opens on, and whether the sidebar tagline and button glow show. Changes apply straight away and are saved on this computer only, no account needed. Reset to the Storm Veil look puts everything back.

## 0.2.11 (2026-09-16)

Remove songs, albums and artists from your library. Right-click a song, album or artist (or press Delete on selected songs, or the trash button on an open album or artist) and choose what happens to the files: move them to the Recycle Bin (the default, so you can restore them), delete them permanently (only files inside the Tune Deck library folder), or keep them. Removed items also leave their Sets and come off the player at its next sync. Audiobook removal uses the same choice, and Find Duplicates now sends unwanted files to the Recycle Bin.

## 0.2.10 (2026-09-15)

Phones now notice new songs. Files go onto a phone under their final names (a renamed upload was filed as 'not media' by Android, so the phone's music app never listed it), and after every sync that changed something Tune Deck makes the phone re-read its Music, Audiobooks and Playlists folders. The Device page has a 'Tell the phone to look again' button for the same nudge by hand. Press it once, or sync once, so songs already on the phone get picked up.

## 0.2.9 (2026-09-15)

Choose where on a device music goes. A phone with an SD card now shows both storages on the Device page under 'Where should music go?': pick one and the next sync fills it, with the option to remove the files Tune Deck had put on the other storage. The SD card is no longer mistaken for a second player.

## 0.2.8 (2026-09-15)

Audiobooks now go on a player through Sets, just like music: put the Audiobooks Set (or any Set holding books) on the player from the Device page, take it off to remove the books. The old 'Keep Audiobooks on Device' setting is gone; if you relied on it, an Audiobooks Set holding every book is created and chosen on every player so nothing disappears. Unchecking 'Always keep on my player' on the Audiobooks Set now sticks (the Audible setup used to switch it back on). Add Audiobooks preselects the Set your books live in.

## 0.2.7 (2026-09-15)

Choose several Sets per player: click a Set on the Device page, the Sets page or a Set's own page to put it on the player or take it off. A song in several chosen Sets is only copied once, and taking a Set off leaves songs other chosen Sets still want. Battery saver is now 'MP3 only on this player': turn it on and the next sync puts every song on that player as MP3, converting M4A, FLAC, WAV and the rest on the way, without touching your other players. Phones now receive MP3, WAV and OGG only, so a flip phone stops getting M4A.

## 0.2.6 (2026-09-15)

- Phones now work as players: plug in an Android phone (like the Kyocera DuraXV) with File transfer chosen, and Tune Deck lists it and syncs music, audiobooks and playlists to it.
- Player types: each player is a Surfans F22, an Android phone or tablet, a Rockbox player or another MP3 player, which sets its folder layout and formats. Tune Deck asks once when a new player is adopted; change it under Advanced on the player page.
- The player page and sidebar show whatever player you use instead of assuming a Surfans.

## 0.2.5 (2026-09-14)

- Player Care on the device page: Check my player looks over the card for half-copied files, computer leftovers, songs the player can't play, duplicates, empty folders, a full card and its format, with one-click fixes that only touch what the report lists.
- Battery saver: a switch that puts MP3 on the player instead of lossless formats on the next sync; your library keeps the originals.
- Card check and repair using Windows' own tools, and a helper that puts a firmware file you downloaded onto the card.

## 0.2.4 (2026-09-14)

- Wording in the Audible setup now speaks to you directly.

## 0.2.3 (2026-09-14)

- Single-file audiobooks (M4B, or MP3/MP4 with chapter markers) are split into one file per chapter on import, so the player can list, jump between and resume chapters. Works for Add Audiobooks, drag and drop, and Libation downloads.
- Settings → Audiobooks → Remove all audiobooks clears the audiobook library in one step; files inside the library folder are only deleted if you say so, files elsewhere are never touched.
- Audible downloads now stay in Libation's Books folder instead of being copied into the library folder (a switch in Settings keeps a second copy if you prefer).

## 0.2.2 (2026-09-14)

- Audiobooks now go into the player's own AUDIOBOOK folder, so the F22's Audiobook menu, resume and bookmarks work. Books put there by an earlier version are moved on the next sync, not copied again.
- Get audiobooks from Audible through Libation: a guided setup connects Libation on any computer, Audiobooks → On Audible lists your Audible library with Download buttons, and downloads land in your library and your chosen Set. Books downloaded in Libation directly are picked up automatically.
- Audible books already in your library are linked, not duplicated.

## 0.2.1 (2026-09-14)

- Audiobooks can be browsed by author or by genre, with sections and quick-jump chips. Books now have a Genre (from tags, editable in Edit Info).
- In Music, an artist's songs are sectioned under each album, with chips to switch between albums.
- Fixed an empty header showing above the artist name in the Music detail panel.

## 0.2.0 (2026-09-14)

- Built-in player: play songs, albums, Sets and audiobooks inside Tune Deck.
- Audiobooks remember where you stopped and offer Continue.

## 0.1.0 (2026-09-14)

- First release: Sets, sync to the Surfans F22, audiobooks, backups, format conversion and self-updating installer.















