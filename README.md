# controllable-party-miitopia-3ds
This is an .IPS patch for Miitopia (3DS) that allows you to control your party members in battle.

## Compiling the patch
To compile the patch, you'll need:
- [armips](https://github.com/Kingcom/armips)
- [flips](https://github.com/Alcaro/Flips)
- Decompressed `code.bin` from your Miitopia dump placed in the `src` folder

Then you can just use `make REGION` to compile the patch

Replace `REGION` with one of the following values based on your game's region:
  - `us` for the North American version
  - `eu` for the European version
  - `jp` for the Japanese version
  - `jp_upd` for the Japanese version (v1.1)
