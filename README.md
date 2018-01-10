# sprite_get_pixel

sprite_getpixel() gets the color of a sprite's pixel.

• Returns the data in an array, in RGBA order.

• Values are in the 0-255 range.

• Uses buffers, which are fast!

• Automatically handles buffer creation & usage, so it only has to go through the "sprite -> surface -> buffer" process ONCE for each image, resulting in reduced processing overhead.

Usage example:

var arr = sprite_getpixel(sBoi, 0, 2, 4); // (sprite, subimg, x, y)

var color = make_color_rgb(arr[0], arr[1], arr[2]);

var alpha = arr[3]/255;

Read the documentation present inside the Scripts for usage instructions.
