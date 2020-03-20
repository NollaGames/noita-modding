TODO

- Stainable sprites should have a corresponding SPRITE_NAME_uv_src.png next to the sprite file, and the folder containing the sprite should be passed to ModDevGenerateSpriteUVsForDirectory() in init.lua.
- For example for 'player.png' the corresponding UV source file is called 'player_uv_src.png'
- ModDevGenerateSpriteUVsForDirectory( directory_path ) must be called in init.lua file scope. It doesn't do anything outside noita_dev.exe.