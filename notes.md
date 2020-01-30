### Build: 2020013001
#### app: v7.5.2
#### Magisk: v20.4-35458567

- 8a6b3644: Strip only debug and verbose logging
- 8ca169a4: Restore additional paddings for fdt
- 003a8a9f: scripts: fixes for Tegra partition naming + bootsigner on Android 10 - adjust mount scripts to support SOS, APP and CAC Tegra partition naming (vendor is still vendor, oddly) - -Xnodex2oat is removed on Android 10 in AOSP (despite it still erroneously showing in dalvikvm --help); older devices will still run safely without it - Android 10 dynamically linked binaries need APEX mounts and variables so add this to recovery_actions/cleanup (thanks @Zackptg5) - clean up known systemless root leftovers because we're helpful
- ab570c8e: magiskboot: fix lzop detection
- 402147da: init: fix Tegra "APP" /system partition mounting - thanks rootfan in https://github.com/topjohnwu/Magisk/issues/2063#issuecomment-573232567

#### Most recent 20 previous commits:

- 1d89fe50: Fix manager hiding
- 788db036: Don't use Zopfli
- c38c473e: Fix compile error
- aef1f8f7: Update strings.xml
- 83f97672: Update strings.xml
- 3e0352ee: Update strings + Corrections
- 28faff64: Fix French translation
- d0112f98: Cleanup classes
- 9c4c310f: Fixed messages on modules screen replicating indefinitely
- 7bf7bfb9: Updated Flash / SuRequest activities with app themes
- fbe776db: Update Turkish language
- 1e2de1bb: Preserve everything in package 'a'
- e395c944: Upstream system_properties
- 30286f0e: Fixed translations
- 60ee7428: Update RO strings
- a913ede4: French translation update
- 95925837: Language update PT-BR
- ad49d3ad: Update Simplified Chinese Translation
- 21ee73c2: Translation Correction
- f5d0cc9f: Updated helper lists so they are lazily populated
