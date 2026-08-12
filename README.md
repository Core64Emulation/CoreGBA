[README.txt](https://github.com/user-attachments/files/30964101/README.txt)
COREGBA v0.3.4 — RED NATIVE EMULATOR BRANDING
===============================================







<img width="1920" height="1080" alt="gbaemulator" src="https://github.com/user-attachments/assets/0e6ea1ab-8957-48cf-8e4b-bb7de2451399" />










WHAT CHANGED
------------
- The large native GBA handheld shown when no ROM is loaded is now RED instead of purple.
- The handheld screen now says CoreGBA instead of mGBA.
- The CoreGBA desktop/application icon is now a matching red version.
- The running native emulator title bar keeps the CoreGBA name.
- The running native emulator window/taskbar icon is switched to the same CoreGBA red icon.
- The previous green/red controller-mapping artwork remains in place.
- No installer/setup files were changed in this package.

NATIVE APPLICATION
------------------
CoreGBA.exe opens the native emulator directly. There is no HTML/CSS/JS frontend,
Electron, WebView, dashboard, library shell, or extra launcher window.

The native mGBA 0.10.5 runtime remains the emulation backend. CoreGBA applies its
branding directly to the local native runtime before it starts.

NORMAL LAUNCH
-------------
CoreGBA.exe
CoreGBA.exe "C:\Games\Example.gba"

FOLDERS
-------
Core\    Native emulator runtime.
Games\   Optional folder for legally-owned GBA dumps.
Data\    Reserved CoreGBA data.
Source\  CoreGBA source/build files and embedded native branding resources.

IMPORTANT
---------
CoreGBA does not include ROMs, Nintendo BIOS files or commercial game content.
mGBA remains an independent open-source project governed by its own license.
See THIRD_PARTY_NOTICES.txt.
