### Build: 2020050701
#### app: v7.5.2
#### Magisk: v20.5-6522443c

- aa8b2310: Modernize resetprop with fancy C++
- c113f854: Fix overlay.d on SAR again

#### Most recent 20 previous commits:

- 87de0e7a: Force remove AVB for 2SI since it may bootloop some devices
- 85755e30: Tone down our DTB patching
- 02dc1172: Revert DTB patches to in-place binary patches
- dbf8c412: Force init to load fstab from file in 2SI
- 8c4fd759: Strip Huawei specific logic
- 23dc19ad: scripts: don't abort if /vendor fails to mount
- 0c99c4d9: More complete support for fstab in dt
- 8ab04533: Workaround realpath FORTIFY crashes
- a8d0936e: Update BusyBox
- 4e349acb: Build libselinux without ANDROID defined
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
