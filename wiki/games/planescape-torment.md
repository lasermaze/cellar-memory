# Planescape Torment

**Last updated:** 2026-04-15 | Sources: Lutris, PCGamingWiki

## Compatibility

**ProtonDB:** No ProtonDB data available

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

> Planescape: Torment is a singleplayer bird's-eye view and isometric RPG game in the Planescape: Torment series.
> There are several recommended mods containing bug fixes, widescreen support, restoration of cut content and tweaks to some of the more annoying aspects of the game (such as the hit-points per level being constant instead of completely random). It is recommended that you follow this guide, as the mods require that you install them in a certain order. GOG.com version users can skip to step 3a.
> Delete, move or rename the following file: genmovB.bif.
> Configuration file(s) location
> Go to the configuration file(s) location.
> Find Full Screen=1 and change it to Full Screen=0.
> Add Torment.exe to list of DxWnd applications, and open its properties.
> Under the Main tab, set window size to W=640 H=480 (integer multiples allowed), and check "Terminate on window close".
> (Optional) Under the Mouse tab, check "Keep cursor within window".
> Under the DirectX tab, Enable "Compensate Flip Emulation".
> Find Maximum Frame Rate and change the value to 60.
> Install unofficial patch (DDraw Fix).
> If the patch causes cursor trails to appear, open setup-pst-drawfix.tp2 with a text editor and delete the following lines: PATCH_IF( offset !
