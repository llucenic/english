# Install D locally

On the D language's website [dlang.org](https://dlang.org) the most recent
compiler version of the reference compiler **DMD** (Digital Mars D)
can be [downloaded](http://dlang.org/download.html) and installed:

### Windows

* [Installer](http://downloads.dlang.org/releases/2.x/{{latest-release}}/dmd-{{latest-release}}.exe)
* or: [Archive](http://downloads.dlang.org/releases/2.x/{{latest-release}}/dmd.{{latest-release}}.windows.7z)
* using [chocolatey](https://chocolatey.org/packages/dmd): `choco install dmd`

### macOS

* `.dmg` [package](http://downloads.dlang.org/releases/2.x/{{latest-release}}/dmd.{{latest-release}}.dmg)
* or: [Archive](http://downloads.dlang.org/releases/2.x/{{latest-release}}/dmd.{{latest-release}}.osx.tar.xz)
* using [Homebrew](http://brew.sh): `brew install dmd`

### Linux / FreeBSD / macOS

To quickly install dmd within your user directory, run: `curl -fsS https://dlang.org/install.sh | bash -s dmd`

Packages for various distributions are provided:

* [ArchLinux](https://wiki.archlinux.org/index.php/D_(programming_language))
* [Debian/Ubuntu](http://d-apt.sourceforge.net).
* [Fedora/CentOS](http://dlang.org/download.html#dmd)
* [Gentoo](https://wiki.gentoo.org/wiki/Dlang)
* [OpenSuse](http://dlang.org/download.html#dmd)

## Other compilers

Besides the DMD reference compiler which uses its own backend, there are
two other compilers that can be fetched through the
[dlang.org](https://dlang.org) download section:

* [**GDC**](http://gdcproject.org/downloads) which uses the GCC backend
* [**LDC**](https://github.com/ldc-developers/ldc#installation) based on the LLVM backend

GDC and LDC aren't always at the most recent DMD frontend's versions,
but provide better optimization levels as well as support
for other platforms like e.g. ARM.

See the wiki for [more information](https://wiki.dlang.org/Compilers)

## Configure your editor

The beauty about D is that you don't need a fancy IDE as boilerplate code is very rare.
However, using D is nicer when you are in the comfortable zone of your favorite editor.
There are D plugins for at least the following editors:

- [Atom](https://github.com/Pure-D/atomize-d)
- [Eclipse](http://ddt-ide.github.io)
- [Emacs](https://github.com/Emacs-D-Mode-Maintainers/Emacs-D-Mode)
- [IntelliJ](https://github.com/intellij-dlanguage/intellij-dlanguage)
- [Sublime Text](https://github.com/yazd/DKit)
- [Vim](https://wiki.dlang.org/D_in_Vim)
- [VS Code](https://marketplace.visualstudio.com/items/webfreak.code-d)
- [Visual Studio](http://rainers.github.io/visuald/visuald/StartPage.html)

You may also want to try an IDE dedicated to D:

- [Coedit](https://github.com/BBasile/Coedit)
- [Dlang IDE](https://github.com/buggins/dlangide)

The D wiki contains a more detailed overview of available [editors](https://wiki.dlang.org/Editors) and [IDEs](https://wiki.dlang.org/IDEs).
