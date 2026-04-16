# System Shock 2

**Last updated:** 2026-04-15 | Sources: Lutris, ProtonDB, PCGamingWiki

## Compatibility

**ProtonDB:** platinum (strong, 54 reports)

## Known Working Configuration (Lutris)

**Environment variables:**
(none)

**DLL overrides:**
(none)

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

> System Shock 2 is a singleplayer first-person immersive sim, shooter and RPG game in the System Shock series.
> Configuration file(s) location
> For retail versions, install SS2Tool.
> Edit <path-to-game>\cam_ext.cfg.
> Change ;fov 90 to fov # (any number).
> Change ;force_windowed to force_windowed
> Change ;vsync_mode 0 to vsync_mode 0
> Change ;vsync_mode 7 to vsync_mode 7
> Change framerate_cap 100.0 to the desired FPS cap.
> Change ;phys_freq 60 to phys_freq 60
> If you want more than 250 FPS, change SlowFrame 4 to ;SlowFrame 4
> Disable bilinear texture filtering
> Change tex_filter_mode 16 to tex_filter_mode 0.
> Go to the installation folder.
> Add the line use_raw_mouse_input.
> Left-clicking or dragging does not work
> Small game window or black screen
> Open cam_ext.cfg using a text editor.
> Comment out and change multisampletype 8 to ;multisampletype 8
> Download and run the SS2Tool installer.
> At the Choose Components installation step, enable Safe Mode.
> Click Install and finish installing.
> UI too small on high screen resolutions
> Open cam_ext.cfg in a text editor.
> Uncomment the line ;d3d_disp_scaled_2d_overlay 64 by removing the semicolon.
> Poor performance on Mac wineskin version
> Find the System Shock 2.app and right-click on it. Click Show Contents and run Wineskin.app. In the Screen Options, you should see a checkbox that says Use Mac Driver instead of X11. Uncheck that box and that should fix the problem. If box is already unchecked then check it instead.
