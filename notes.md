### Build: 2020020801
#### app: v7.5.2
#### Magisk: v20.4-fbd17bc3

- 4dd8d75c: Update scripts
- e5f50bb7: Update busybox
- 45d5b4be: scripts: recovery addon.d-v2 and env fixes - recovery addon.d-v2 requires /system and /system_root stay mounted - find OUTFD from recovery update_engine for addon.d-v2 output - fix finding OUTFD on addon.d failure with toybox ps - simplify heredoc creation - update to longer apex BOOTCLASSPATH - save and restore any mountpoint symlinks encountered

#### Most recent 20 previous commits:

- ed58cf95: Add missing string resources
- ec26bc5a: Corrections for Romanian
- 84e4bd3d: Move readlinkat fix into xwrap
- 0ecfb63c: Fix crash during boot in x86 platform
- ebdd6ec4: Fallback to getprop to get SDK_INT
- 05867603: Polish translation - Minor corrections/improvements
- d535f244: Corrected translation
- 613d4682: Update
- 041355f1: Final Language Update PT-BR
- 6977dc08: Fixed texts being incorrect if injected from context
- d3dffe81: Updated legacy theme to match error color instead of having separate secondary color
- 6812f9d2: Updated su request dialog to match overall app theme
- 555e7cc9: Fixed dialog not being centered
- 61805580: Add support for genfscon sepolicy rules
- cf589f8c: Fix error loading libsqlite.so
- e864919c: Jellybean supports modules
- c72d83b6: Update docs
- f2d2f28e: scripts: fixes for Tegra partition naming + bootsigner on Android 10 - adjust mount scripts to support SOS, APP and CAC Tegra partition naming (vendor is still vendor, oddly) - -Xnodex2oat is removed on Android 10 in AOSP (despite it still erroneously showing in dalvikvm --help); older devices will still run safely without it - Android 10 dynamically linked binaries need APEX mounts and variables so add this to recovery_actions/cleanup (thanks @Zackptg5) - clean up known systemless root leftovers because we're helpful
- a7435dad: magiskboot: fix lzop detection
- 793f0b60: init: fix Tegra "APP" /system partition mounting - thanks rootfan in https://github.com/topjohnwu/Magisk/issues/2063#issuecomment-573232567
