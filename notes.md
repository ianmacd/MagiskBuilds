### Build: 2020051701
#### app: v7.5.2
#### Magisk: v20.5-3b8640c1

- 1bcef387: Fix German translation
- aac6ad73: Fix collect modules
- 122b4d66: Move Android logging out of libutils
- 0f8f4e36: Update collect log logic

#### Most recent 20 previous commits:

- 3733b589: native: fix slower build on non-Windows platforms
- 6a2e781d: magiskhide: add vendor.* props
- c6569ce0: Fix service scripts
- a62bdc58: Use env variables to enable standalone mode
- 91200949: Revert accidental build script change
- a5d7c41d: Support Safe Mode detection
- 232ae2a1: Update resetprop to partially use system impl
- aa8b2310: Modernize resetprop with fancy C++
- c113f854: Fix overlay.d on SAR again
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
