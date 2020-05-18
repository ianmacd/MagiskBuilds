### Build: 2020051802
#### app: v7.5.2
#### Magisk: v20.5-0ef6c860

- 99ef2062: Remove unused code
- 4497e0aa: Don't expose module_list
- c3e045e3: Use daemon state to determine late prop hiding
- 501d3e6c: Maintain global daemon status
- b27b9c1d: Minor code changes
- f7d3d1ee: Increase post-fs-data mode to 40 secs
- 0d72a4c8: Fix compile error
- dbdb0a25: Move late props to boot complete

#### Most recent 20 previous commits:

- 18a09703: Updated Georgian translation
- bc6a14d3: Remove property ro.build.selinux
- 97db49a5: Move vendor property manipulation to late start
- eca21686: Guard magiskhide state with mutexes
- 1bcef387: Fix German translation
- aac6ad73: Fix collect modules
- 122b4d66: Move Android logging out of libutils
- 0f8f4e36: Update collect log logic
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
