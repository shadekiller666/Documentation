Locations
=========

Minecraft expects certain parts of your project to be in certain locations, such as textures and JSONs.

All locations and items covered in this page are relative to your `./src/main/resources/` folder.

### mcmod.info

The `mcmod.info` file is in the root directory.

### Blockstates

Blockstate definition files are in the JSON format and are in the `./blockstates/` folder.

### Localizations

Localizations are plain-text files with the file extension .lang and the name being their [language code](https://msdn.microsoft.com/en-us/library/ee825488(v=cs.20).aspx) such as `en_US`.

They are located in the `./lang/` folder.

### Models

Model files are in JSON format and are located in `./models/block/` or `./models/item/` depending on whether they are for a block or an item, respectively.

### Textures

Textures are in the PNG format and are located in `./textures/blocks/` or `./textures/items/` depending on whether they are for a block or an item, respectively.
