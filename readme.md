Motive Version 1.0.0    {#motive_readme}
====================

# Overview

Motive is an open-source, cross-platform, memory efficient, and performant animation system.

# Features

The v1.0 release of Motive is feature light. It's focused primarily on
procedural animation and simple hand-tunable motion. It is suitable for
the animation of props, cameras, GUI elements, and simple rigs.

# Dependencies

Motive depends upon:

* [MathFu][] -- used internally; you can substitute your own vector types
  in the external API.
* [FplUtil][] -- C++ allocator libraries.

Motive has optional features that depend upon:

* [FlatBuffers][] -- allow animation data to be defined in json and then
  compiled to a small binary format.

The Motive performance benchmark application also uses:

* [SDL][] -- for crossplatform graphics rendering

# Notes

For applications on Google Play that integrate this tool, usage is tracked.
This tracking is done automatically using the embedded version string in
`kVersion`. Aside from consuming a few extra bytes in your application binary,
it shouldn't affect your application at all.  We use this information to let us
know if Motive is useful and if we should continue to invest in it. Since this
is open source, you are free to remove the version string, but we would
appreciate if you would leave it in.

  [MathFu]: http://google.github.io/mathfu/
  [FplUtil]: http://google.github.io/fplutil/
  [FlatBuffers]: http://google.github.io/flatbuffers/
  [SDL]: https://www.libsdl.org/