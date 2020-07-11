### Build: 2020071101
#### app: v7.5.2
#### Magisk: v20.5-91b099bb

- b41b2283: Rename package
- e8e7cd50: Simply redirect isConnected ObservableField
- 78734339: Remove RxJava as dependency
- 52d19d3e: Roll our own NetworkObserver
- 6348d0a6: Remove more code using RxJava
- f7a650b9: Clear up RxJava from ViewModels
- a97d278b: Remove RxBus
- 8647ba47: Remove more RxJava
- 4631077c: Call the correct constructor
- 18dab28c: Remove usage of KObservableField
- 8ffbffdd: Update SuRequest handler
- f191db2f: Allow ViewModel to opt-out RxJava
- dc8f0f6f: Bug fixes in modules fragment
- 01a43b03: De-Rx ModuleViewModel
- 86db0cd2: Load installed modules with coroutine
- ae6dd50c: Fix RepoUpdater force refresh bug
- 77032ece: Load repos with coroutine

#### Most recent 20 previous commits:

- 820427e9: Have some fun with Kotlin Coroutines
- 89e11c9c: Minor changes in flash viewmodel
- 05cf53fe: Merge files
- 97b72a59: Revert to old SElinux rules on pre 8.0 devices
- 7922f652: Welcome Gradle Kotlin DSL
- 67f79354: Restructure project
- 9348c5ba: Fix build script
- 0f7caa66: Remove usage of grid layouts
- bd14994e: Update Polish translation
- 08818e85: Remove force_pm_install
- 706eba32: Add release notes to the install fragment
- f6a2b1c8: Minor gradle script changes
- c2e66220: Update README
- 53904b06: Use gradle magic to optimize resources
- cef14d45: Fix release build XLint error for translations
- 73203a55: Use fancy NestedScrollView for Magisk logs
- 397f7326: Update SafetyNet UI to show evalType
- 4bbd7989: Update snet extension
- a0b47f3c: Precompute TextView in I/O thread for performance
- 89e9e7c1: Simplify UI code for Magisk logs
