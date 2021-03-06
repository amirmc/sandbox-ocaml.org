# OCaml 4.00.1
**License**<br />
 The OCaml system is open source software: the compiler is distributed
under the terms of the Q Public License, and its library is under LGPL;
please read the [license](../license.html) document for more details. A
BSD-style license is also available for a fee through the [OCaml
Consortium](../support.html#consortium).

The most recent released version of OCaml is OCaml 4.00.1, released on
2012-10-05.

Development versions, and [earlier
releases](http://caml.inria.fr/pub/distrib/) are also available; the
most recent stable release of the the previous major version of OCaml
was [3.12.1](3.12.1.html), released in 2011.

## What's New
Release 4.00.1 is mostly a bugfix release.

Some of the highlights in release 4.0.0 (July 2012) are:

* The name the language is now officially "OCaml", and this name is
 used consistently in all the documentation and tool outputs.
* Generalized Algebraic Data Types (GADTs): this is a powerful
 extension of the type system that provides great flexibility and
 power to the programmer.
* A new and improved ARM back-end.
* Changes to first-class modules: type annotations can now be omitted
 when packing and unpacking modules (and are inferred from context
 whenever possible), and first-class modules can now be unpacked by
 pattern-matching.
* Support for randomized hash tables to avoid denial-of-service
 vulnerabilities.
* Installation of the compiler's internal libraries in
 `+compiler-libs` for easier access by third-party programming tools.

For more information, please consult the [comprehensive list of
changes](http://caml.inria.fr/pub/distrib/ocaml-4.00/notes/Changes).

## ![](../img/source.gif "")Source distribution
* [Source
 tarball](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00.1.tar.gz)
 (.tar.gz) for compilation under Unix (including Linux and MacOS X)
 and Microsoft Windows (including Cygwin).
* Also available in
 [.tar.bz2](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00.1.tar.bz2)
 format.
* You also have read-only [SVN access](svn.html) to the working
 sources and to all previous public releases.

The [INSTALL](http://caml.inria.fr/pub/distrib/ocaml-4.00/notes/INSTALL)
file of the distribution provides detailed compilation and installation
instruction.

## ![](../img/linux.gif "")Precompiled binaries for Linux
* [Debian packages](http://packages.debian.org/ocaml).
* [Fedora
 packages](https://admin.fedoraproject.org/pkgdb/acls/name/ocaml/).
* [Gentoo
 packages](http://packages.gentoo.org/packages/?category=dev-lang;name=ocaml).

## ![](../img/macos.gif "")Precompiled binaries for MacOS X
Binary package compiled on Mac OS 10.7.5 with XCode tools 4.4 (probably
not compatible with earlier versions of Mac OS X):

* [for
 Intel](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00.1-intel.dmg)
 (4.00.1)

## ![](../img/windows.gif "")Precompiled binaries for Microsoft Windows
Four ports of OCaml for Microsoft Windows are currently available. For
additional information, please consult the list of [portability
issues](http://caml.inria.fr/ocaml/portability.en.html) or the [Windows
release
notes](http://caml.inria.fr/pub/distrib/ocaml-4.00/notes/README.win32).

* [Cygwin-based native Win32 port
 (4.00.0)](http://protz.github.com/ocaml-installer/). A self
 installer. The interactive loop comes with a simple graphical user
 interface. Some features require the Cygwin environment, which the
 installer can fetch for you. However, the compilers are, and
 generate true Win32 executables, which do not require Cygwin to run.
* Microsoft-based native Win32 port. No binary distribution available
 yet; download the source distribution and compile it.
* [Cygwin](http://cygwin.com/)-based port. Requires Cygwin. No
 graphical user interface is provided. The compilers generate
 executables that do require Cygwin. The precompiled binaries are
 part of the Cygwin distribution; you can install them using the
 Cygwin `setup` tool. Alternatively, download the source distribution
 and compile it under Cygwin.
* Microsoft-based native Win64 port Same features as the
 Microsoft-based native Win32 port, but generates 64-bit code. No
 binary distribution available yet; download the source distribution
 and compile it.

## Precompiled binaries for Solaris
Available at [sunfreeware.com](http://sunfreeware.com/).

## Alternative Compilers
Additionally, the following projects allow you to compile OCaml code to
targets traditionally associated with other languages:

* The [js_of_ocaml project](http://ocsigen.org/js_of_ocaml/), an
 OCaml to Javascript compiler (stable)
* The [ocamljava project](http://cafesterol.x9c.fr/), an OCaml to Java
 compiler (experimental)

## ![](../img/doc.gif "")User's manual
The user's manual for OCaml can be:

* [browsed
 online](http://caml.inria.fr/pub/docs/manual-ocaml-4.00/index.html),
* downloaded as a single
 [PostScript](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman.ps.gz),
 [PDF](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman.pdf),
 or [plain
 text](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman.txt)
 document,
* downloaded as a single
 [TAR](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman-html.tar.gz)
 or
 [ZIP](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman-html.zip)
 archive of HTML files,
* downloaded as a single
 [tarball](http://caml.inria.fr/pub/distrib/ocaml-4.00/ocaml-4.00-refman.info.tar.gz)
 of Emacs `info` files.

