# odin-sdl_bitmap_font

This is just a suuuuper-simple bitmap font rendering library for SDL2.

DISCLAIMER: This was written in like three minutes. Use at your own peril.

## Usage
```
import fnt "shared:odin-sdl_bitmap_font"

...

font := fnt.load_bitmap_font(texture, character_width, character_height, characters);

...

fnt.draw_string(font, renderer, str, x, y);

...

fnt.get_string_width(font, str)
```
