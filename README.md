All parts of this project are protected under the [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).
# UnGPU
The UnGPU is a TTL-based monochrome GPU. It is called the "UnGPU" because it can only display text. You cannot change individual pixels with it.

The UnGPU outputs an 800x600 60Hz VGA signal, but the true resolution is only 200x150 pixels. It uses an 8x8 font to display 25x18 characters. The VGA timing circuitry was borrowed from Ben Eater's World's Worst Video Card. Schematics for the horizontal and vertical timing circuits are available on [his website](https://eater.net/vga). The rest of it is in the schematic below:

![UnGPU main schematic](SCH_UnGPU Text Generator_1-P1_2026-11-17.svg)

