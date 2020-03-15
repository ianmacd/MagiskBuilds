### Build: 2020031501
#### app: v7.5.2
#### Magisk: v20.4-77b8b71b

- 72f6770d: Fix string resources
- 7da35e54: Extract full module installation logic
- 7768274b: Fix build issue
- 33f00665: Update README
- 612b51d4: Disable MagiskHide by default
- 8101f3f6: Set proper permissions
- e3c8d723: Add linebrake notice for module.prop
- 45798257: Updated Georgian strings
- ef91c33f: Update RU strings
- 511d5993: Update Strings-es.xml
- 9f4958e8: Updated safetynet success color to primary
- c07775f5: Add missing ro.vendor(.boot).warranty_bit props
- e261579e: Use standalone mode in boot scripts

#### Most recent 20 previous commits:

- cf54cad3: deleteprop -> delprop
- a0998009: Small native code reorganization
- d6fdbfe9: Utilize standalone mode for emulator.sh
- 07228279: Update Slovak translation
- 6877ef79: Add strings
- a3809648: Update Romanian
- df15606b: prop compare fix
- 4dc0d136: Xiaomi cross region flash hacks
- 541fa5cb: Update dependencies
- ab9442d4: Fixup mounting system on Lineage Recovery
- f5c099e9: scripts: fix addon.d after merge to trampoline - pass addon.d arguments through trampoline or nothing will happen - exit immediately after handing over from trampoline - better grep for recovery OUTFD which should work in all cases - output to logcat when booted and no binaries are found - use /postinstall/tmp path to call functions from addon.d-v2 in progress - remove unnecessary check for $MAGISKBIN since we're already executing from within it - make sure we're not in $TMPDIR again before we delete it - use $MAGISKBIN wherever possible in case it ever needs to be changed
- 9582379e: Fix error patching boot.img
- db9a4b31: Update scripts to use BusyBox standalone mode
- 409cb06e: Fixed layout not reacting to nested scroll on su screen
- 88d917b6: Added permission check for installing/downloading modules
- faf077b4: Min ver is 19.0, don't need legacy commands
- ee1f45aa: Add new commandline option to get tmpfs root
- 915fd302: Small string resource reorganization
- 642788ab: Typo fix.
- 3cd11dd9: Update Slovak translation
