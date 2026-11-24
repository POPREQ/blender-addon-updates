# blender-addon-updates

Latest version information for POPREQ's Blender add-ons.
The add-ons read these files when the user presses "Check for Updates" in the add-on preferences.
Nothing else is stored here, and no information is sent by the add-ons beyond a plain HTTP GET.

| File | Add-on |
|---|---|
| `close_bone_picker.json` | Close Bone Picker |

## Format

```json
{
  "schema": 1,
  "version": "1.8.0",
  "notes": ["One line per change, shown in the preferences"]
}
```

- `version` — the latest released version (`MAJOR.MINOR.PATCH`)
- `notes` — short English lines shown under the update notice (keep each line short; Blender does not wrap labels)
- Download links are intentionally not included. The add-on opens a fixed download page (a list of stores) that is written in the add-on itself.
