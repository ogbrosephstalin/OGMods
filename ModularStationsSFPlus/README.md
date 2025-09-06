# Example ContentLib Mod

This template was obtained from the
[ContentLib Documentation](https://docs.ficsit.app/contentlib/latest/index.html).

Before you release a mod from this template,
you must switch over some files to use your mod reference
instead of the current value of `ExampleContentLibMod`

Once you have decided on a
[Mod Reference](https://docs.ficsit.app/satisfactory-modding/latest/Development/BeginnersGuide/index.html#_mod_reference),
you will have to:

- Rename the folder (from `ExampleContentLibMod` to `YourModReferenceHere`)
- Rename the .uplugin file inside the folder
  (from `ExampleContentLibMod.uplugin` to `YourModReferenceHere.uplugin`)
- (Optional) Replace `/Resources/Icon128.png` with image of your choice for the mod icon

Inside the .uplugin file:

- Edit the FriendlyName, Description, and CreatedBy fields to your preferences
- Replace the "SmlVersionReplaceMe" with the latest version number of SML found here:
  <https://ficsit.app/sml-versions>, so that it follows the format `^The.Number.Here`.
  Once you're done, that section will look similar to this:

```json
{
  "Name": "SML",
  "Enabled": true,
  "SemVersion": "^3.7.0"
},
```

- Replace the "ContentLibVersionReplaceMe" with the latest version number of ContentLib found here:
  <https://ficsit.app/mod/ContentLib>, so that it follows the format `^The.Number.Here`.
  Once you're done, that section will look similar to this:

```json
{
  "Name": "ContentLib",
  "Enabled": true,
  "SemVersion": "^1.4.0"
},
```

- Replace the "GameVersion" with the latest game version number so it follows the format `>=GameCLVersionReplaceMe`.
  You can find the latest game version number in the "Game Versions" column of the [SML mod page's Versions tab](https://ficsit.app/mod/SML). Once you're done, it will look similar to this:

```json
"GameVersion": ">=365306",
```
