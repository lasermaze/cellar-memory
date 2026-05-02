# Homeworld

**Last updated:** 2026-05-02 | Sources: Lutris, PCGamingWiki

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

> ### Hardware acceleration fix for Windows 8 and above
> For Windows 8.x, 10, and 11, use the Homeworld hardware acceleration fix This solution force-enables compatibility mode for Windows NT 4.0 (Service Pack 5) which is not a selectable option in newer versions of Windows, but is still present in the backend. Alternatively, this process can be completed manually.
> Manual fix Depending on whether the program is installed for one user or the whole machine, navigate to either: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers HKEY_CURRENT_USER\Software\Microsoft\Windows NT\CurrentVersion\AppCompatFlags\Layers Double-click the Homeworld registry entry. Type NT4SP5. Save changes.
> In-game general graphics settings.
> In-game advanced graphics settings.
> Graphics feature State WSGF Notes Widescreen resolution See Widescreen resolution. HUD doesn't scale on higher resolutions. Multi-monitor Ultra-widescreen 4K Ultra HD Field of view (FOV) Determined by the aspect ratio (see Widescreen resolution). Windowed See Windowed. Borderless fullscreen windowed See Windowed. Anisotropic filtering (AF) See the glossary page for potential workarounds. Anti-aliasing (AA) See the glossary page for potential workarounds. Vertical sync (Vsync) Use the command line parameter /triple 60 FPS and 120+ FPS No frame rate cap. Ships and other elements move and update at a locked frame rate. High dynamic range display (HDR) See the glossary page for potential alternatives.
