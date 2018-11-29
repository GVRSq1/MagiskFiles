## v17.4/v6.0.2 rev.24

### Magisk
- Switch from deprecated AUDITDENY to DONTAUDIT
- Temporarily suppress warnings when applying Magisk rules
- Remove all dontaudit in magisk rules
- Support removing redundant avtab nodes
- Remove '--install'
- Update magiskpolicy

### Selinux
- Add function: avtab_remove_node
- Add Android M policy compatibility
- Add NDK support to libsepol
- libsepol: ibpkeys.c: fix printf format string specifiers for subnet_prefix
- gui: remove html_util.py
- dbus: remove deprecated at_console statement
- libselinux: selinux_restorecon: fix printf format string specifier for uint64_t
- python: replace aliases with corresponding type names
- libsepol: mark permissive types when loading a binary policy
- libselinux: fix overly strict validation of file_contexts.bin
