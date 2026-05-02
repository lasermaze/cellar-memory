# Unreal Tournament 2004

**Last updated:** 2026-05-02 | Sources: Lutris, ProtonDB, PCGamingWiki

## Compatibility

**ProtonDB:** gold (strong, 51 reports)

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
- ut2004.ini: ReduceMouseLag=False

## Community Notes

### PCGamingWiki

> Unreal Tournament 2004 is a singleplayer and multiplayer first-person action, FPS and shooter game in the Unreal series.
> D3D8 to D3D9 wrapper The 64-bit build of the game comes with an experimental D3D9 renderer, which offers better performance with modern hardware, but has issues such as broken graphical effects. Therefore, it is recommended to use the following unofficial D3D8 to D3D9 wrapper with the 32-bit version of the game, which will display the whole graphical featureset of the game combined with better performance. Download latest version of d3d8.dll from https://github.com/crosire/d3d8to9/releases Extract to <path-to-game>\System directory.
> Disable "Reduce mouse lag"[4] The game comes with an option to "reduce mouse lag" checked by default, however this option actually functions like a waitstate for the GPU and was put in place to help with input lag in the sub-30 FPS range, which was not uncommon for systems of the time of the game's release. On modern systems this option often cuts FPS in half without any benefits, so it is recommended to disable it. This may also solve some reported Windows 10-specific issues. Open <path-to-game>\System\ut2004.ini Find ReduceMouseLag and change each occurrence to ReduceMouseLag=False. Save and close the file.
> ### SDL Compatibility Layer (Linux)
> libsdl2-dev package is required for Ubuntu/Debian based distro (For other distros you need sdl2 package itself) for compiling. Be sure that the main library is also installed.
