## v17.4/v6.0.2 rev.1

### Magisk
- Revert "Properly support boot image header v1"
- Make a copy of logcat and use that instead
- Fix Dark theme to display cards as slightly lighter than background as per Material Design standards. Also redirect colors to app as opposed to calling on framework
- Update changelogs
- Ask permissions to read internal storage
- Update encryption detection for determining default flags
- Always ACK before doing anything
- Try to flush database before uninstalling
- Remove support for Magisk lower than 1500
- Remove unnecessary instruction from Defex hexpatch
- Properly support boot image header v1
