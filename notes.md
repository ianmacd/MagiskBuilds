### Build: 2020013101
#### app: v7.5.2
#### Magisk: v20.4-49f6baeb

- c72d83b6: Update docs
- f2d2f28e: scripts: fixes for Tegra partition naming + bootsigner on Android 10 - adjust mount scripts to support SOS, APP and CAC Tegra partition naming (vendor is still vendor, oddly) - -Xnodex2oat is removed on Android 10 in AOSP (despite it still erroneously showing in dalvikvm --help); older devices will still run safely without it - Android 10 dynamically linked binaries need APEX mounts and variables so add this to recovery_actions/cleanup (thanks @Zackptg5) - clean up known systemless root leftovers because we're helpful
- a7435dad: magiskboot: fix lzop detection
- 793f0b60: init: fix Tegra "APP" /system partition mounting - thanks rootfan in https://github.com/topjohnwu/Magisk/issues/2063#issuecomment-573232567
- 5b56ca7f: Use MAX_FDT_GROWTH instead of hardcode value
- 5c988510: Preserve fdt paddings
- 29062484: Reorganize dtb code

#### Most recent 20 previous commits:

- 497efc9f: Make scrambled text prettier
- 19d76b63: Fix de strings
- 4875def3: Complete and improve French translation
- 155c0e36: Update Slovak language
- 00ea15dc: Update and fix Polish language
- f04c4cb7: Update de strings
- 6e477769: Change recreate logic
- 4638fdf2: Fixed dialog content being squished unnecessarily
- 0783d385: Removed security note
- cf918e7d: Updated text "variant" transparency
- 1ba9faf3: Added legacy theme (Fraxure)
- 6e48294f: Removed unnecessary files and merged styles
- dea607b1: Small SignAPK improvements
- e938e717: Refactor PatchAPK code
- 2eed09ef: Upgrade AS
- 8a6b3644: Strip only debug and verbose logging
- 1d89fe50: Fix manager hiding
- 788db036: Don't use Zopfli
- c38c473e: Fix compile error
- aef1f8f7: Update strings.xml
