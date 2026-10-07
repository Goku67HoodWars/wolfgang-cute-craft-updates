# Wolfgang Cute Craft — custom mod updates

Auto-update manifest + jars for the private **Wolfgang Cute Craft** modpack's custom (non-CurseForge)
mods. The `wolfgangupdater` mod in the pack reads `manifest.json` on launch, downloads any newer jar
here, and swaps it in on the next restart. CurseForge still manages all the CurseForge mods.

To update a mod: bump its `version` in its jar, upload the new jar to the `mods` release (replacing the
asset), and bump the matching `version` + `sha256` in `manifest.json`.
