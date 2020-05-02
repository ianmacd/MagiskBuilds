### Build: 2020050201
#### app: v7.5.2
#### Magisk: v20.5-4e699190

- a8d0936e: Update BusyBox
- 4e349acb: Build libselinux without ANDROID defined
- e51ffef8: RECOVERYMODE should not always be overridden on legacy SaR devices.

#### Most recent 20 previous commits:

- 947e3b06: Use template to get lambda for RAII
- 5fd574a1: Fix --remove-modules command
- 03c10538: scripts: fix persist out-of-space copying sepolicy.rule - bugged TWRPs were filling persist with recovery logs, so clean those as a potential workaround - abort module install if sepolicy.rule fails to copy, since 99% of the time the module wouldn't include it if it could function without it
- c7ed0ef5: Fix SAR support for overlay.d
- 2aede977: scripts: fix find_block false positives /dev/log/kernel and /dev/BOOT - try /dev/block first with full depth to catch all platform/soc variations to the by-name directory, and the new dynamic partition /dev/block/mapper - next try uevent for block devices as before - lastly try /dev with maxdepth 1 (immediate directory) to find /dev/bootimg, /dev/recovery, etc. while avoiding /dev/log/kernel - move bootimg higher in the list than boot so /dev/bootimg gets found first and avoids /dev/BOOT - recovery_a/_b now also exists - minor touch-ups for readability and consistency
- 9b8a5e9b: scripts: add author name back to module install banner print
- 0f910f2d: scripts: ensure system is able to be mounted rw before attempting - this is needed for installations on Lineage 17.1 Recovery (AOSP Q) for logical partition devices, which uses /dev/block/mapper to stage the partitions
- 15f15510: Rewrite skel_node mounting and construction logic
- 2468f5a6: Fix custom sepolicy patches
- 945a52a9: Handle extremely rare edge case
- 486b2c82: Disable kmsg rate limiting
- 800b7f43: Bump min module Magisk version to v20.0
- 8ca5a048: Support system_ext
- 44b7a3c3: Only run bootsigner on Android 5.0+
- 554ebe72: Skel dest could not exist
- d7b87fcb: Add untrusted_app_29 for Android 11
- c94f9e1c: Use a binary that exists on all devices for hijacking
- 68532fad: Update SAR detection method for Android 11
- e219867c: Hijack another binary for 2nd stage
- 6caba51e: RECOVERYMODE should not always be overridden on legacy SaR devices.
