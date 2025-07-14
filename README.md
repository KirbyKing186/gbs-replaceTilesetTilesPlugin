# gbs-replaceTilesetTilesPlugin
Load and replace tiles in the VRAM tileset using a tileset [Plus "Source Tile Offset Index" Preview]
## Disclaimer
The following fork provides a small Quality-of-Life update so that the "Source Tile Offset Index" can be previewed in the GB Studio.

Due to the way the preview function works, replacing the original plugin with this fork will result in every "Replace Tileset Tiles" event having its "Source Tile Offset Index" field to be reset to 0, requiring a manual change back in order to avoid compiler warnings. Using this plugin from a fresh installation (without older "Replace Tileset Tiles" events existing in the project) will not have this issue.

<img width="820" height="284" alt="Image showing three 'Replace Tileset Tiles' events. Each event has a different 'Source Tile Offset Index' value, and the small tile icon to the left of the tileset field reflects the Source Tile." src="https://github.com/user-attachments/assets/e2cb069b-e3e8-4b39-a987-466d049bdd1f" />

## Usage
This plugin adds the event to use the GBVM command VM_REPLACE_TILE.

![image](https://github.com/user-attachments/assets/4400d11b-e663-4163-b840-da48ab1783ee)

![image](https://github.com/user-attachments/assets/c0ba1ef1-faac-4e95-9ae7-e18cf8e226b3)
