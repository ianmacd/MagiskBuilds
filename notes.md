### Build: 2020032301
#### app: v7.5.2
#### Magisk: v20.5-0c97f72e

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

#### Most recent 20 previous commits:

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
- ed7e5608: Fix ensure_bb implementation
- 47e50e85: scripts: add nand/mtd support to installer - Magisk's busybox now has nanddump, flash_eraseall and nandwrite, so use these to support character devices
- 72f6770d: Fix string resources
- 7da35e54: Extract full module installation logic
- 7768274b: Fix build issue
- 33f00665: Update README
- 612b51d4: Disable MagiskHide by default
- 8101f3f6: Set proper permissions
- e3c8d723: Add linebrake notice for module.prop
- 45798257: Updated Georgian strings
