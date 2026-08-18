# Mirrored icons

Art that [axilog](https://github.com/darkharasho/axilog)'s icon catalogs
reference but that lives on hosts nobody here controls.

Most GW2 icons come from `render.guildwars2.com` (ArenaNet's own render
service) or `wiki.guildwars2.com`. Both are durable enough to hot-link.

These 18 are not. Elite Insights sources them from `i.imgur.com` —
anonymous uploads made years ago by contributors, which imgur may remove at
any time — and from `assets.gw2dat.com`, a community site with no
durability guarantee. They cannot simply be re-sourced: of the 61 buff and
skill ids they cover, the official API knows exactly one, and that one
carries no icon.

Filenames keep the upstream id and gain a host prefix, so provenance stays
readable in a `git diff`:

| file | upstream |
|---|---|
| `gw2dat-3568389.png` | https://assets.gw2dat.com/3568389.png |
| `gw2dat-3568391.png` | https://assets.gw2dat.com/3568391.png |
| `gw2dat-3568392.png` | https://assets.gw2dat.com/3568392.png |
| `gw2dat-3691067.png` | https://assets.gw2dat.com/3691067.png |
| `gw2dat-3772576.png` | https://assets.gw2dat.com/3772576.png |
| `imgur-0EnjyQX.png` | https://i.imgur.com/0EnjyQX.png |
| `imgur-0VuijTx.png` | https://i.imgur.com/0VuijTx.png |
| `imgur-2m630qZ.png` | https://i.imgur.com/2m630qZ.png |
| `imgur-7TAlNtd.png` | https://i.imgur.com/7TAlNtd.png |
| `imgur-e0IXt8w.png` | https://i.imgur.com/e0IXt8w.png |
| `imgur-K7taOUe.png` | https://i.imgur.com/K7taOUe.png |
| `imgur-l7SjOSw.png` | https://i.imgur.com/l7SjOSw.png |
| `imgur-LgfmRM4.png` | https://i.imgur.com/LgfmRM4.png |
| `imgur-lxeruPM.png` | https://i.imgur.com/lxeruPM.png |
| `imgur-nNQEVpb.png` | https://i.imgur.com/nNQEVpb.png |
| `imgur-nSYuby8.png` | https://i.imgur.com/nSYuby8.png |
| `imgur-Ti4NWys.png` | https://i.imgur.com/Ti4NWys.png |
| `imgur-uf1VZEJ.png` | https://i.imgur.com/uf1VZEJ.png |

Regenerating axilog's catalogs rewrites these URLs automatically —
see `scripts/icon_mirror.py` there. Adding a file to this directory
without also adding its name to that module's `MIRRORED` set does
nothing; adding an upstream URL that is not mirrored here is a hard
error at generation time, deliberately, so a broken link can never
reach a published report unnoticed.
