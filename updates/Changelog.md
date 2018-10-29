## v17.4/v6.0.2 rev.5

### Magisk
- Skip files when scanning modules
- daemon.c uses external flags
- Upgrade snet extension
- Upgrade Bouncycastle
- Hint what FBE means in details.md
- Remove redundant semicolon
- Revert "Make dark theme cards slightly darker"
- Fix and prevent crashes
- Retry db construction if first time failed
- Buffer OutputStream to prevent broken pipe error
- Add missing flags and move debug logging logic to libutils
- Make sure magisklogd is properly initialized
- Sort Policies before returning
- Update donation link
- Only allow device owner to hide/restore Magisk Manager
- Micro optimizations
- Optimize logging in Magisk Manager
- Default to cmdline logging
- Fix bug when query database with specific keys
- Handle magisk.db completely natively
- Prepare for new database implementation
- Update sqlite header
