PC Locker
Fullscreen workstation lock overlay for Windows.
PC Locker is a lightweight Windows utility that displays a fullscreen semi-transparent overlay to lock the workstation, blocking all keyboard input and preventing accidental interaction with open applications, settings, or parameters.

Features

Fullscreen overlay on all connected monitors simultaneously — no monitor left unprotected
Low-level keyboard hook (WH_KEYBOARD_LL) — blocks all keystrokes including Win key, Ctrl+Alt+Del, Ctrl+Shift+Esc, and Alt+Tab
Underlying applications remain visible and keep running normally
Configurable unlock keyboard shortcut (default Ctrl+Alt+L)
Password unlock — dialog opens on the monitor where the button was clicked
Configurable overlay opacity (0.2 to 0.85)
Single portable .exe — no installation required
Also available as an installer

Use cases

Locking a media server during a live show to prevent accidental input
Securing an unattended workstation during breaks
Protecting open applications in recording sessions or broadcast environments

How to use

Launch PCLocker.exe — UAC elevation is requested automatically (required for the keyboard hook)
The control panel appears at screen centre
Click Lock PC to activate the overlay
Unlock with the keyboard shortcut or click Unlock with password on any screen

Distribution
Two versions are available in the Releases tab:

Portable — single .exe, no installation. Drop it anywhere and run.
Installer — standard Windows setup. Installs and creates a Start Menu shortcut.

System requirements

Windows 10 / 11 (64-bit)
Administrator privileges (auto-requested on launch)

Technical notes

Configuration is saved to locker_config.json in the same folder as the executable (portable version)
Deleting locker_config.json resets the user password to the default value (password) — change it before deploying
Win+L (Windows lock screen) is not blocked by design — it can be used as an emergency exit
Full-screen exclusive applications may render above the overlay on secondary monitors

Version
See the Releases tab for the full version history.

Made by Riccardo Nessi — Stage Tools
