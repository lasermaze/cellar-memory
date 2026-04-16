# Thief II

**Last updated:** 2026-04-15 | Sources: Lutris, ProtonDB, PCGamingWiki

## Compatibility

**ProtonDB:** gold (strong, 53 reports)

## Known Working Configuration (Lutris)

**Environment variables:**
(none)

**DLL overrides:**
- openal32: b

**Winetricks:**
(none)

## Fixes (WineHQ / PCGamingWiki)

**Environment variables:**
(none)

**DLL overrides:**
(none)

**Winetricks:**
(none)

**INI changes:**
(none)

## Community Notes

### PCGamingWiki

> Thief II: The Metal Age is a singleplayer first-person stealth and immersive sim game in the Thief series.
> The game was the final title by Looking Glass Studios, as the studio would shut down a mere two months after release.
> The retail version of the game has significant issues running out-of-the-box (e.g. stability, rendering, cutscene codec breaking after a few sessions). Several unofficial patches have been created over the years, most notably the NewDark engine patch and T2Fix.
> NewDark is a fan-developed update to the Dark Engine that lets Thief 2: The Metal Age run on modern systems.
> T2Fix is an "upgrade" patch that updates the game with NewDark which improves compatibility on modern systems, alongside other features.
> Open <path-to-game>\cam.cfg using a text editor.
> Add the line skip_intro to the file and save it.
> Open <path-to-game>\cam_ext.cfg using a text editor.
> Change ;d3d_disp_scaled_2d_overlay 64 to d3d_disp_scaled_2d_overlay 64.
> Configuration file(s) location
> Install NewDark and set the desired resolution in-game.
> If the proper FOV is not detected, edit it in <path-to-game>\cam_ext.cfg.
> Change ;fov 90 to fov ## with the desired FOV.
> Save the changes and relaunch the game.
> Open <path-to-game>\cam_ext.cfg.
> Change ;force_windowed to force_windowed.
> Save the changes and set the chosen resolution in-game.
> Change ;vsync_mode 0 to vsync_mode 0 and save the changes.
> Change framerate_cap 100.0 to framerate_cap ### with the desired framerate.
