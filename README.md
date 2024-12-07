# My musings on creating a FUSE file system in Nim.

The purpose is to document the process of creating a minimal FUSE file
system with as few distractions as possible and then continue with
documenting the extension of this minimal system to do something
useful (or perhaps merely interesting).

So here is a short list of things I intend to do and not do.  These
lists may be expanded later.

To do:
  * Find out how to integrate the FUSE library, libfuse, into a Nim
    program
  * Create the simplest possible FUSE file system

To not do:
  * Make this cross platform
  * Automate the discovery of compiler flags that should be used.
  * Performance optimizations beyond those necessary to make it usable
