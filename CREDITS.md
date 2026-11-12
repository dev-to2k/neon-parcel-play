# Credits

The life-hub menus, item icons, and combat VFX are original procedural pixel art drawn in `game.js`. The hub street's buildings, props, and townsfolk are cut from GrafxKid's CC0 City Mega Pack (`art/street/`, notice in `CREDITS.txt`); the older procedural street and NPC drawings in `game.js` remain as the fallback. The rented studio and the extra street dressing live in `home-decor.js`; the studio's door, desk, kitchen, shelf, and curtains come from the same pack, with the procedural drawings kept as the fallback. Sewer floors draw CC0 brick and algae textures from `art/sewer/` (recolored) plus original dressing in `sewer-visual.js`. Notices are in `art/sewer/CREDITS.txt`. This build does not ship paid asset packs. When the street atlas does not load, the hub NPC bodies fall back to recoloured CC0 sprites from OVFudj's Modern RPG Guy, and the far skyline band is a recoloured crop of ansimuz's CC0 Warped City plate; both live in `art/hub/` with a per-file ledger in `art/hub/LEDGER.txt`.

Hub UI text uses **Fusion Pixel Font**, the 12px proportional Latin face, by TakWolf (https://takwolf.com). It is licensed under the SIL Open Font License 1.1, which allows commercial use when the font is bundled with software and is not sold by itself. The file shipped here is `fonts/fusion-pixel-12px-latin.woff2`, a Latin and Vietnamese subset of release 2026.10.25 (https://github.com/TakWolf/fusion-pixel-font). The subset keeps the original font name. No reserved font name is declared. The full license is `fonts/OFL.txt`.

That Latin build also includes glyphs derived from Ark Pixel, Cubic 11, and Galmuri, each under the SIL Open Font License. Their notices are in `fonts/LICENSES/`.

Body text is drawn from the Fusion Pixel 12px bitmap at its native 12px. Titles are that same bitmap at an integer 2×. The run HUD, title, story, and play-mode toasts use the Fusion Pixel 8px bitmap where the line is one cap tall, and the 12px bitmap at an integer multiple otherwise. Both sizes are the authored BDF pixels in `fonts/pixel-face.js`, from the same 2026.10.25 release. The 8px face does not contain every Vietnamese tone, so a string with a missing 8px glyph is drawn with the 12px face. The woff2 stays for the HTML line under the canvas.

Earlier motion studies mentioned free itch.io packs (cs5475, nerijs PVFX Foundry, IceMaan) as timing reference only. Those files are not in the repository and none of their pixels are copied here.

No project `LICENSE` file has been chosen. Font files keep their own SIL OFL notices. That is not a game-wide license. The shipped OFL texts define the term Reserved Font Name and do not name one after the copyright line. That is an observation, not legal clearance.

The drop-point mailbox is a CC-BY 3.0 derivative, not a CC0 file. The release notice that ships next to `index.html` is `CREDITS.txt`.

The rival courier (Alex's Assets), the rooftop and hub cats (kotnaszynce), the sewer hound (Cough-E), and the market crab (Camacebra Games) are CC0 sprites loaded by `char-skin.js` from `art/rival/`, `art/cat/`, and `art/foes/`; the older procedural drawings in `game.js` remain the fallback. Notices are in `CREDITS.txt` and `docs/ASSET_LICENSES.md`.

Item pass 2: the magnet, slow-mo, and decoy power-ups (world and HUD), the gear icons (grip shoes, legend shoes, soft glove, bell charm), and the apartment desk lamp and sill pot are CC0 sprites from Pixnote Pixels, SpritePilot, Alex's Assets, and the existing Kenney item cells, loaded by `item-cast.js` from `art/items/`. The older procedural drawings remain the fallback. Notices are in `CREDITS.txt` and `docs/ASSET_LICENSES.md`; hashes in `art/items/manifest-v2.json`.
