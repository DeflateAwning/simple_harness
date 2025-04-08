# simple_harness

Wiring harness editor and viewer in C. Based on [raylib](https://github.com/raysan5/raylib/).

<video controls>
  <source src="Demo.mp4" type="video/mp4">
  Your browser does not support the video tag. See <a href="Demo.mp4">demo.mp4</a> for download.
</video>

Edit simple_harness.c to point to a TTF font in your ``$HOME/bin`` directory and compile using your favourite C compiler.

Harness connectors and wiring are expressed in ASCII text files.

Uses ``strsep(...)`` from ``<string.h>``; you might have to implement this yourself on some OS's.

To compile on ``macos``, have a look at the source code for ``compile.c``. Hints for other OS's are available from the raylib wiki.

License: GPL v3
