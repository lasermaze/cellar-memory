# Quake III Arena

**Last updated:** 2026-04-15 | Sources: ProtonDB, PCGamingWiki

## Compatibility

**ProtonDB:** gold (strong, 36 reports)

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

> Quake III Arena is a singleplayer and multiplayer first-person action, FPS and shooter game in the Quake series.
> On August 19, 2005, id Software released the source code.[1]
> Configuration file(s) location
> Launch the game at least once then close it.
> Open <path-to-game>\baseq3\q3config.cfg with a text editor.
> Change the following lines to set the resolution. seta r_customwidth "XXXX" seta r_customheight "XXXX"
> Change the following line to this value. seta r_mode "-1"
> Launch the game at least once, then close it.
> Go to the configuration file(s) location.
> Open q3config.cfg with a text editor.
> Change the following line to the desired value: seta cg_fov "XX"
> The game crashes on exit (Steam)
> Right-click the game in the Steam library.
> Uncheck Enable the Steam Overlay while in-game.
> Find the line r_overBrightBits 2.
> Launch Quake 3 with either quake3e-vulkan.x64 or quake3e-vulkan.
> Open the developer console (default key: tilde `).
> Type r_fbo 1, and press Enter.
> Then either type vid_restart and press Enter again, or close and restart Quake3e Vulkan to apply changes.
> After starting the game, open the console, write /r_subdivisions -1; r_lodbias -1 then press Enter. The first command increases world geometry detail, whereas the second command uses high-quality models regardless of the viewing distance.
> ↑ 1.0 1.
