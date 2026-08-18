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
| `imgur-03RLBaX.png` | https://i.imgur.com/03RLBaX.png |
| `imgur-0EnjyQX.png` | https://i.imgur.com/0EnjyQX.png |
| `imgur-0VuijTx.png` | https://i.imgur.com/0VuijTx.png |
| `imgur-1jUOMlX.png` | https://i.imgur.com/1jUOMlX.png |
| `imgur-1uDdNtU.png` | https://i.imgur.com/1uDdNtU.png |
| `imgur-1znO8HP.png` | https://i.imgur.com/1znO8HP.png |
| `imgur-2B73rSk.png` | https://i.imgur.com/2B73rSk.png |
| `imgur-2m630qZ.png` | https://i.imgur.com/2m630qZ.png |
| `imgur-2ybEpCV.png` | https://i.imgur.com/2ybEpCV.png |
| `imgur-4wTs28o.png` | https://i.imgur.com/4wTs28o.png |
| `imgur-7TAlNtd.png` | https://i.imgur.com/7TAlNtd.png |
| `imgur-A6JTWBV.png` | https://i.imgur.com/A6JTWBV.png |
| `imgur-ArLGcWu.png` | https://i.imgur.com/ArLGcWu.png |
| `imgur-Cd9yD43.png` | https://i.imgur.com/Cd9yD43.png |
| `imgur-FXgZQ46.png` | https://i.imgur.com/FXgZQ46.png |
| `imgur-FnLyZvk.png` | https://i.imgur.com/FnLyZvk.png |
| `imgur-Glb39dj.png` | https://i.imgur.com/Glb39dj.png |
| `imgur-GqKocpf.png` | https://i.imgur.com/GqKocpf.png |
| `imgur-HbDL75f.png` | https://i.imgur.com/HbDL75f.png |
| `imgur-Ie4y9Qf.png` | https://i.imgur.com/Ie4y9Qf.png |
| `imgur-IimHVxe.png` | https://i.imgur.com/IimHVxe.png |
| `imgur-K7taOUe.png` | https://i.imgur.com/K7taOUe.png |
| `imgur-LgfmRM4.png` | https://i.imgur.com/LgfmRM4.png |
| `imgur-O7kekkb.png` | https://i.imgur.com/O7kekkb.png |
| `imgur-PwhIT4u.png` | https://i.imgur.com/PwhIT4u.png |
| `imgur-Q96yagv.png` | https://i.imgur.com/Q96yagv.png |
| `imgur-R1f6iXn.png` | https://i.imgur.com/R1f6iXn.png |
| `imgur-R5p9fqw.png` | https://i.imgur.com/R5p9fqw.png |
| `imgur-RiCJalE.png` | https://i.imgur.com/RiCJalE.png |
| `imgur-S8msdHU.png` | https://i.imgur.com/S8msdHU.png |
| `imgur-SjSb5yJ.png` | https://i.imgur.com/SjSb5yJ.png |
| `imgur-TOsmJOl.png` | https://i.imgur.com/TOsmJOl.png |
| `imgur-Ti4NWys.png` | https://i.imgur.com/Ti4NWys.png |
| `imgur-UbvyFSt.png` | https://i.imgur.com/UbvyFSt.png |
| `imgur-Wp4lhTM.png` | https://i.imgur.com/Wp4lhTM.png |
| `imgur-X463V90.png` | https://i.imgur.com/X463V90.png |
| `imgur-Z4YUAvW.png` | https://i.imgur.com/Z4YUAvW.png |
| `imgur-aXVbVl6.png` | https://i.imgur.com/aXVbVl6.png |
| `imgur-byOtZxM.png` | https://i.imgur.com/byOtZxM.png |
| `imgur-dNY6e8n.png` | https://i.imgur.com/dNY6e8n.png |
| `imgur-dS8un97.png` | https://i.imgur.com/dS8un97.png |
| `imgur-e0IXt8w.png` | https://i.imgur.com/e0IXt8w.png |
| `imgur-ejI5STj.png` | https://i.imgur.com/ejI5STj.png |
| `imgur-fL88z7p.png` | https://i.imgur.com/fL88z7p.png |
| `imgur-hKBqtWE.png` | https://i.imgur.com/hKBqtWE.png |
| `imgur-hckhnZy.png` | https://i.imgur.com/hckhnZy.png |
| `imgur-kK3l1C1.png` | https://i.imgur.com/kK3l1C1.png |
| `imgur-kryyJRy.png` | https://i.imgur.com/kryyJRy.png |
| `imgur-l329bR4.png` | https://i.imgur.com/l329bR4.png |
| `imgur-l7SjOSw.png` | https://i.imgur.com/l7SjOSw.png |
| `imgur-lvp7545.png` | https://i.imgur.com/lvp7545.png |
| `imgur-lxeruPM.png` | https://i.imgur.com/lxeruPM.png |
| `imgur-mFzTJXv.png` | https://i.imgur.com/mFzTJXv.png |
| `imgur-nAaynHA.png` | https://i.imgur.com/nAaynHA.png |
| `imgur-nNQEVpb.png` | https://i.imgur.com/nNQEVpb.png |
| `imgur-nSYuby8.png` | https://i.imgur.com/nSYuby8.png |
| `imgur-nVAyYVQ.png` | https://i.imgur.com/nVAyYVQ.png |
| `imgur-nVu2ivF.png` | https://i.imgur.com/nVu2ivF.png |
| `imgur-pIFrNLa.png` | https://i.imgur.com/pIFrNLa.png |
| `imgur-qaXHsQU.png` | https://i.imgur.com/qaXHsQU.png |
| `imgur-r7TAcjS.png` | https://i.imgur.com/r7TAcjS.png |
| `imgur-rI1tW64.png` | https://i.imgur.com/rI1tW64.png |
| `imgur-sncfljQ.png` | https://i.imgur.com/sncfljQ.png |
| `imgur-t0khtQd.png` | https://i.imgur.com/t0khtQd.png |
| `imgur-u8l36Pw.png` | https://i.imgur.com/u8l36Pw.png |
| `imgur-uVdgw3H.png` | https://i.imgur.com/uVdgw3H.png |
| `imgur-uf1VZEJ.png` | https://i.imgur.com/uf1VZEJ.png |
| `imgur-whOAxsp.png` | https://i.imgur.com/whOAxsp.png |
| `imgur-xRdE1iN.png` | https://i.imgur.com/xRdE1iN.png |

Regenerating axilog's catalogs rewrites these URLs automatically —
see `scripts/icon_mirror.py` there. Adding a file to this directory
without also adding its name to that module's `MIRRORED` set does
nothing; adding an upstream URL that is not mirrored here is a hard
error at generation time, deliberately, so a broken link can never
reach a published report unnoticed.
