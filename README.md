# mahjong-packs

Download host for the optional music loops and the script fonts of **Mahjong Solitaire** (NR Games), Huawei AppGallery build.

The game fetches one loop (about 1.3 MB, Ogg Opus) when a player gets a live theme. Nothing here is meant to be opened or
reused by hand.

- Files are release assets of the `packs-v*` releases, named `<theme id>-<first 8 hex of SHA-256>.ogg`. The name changes when
  the sound changes, so an old build keeps working with its old file.
- The app checks the size and the full SHA-256 of every file against the values built into it and keeps nothing else.
- All sound is synthesized by NR Games code; no third-party recordings.
- The fonts (`MahjongSerif*-<first 8 hex of SHA-256>.otf`) are subsets of Noto Serif CJK JP/KR/SC/TC, Noto Serif Thai,
  Noto Serif Devanagari and Noto Naskh Arabic, renamed. They are downloaded only when a player picks a language that needs one.
  They are licensed under the SIL Open Font License 1.1 (`OFL.txt` in this repository); the original copyright notices of the
  Noto fonts (Google LLC and Adobe) are kept in each font file.

Copyright (c) 2026 Nik Rybak, NR Games. The music loops: all rights reserved, published only so that the game can download them.
The fonts: SIL Open Font License 1.1.
