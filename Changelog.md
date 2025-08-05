ocmtoc changelog
================

#### v1.0.4
- Rebased to cctools 1024.3
- Added `__SBAT` support, thx @dakanji
- Added `--fullversion` argument, thx @dakanji

#### v1.0.3
- Verify `__RO_RELOCS` protection level
- Fixed DebugDirectoryEntry size

#### v1.0.2
- Mark `.reloc` and `.debug` as NX
- Added `-require_read_only_relocs` argument
- Renamed `__RELOC_FIX` to `__RO_RELOCS`

#### v1.0.1
- Added support for the `__RELOC_FIX` marker segment

#### v1.0.0
- Initial version based on cctools 973.0.1
- Fixed section permissions causing executable data
- Added constant rodata support
- Added `--version` argument
