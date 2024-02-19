# TachiyomiAZ  
the BEST fork - az4521 (unbiased)
  
https://discord.gg/tachiyomi  
https://discord.gg/mihon

## features since tachiyomi.org yeeted /forks
- more fumo (fumo theme)
- material design 1 (sidebar + hamburger)
- Get Recommendations From MyAnimeList And AniDB
- best fork

## TODO
> warning: the code is spaghetti  
> if some of these sound interesting, feel free to open a pull request. thanks!
  
### dead source removal + delegation
- [x] remove hbrowse (dead)
- [x] remove perveden (dead)
- [ ] delegate 8muses
- [ ] delegate hitomi
### fix
- [ ] extension prefs are applied incorrectly in multi src exts
- [x] https://github.com/mihonapp/mihon/commit/d6c4af89c4a2df213f06ed4c3d714a2608117afb
- [x] ~~switch from glide to coil, and use tachiyomi's image decoder~~
- [x] ~~include tachiyomi's image decoder for exts to use, support AVIF and HEIC~~
- [x] include tachiyomi's image decoder as a decoder for glide, supporting AVIF, HEIC, and JXL!
- [ ] recognize CBZ downloads in UI, not only in badges
- [ ] fix smart background (steal from j2k)
- [ ] chapter list: current page progress same color as scanlator group
- [ ] extension repo list: remove category icon, add left-right padding
- [x] rgb filter corrupted preview image ~~(remove?)~~ replace with fox girl drawing
### match stable/j2k
- [ ] allow downloading in CBZ
- [x] ~~extlib 1.5 (migrate rx to coroutines)~~ 1.5 isn't happening, but I *did* migrate pagers to coroutine, fixing the pixiv ext
- [ ] re-order per-source downloads
- [ ] j2k: editing manga info - [j2k commit](https://github.com/Jays2Kings/tachiyomiJ2K/commit/d3ec230d4baa8584118dc30807728305715db25b)
- [ ] j2k: reader: add chapter list view
### maybe
- [ ] add quick shortcut to extension repos in "Extensions" tab
- [ ] improve internals
