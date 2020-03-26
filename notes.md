### Build: 2020032601
#### app: v7.5.2
#### Magisk: v20.5-b8d6ff08

- 69076517: Updated flash screen so it's a fragment
- fc2d0246: Added requesting navigation being hidden when showing alternative view
- bb9c362b: Added back button for ModuleFragment when displaying filter
- 51402e68: Fixed log not displaying back button when alternative view is shown
- 1b881322: Updated the app to use navigation components instead of custom solution
- 922e36cf: Updated the width of bottom navigation
- edff0946: Added log as primary fragment
- aa72a080: core: clean up /data/adb/magisk.img, etc. as well
- 2a93d1c6: Update shields.io URL for caching
- 6b2f2371: Add live download counts

#### Most recent 20 previous commits:

- 375ab93e: Update logo.png
- d5962e9d: Update README.MD
- ffaa264b: Update documentation
- ba7cb473: Make version reporting consistent
- 48d417f9: Add symlink for backwards compatibility The native code has to run with an old verison of Magisk Manager, add this back so things will work properly.
- df4db6bf: Added Dutch translation for stub
- b8ef491b: Updated Dutch translation
- ea1ebb8d: Polish translation - fix missing string
- 91b6d285: scripts: add nand/mtd support to uninstaller
- d7cd1b37: add missing flags
- 160ff7bb: Update abort function to cleanup module installs
- 31142180: Fix strings
- 38b0fa04: Small translation fix
- 29817245: update de strings
- 925fe6f1: Update RU strings
- 93fd574b: 更新繁體中文字串
- 0de88bcb: Polish translation - add missing strings, small improvements.
- 0b70bd2b: scripts: make remaining header/section dividers uniform - match other recent formatting updates from topjohnwu
- 84ecba46: scripts: fix addon.d again by ensuring all arguments get passed - /proc/$$/cmdline is \0 terminated argument strings except for the last argument which has no terminus, so the last argument was being dropped by `while read` which requires input to be \n terminated - switch to a for loop, which will use the \n delimiter but also read the last argument; all arguments are still protected by quoting - clean up potentially breaking recovery env since $OLD_PATH no longer exists
- f7142e69: Fix module install in util_functions.sh
