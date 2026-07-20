# Liberty City Stories for open.mp

[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)


Liberty City Stories converted to **open.mp** by **spicybung**; unfortunately, as it currently stands, there is too many custom objects for SAMP 0.3DL.

## Configuration

Open your `config.json` file and locate the `"pawn"` section.

Add the filterscript to the `"side_scripts"` array.

> **Note:** Do **not** include the `.amx` extension.

### Example

```json
{
    "pawn": {
        "legacy_plugins": [
            "streamer",
            "sscanf"
        ],
        "main_scripts": [
            "your_gamemode 1"
        ],
        "side_scripts": [
            "filterscripts/LCS2OMP"
        ]
    }
}
```

After saving `config.json`, restart your open.mp server. The LCS2OMP filterscript will be loaded automatically on startup.

## Acknowledgements

+ The open.mp developer team(iAmir, Ksen, Hual, etc...), for their work in making a new SAMP and increasing its capabilities - creating the inspiration to do this
+ The SAMP community, which deserves long overdue upgrades
+ The GTA Modding community, for the initial inspiration way back as a kid
