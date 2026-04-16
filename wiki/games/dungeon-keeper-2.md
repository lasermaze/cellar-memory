# Dungeon Keeper 2

**Last updated:** 2026-04-15 | Sources: Lutris, ProtonDB, PCGamingWiki

## Compatibility

**ProtonDB:** gold (low, 6 reports)

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
- direct_mode: n

**Winetricks:**
(none)

**INI changes:**
(none)

## Community Notes

### PCGamingWiki

> Dungeon Keeper 2 is a singleplayer and multiplayer bird's-eye view and first-person building and RTS game in the Dungeon Keeper series.
> The game received multiple official patches after release, the last two of which included new creatures, but inadvertently broke the enemy AI and creature spawns in some levels.
> On modern systems, the game requires the General Improvement Mod (GIM) and the level fix to reduce compatibility issues and bugs.
> Flame is an unofficial patch based on a community driven decompilation of the game. It features improved compatibility with modern Windows versions and overall stability, fixes a plethora of bugs (including version specific bugs), and adds support for mouse wheel controls, widescreen, windowed mode, and a much wider selection of resolutions. It also adds better modding support, the ability to tweak GOG-exclusive fixes, a custom launcher with more settings than officially offered.
> Unzip it into <path-to-game> and overwrite existing files.
> Go to <path-to-game>\Data\Movies.
> Delete or rename the following files: BullfrogIntro.tgq, INTRO.TGQ.
> Configuration file(s) location
> Open the Registry Editor and browse to HKEY_CURRENT_USER\Software\Bullfrog Productions Ltd\Dungeon Keeper II\Configuration\Video. If the \Configuration\Video key path does not exist, create it manually.
> Change the Screen Height and Screen Width string values to the desired resolution (decimal base).
> Use SBS by default, or with direct_mode=sbs.[5]
> For TAB set direct_mode = tab.
