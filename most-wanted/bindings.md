# Most Wanted Native Bindings

These are the native libraries that are most wanted as NativeCall bindings
rather than as Perl 6 source ports.  Often this is because the native library
offers performance or security guarantees that would be difficult or
impossible to provide in HLL code.  In other cases, it is because the library
provides such complex or finicky functionality that it could not be reproduced
in a correct new implementation without great effort -- effort that could be
better spent on [other most-wanted tasks](README-wanted.md).


## Archives and Compression

* zlib (WIP: [Compress::Zlib](https://github.com/retupmoca/P6-Compress-Zlib/))
* bzip2
* 7zip (7z.so/lib7zip)


## Databases

* DBD::
  + MySQL (TODO: proper placeholder / prepared statements)
  + Postgres (TODO: binary data, casting to appropriate types)
  + SQLite (done)


## Image processing

* Canvas and/or GD (WIP: [GD](https://github.com/mrhdias/perl6-GD/), [Cairo](https://github.com/timo/cairo-p6))
* Charting/Graphing
* ImageMagick or similar


## i18n and NLP

Internationalization and Natural Language Processing

* [ICU](http://site.icu-project.org/)
* [Snowball](http://snowball.tartarus.org/)


## Security

* openssl (WIP: [SSL](https://github.com/grondilu/openssl/), [OpenSSL](https://github.com/sergot/openssl/))
* ssh


## User interfaces

* Terminal
  + curses (WIP: [NCurses](https://github.com/azawawi/perl6-ncurses/))
  + readline
* GUI
  + Qt
  + Gtk (WIP: [GTK::Simple](https://github.com/perl6/gtk-simple/))
* 2D Graphics
  + SDL (WIP: [SDL](https://github.com/PerlGameDev/SDL6/), [SDL2](https:/github.com/timo/SDL2_raw-p6))
* 3D Graphics
  + OpenGL

## Other

* XML
  + Libxml2 (WIP: [XML::LibXML](https://github.com/FROGGS/p6-XML-LibXML))
  + Libxslt
* GeoIP (WIP: [GeoIP](https://github.com/bbkr/GeoIPerl6))
* [libgit2](https://libgit2.github.com/)
