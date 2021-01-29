<img src="https://i.imgur.com/5fdSk4G.png" width="35%">

A high-quality graphics library for embedded devices that doesn't exist yet.

You can find the development update posts below, in chronological order. Stay tuned for updates!

# Target platform

Long time, no updates. I'm happy to announce that microGL will support the RP2040 chip out of the box, along with ESP32. Future updates on the graphics engine will most likely showcase it running on the Raspberry Pi Pico. RP2040 is the perfect candidate for such a graphics engine, as it has dedicated hardware that accelerates linear transformations.

# Hello, world!

After a long period of ~procrastination~ refactoring, the codebase is now neatly structured, and we've got proper rendering of sprites, and affine transformations. Video at the link below.
https://www.reddit.com/r/arduino/comments/ffol0v/wip_graphics_library_for_esp32_arduino_core_with/

# Eye candy

Nearest-neighbour may be fast, but it sure isn't pleasant to look at. Latest update gives you the option to use bilinear filtering where smoothness is needed. Video and discussion at the link below.

**Update:** Filtering has been optimized, and now yields 40% better performance compared to the initial implementation.
https://www.reddit.com/r/esp32/comments/fi7tsl/wip_extremely_smooth_realtime_image
