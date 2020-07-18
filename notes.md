### Build: 2020071801
#### app: v7.5.2
#### Magisk: v20.5-bc1c0629

- 07f712a1: Always show hidden apps
- c7044b0d: Remember show system app toggle in MagiskHide list
- 15866cfb: Fix incorrect command
- 4c257062: Make SettingsItems make much more sense
- 113eec59: Request storage rw for saving logs
- f7abc03d: Move copy util_functions.sh from Python scripts to gradle
- ef3f188a: bel
- dd62fe89: Use CallbackList for collecting STDOUT in flash screen
- ec2d7d77: Reduce usage of ObservableField
- 6c6368fd: Reduce usage of delegation

#### Most recent 20 previous commits:

- ba31c6b6: Use coroutines instead of raw executors
- cad189d2: Remove unnecessary indirection
- 7cf3da1b: Update implementation to use new methods
- 45fabf8e: Update SettingsItems
- 2c12fe6e: More efficient databinding
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
