# Derby Club deployment

Unofficial 2D browser medal-racing game inspired by the betting interface and core rules of Minna de Derby 2. This branch replaces the generic 3D game with single-win, quinella, exacta and axis betting, 1/10-medal increments, a 30-second deadline and cookie-backed progress.

This repository contains static deployment artifacts. Source and test evidence are maintained separately. The implementation does not bundle original game artwork, proprietary algorithms, multiplayer or the complete bonus modes.

Validation: TypeScript/Vite build, seven model tests, complete browser gameplay, three mobile/tablet widths, legacy-cookie migration, automatic race deadline, and two real-browser stale-tab regression scenarios. Independent Sol review approved the corrected behavior in two rounds.
