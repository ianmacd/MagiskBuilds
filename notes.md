### Build: 2020030901
#### app: v7.5.2
#### Magisk: v20.4-11486ff2

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
- bf2c5ce3: Updated Polish translation
- 65c510a2: Update Romanian strings
- 6fbc38d7: Add more notice/messages
- 200bf993: Show unsupported message when running low versions
- 38af82e1: Update AS
- fc05f377: Update env fix handling logic
- 5c0e8638: Add test button toggle in code
- 64f5ff54: Use global A/B detection
- 75877711: Improve application startup
- b90e0430: Don't do layered cards

#### Most recent 20 previous commits:

- 0ce7da1b: Upgrade AGP
- e6464c5c: Fixed module filter list not respecting single column layout
- c6b3f06b: Cleanup stuffs
- 581419b6: Update dependencies
- 696ab677: New pre-init magic mount implementation
- 0d229dac: Support Android 11 SELinux paths
- 3b8ea599: Fix switch_root implementation
- 3e70a61e: Fix strings
- 76f35d02: Update strings-es
- 356b417a: Update RU strings
- 56147a80: Updated Translations
- 91728991: Update Strings-es STUB version
- 0f7e59d2: Update + Fixes ca-strings
- f33028c6: some changes
- f9149ad4: French translation
- 0d7474cc: Fix all locale issues
- 1e7e06d1: Proper canary version detection
- 8453282f: Improve flash console screen
- 40f971d1: Add entrypoint for testing
- ce7cb1ee: Remove device section
