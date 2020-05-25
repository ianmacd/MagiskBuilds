### Build: 2020052501
#### app: v7.5.2
#### Magisk: v20.5-73d9457b

- cd6eca1d: Optimize match-all-type rules
- 951273f8: Cleanup some implementations
- 51eeb89f: Allow consecutive points
- 0efa73d9: Update selinux libs
- 63512b39: Update NDK to r21b
- f392ade7: Rewrite sepolicy.c in C++
- 0236ab88: Several statement parsing improvements
- d4baae41: Modernize magiskpolicy

#### Most recent 20 previous commits:

- e02e46d0: Detect volume down key combo for safe mode
- 3c04dab4: magiskhide: fix late_prop_key setprop, reorganize props slightly
- fc1844b4: Update policy for handling /data/adb
- 99ef2062: Remove unused code
- 4497e0aa: Don't expose module_list
- c3e045e3: Use daemon state to determine late prop hiding
- 501d3e6c: Maintain global daemon status
- b27b9c1d: Minor code changes
- f7d3d1ee: Increase post-fs-data mode to 40 secs
- 0d72a4c8: Fix compile error
- dbdb0a25: Move late props to boot complete
- 18a09703: Updated Georgian translation
- bc6a14d3: Remove property ro.build.selinux
- 97db49a5: Move vendor property manipulation to late start
- eca21686: Guard magiskhide state with mutexes
- 1bcef387: Fix German translation
- aac6ad73: Fix collect modules
- 122b4d66: Move Android logging out of libutils
- 0f8f4e36: Update collect log logic
- 3733b589: native: fix slower build on non-Windows platforms
