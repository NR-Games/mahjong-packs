# mahjong-packs

Download host of **Mahjong Solitaire** by NR Games, Huawei AppGallery build. The game fetches its theme music and some
language fonts from the releases of this repository. Nothing here is meant to be opened or reused by hand.

## The music: all rights reserved

The theme music loops are original works of NR Games, licensed **only for use inside Mahjong Solitaire** (see `LICENSE`).
Copying, re-uploading, recording or using them in any other game, video, stream or work is not allowed without written
permission. Being in a public repository does not make them free to use: they are here only so that the game can download them.

- Release `packs-v2` and later: each loop is sealed for the game (`<theme id>-<first 8 hex of SHA-256>.nrgp`) and does not
  play outside it.
- The game checks the size and the full SHA-256 of every file against the values built into it and keeps nothing else.
- All sound is synthesized by NR Games code; there are no third-party recordings in it.

## The fonts: SIL Open Font License 1.1

The fonts (`MahjongSerif*-<first 8 hex of SHA-256>.otf`) are subsets of Noto Serif CJK JP/KR/SC/TC, Noto Serif Thai,
Noto Serif Devanagari and Noto Naskh Arabic, renamed. The game downloads one only when a player picks a language that needs it.
They are licensed under the SIL Open Font License 1.1 (`OFL.txt`); the original copyright notices of the Noto fonts
(Google LLC and Adobe) are kept in each font file.

## Contact

Permission requests and infringement notices: https://rybaknekyadnexru-cell.github.io/

Copyright (c) 2026 Nik Rybak, NR Games. The music loops: all rights reserved, licensed only for use inside Mahjong Solitaire.
The fonts: SIL Open Font License 1.1.
