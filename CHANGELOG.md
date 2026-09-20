# Changelog

All notable changes to Storm Veil Tune Deck. Newest first.

## 0.8.1 (2026-09-19)

Fixes automatic updates: a downloaded update now installs the next time you open Tune Deck, instead of waiting until you press "Restart to update". (Coming from an older build? One manual update via Settings -> Check for updates -> Restart to update gets you onto this one.)

## 0.8.0 (2026-09-19)

- Cast: choose which PC audio to send. A new "PC audio source" picker lets you send a specific playback device to the player — pair it with a virtual audio cable (e.g. VB-CABLE) and audio plays only on the player, not the PC speakers.
- Cast now auto-plays on a connected Wi-Fi player: hit Start casting and it begins playing on the phone automatically (and stops when you stop).

## 0.7.0 (2026-09-19)

- New: automatic Wi-Fi sync. Turn on "Sync players automatically when they connect over Wi-Fi" in Settings, and a player you've set up syncs its chosen Sets on its own whenever it appears on the network — leave a docked player to keep itself up to date, hands-off.
- The phone app now shows live progress ("Syncing from your computer — N files") while a Wi-Fi sync is running.

## 0.6.0 (2026-09-19)

- New: sync to your phone over Wi-Fi, cable-free. Turn on "Wireless sync" in the Tune Deck phone app, and the phone shows up on the computer like a plugged-in player — pick your Sets and hit Sync to Device, and the songs transfer over Wi-Fi.
- This build is code-signed for the first time (self-signed): installs on trusting machines show "Storm Veil Technologies" as the publisher instead of "Unknown".

## 0.5.0 (2026-09-19)

- New: Wireless sync. Turn it on under Settings → Wireless sync, and the Tune Deck player can pull your Sets, download their songs, and pick up your audiobook positions over Wi-Fi — no cable needed. The player finds this computer automatically on the same network (or you can type its address).

## 0.4.0 (2026-09-19)

- Audiobooks now go on your player as one MP3 per chapter by default, so its Audiobook menu, resume and bookmarks work reliably. Toggle under Settings → Sync.
- Audiobook positions now sync both ways with the Tune Deck player: pick up where you left off on either device (newest position wins).
- Release builds can now be optionally code-signed.

## 0.3.0 (2026-09-19)

- **Cast to player:** stream this computer's audio to your Tune Deck player over the network — a browser tab, a video, anything. The player finds this PC on its own.
- **Companion sync:** your Sets now travel to the player when you sync, so the phone or DAP rebuilds them automatically.

## 0.2.15 (2026-09-17)

Play next and Up next. Right-click songs, albums or artists (or use the buttons on a playlist) to play them next or add them to the end of the queue. The new queue button on the now-playing bar opens Up next, where you can see what's coming, play any song now, move songs up or down, take them out, or clear the rest of the queue.

## 0.2.14 (2026-09-17)

Windows media controls, playback speed and a sleep timer. Keyboard media keys, Bluetooth headphone buttons, the volume pop-up and the lock screen now control Tune Deck even when another window is in front, and show what's playing with its artwork. The now-playing bar gains a speed button (0.75x to 2x, remembered separately for audiobooks and music) and a sleep timer: 15 minutes to 1.5 hours with a gentle fade-out, or at the end of the current song or chapter, keeping your place in the book. Requires Windows 10 version 1809 or later.

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
























