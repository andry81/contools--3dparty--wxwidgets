* README_EN.txt
* 2020.02.10
* contools--3dparty--wxwidgets

1. DESCRIPTION
2. LICENSE
3. REPOSITORIES
4. INSTALLATION
5. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
wxwidgets patched sources fork from:
https://www.wxwidgets.org/downloads/

From authors:

  wxWidgets was started in 1992 by Julian Smart at the University of Edinburgh.
  Initially started as a project for creating applications that were portable
  across Unix and Windows, it has grown to support macOS, GTK+, and many other
  toolkits and platforms (see the history page for more details). The number of
  developers contributing to the project is now in the hundreds and the toolkit
  has a strong userbase that includes everyone from open source developers to
  corporations. So what is special about wxWidgets compared with other
  cross-platform GUI toolkits?

  wxWidgets gives you a single, easy-to-use API for writing GUI applications on
  multiple platforms that still utilize the native platform’s controls and
  utilities. Link with the appropriate library for your platform and compiler,
  and your application will adopt the look and feel appropriate to that
  platform. On top of great GUI functionality, wxWidgets gives you: online
  help, network programming, streams, clipboard and drag and drop,
  multithreading, image loading and saving in a variety of popular formats,
  HTML viewing and printing, and much more.

  Although wxWidgets is written in C++, you can use it with a variety of
  languages including Python, Perl, and C#. If using wxWidgets with C++, you
  will link your code to a different version of the library on each platform.
  Since the wxWidgets libraries are built and compiled in C++ rather than a
  language like Java, they are high-performance and nearly as fast as using
  the native toolkits themselves.

  Supported Platforms
  wxWidgets currently supports the following platforms:

  * wxGTK: The recommended port for Linux and other Unix variants, using GTK+
    version 2.6 or higher.
  * wxMSW: The port for 32-bit and 64-bit Windows variants including Windows
    XP, Vista, 7, 8 and 10.
  * wxOSX/Cocoa: For delivering 32-bit and 64-bit Cocoa-based applications on
    macOS 10.7 and above.
  * wxQt: wxQt is a port of wxWidgets using Qt libraries. It requires Qt 5 or
    later.
  * wxX11: A port for Linux and Unix variants targetting X11 displays using a
    generic widget set.
  * wxMotif: A port for Linux and Unix variants using OpenMotif or Lesstif
    widget sets.

  Additionally the following legacy platforms are supported by the current
  stable 3.0 release:

  * wxMSW: Legacy 32-bit Windows versions like Windows 95, Windows 98, Windows
    2000
  * wxMac: For delivering Carbon applications on Mac OS X 10.2 through 10.6.
  * wxOSX/Carbon: For delivering 32-bit Carbon-based applications on Mac OS X
    10.5 and above.

The original library patched to fix these issues:

1. Build under Visual Studio 2015 Update 3.

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
wxWidgets licence is a modified version of LGPL explicitly allowing not
distributing the sources of an application using the library even in the case
of static linking.

(see included text file "README.md" or
https://github.com/wxWidgets/wxWidgets/blob/master/docs/licence.txt )

-------------------------------------------------------------------------------
3. REPOSITORIES
-------------------------------------------------------------------------------
Primary:
  * https://sf.net/p/contools/3dparty--wxwidgets/HEAD/tree/trunk
    https://svn.code.sf.net/p/contools/3dparty--wxwidgets/trunk
First mirror:
  * https://github.com/andry81/contools--3dparty--wxwidgets/tree/trunk
    https://github.com/andry81/contools--3dparty--wxwidgets.git
Second mirror:
  * https://bitbucket.org/andry81/contools-3dparty-wxwidgets/src/trunk
    https://bitbucket.org/andry81/contools-3dparty-wxwidgets.git

-------------------------------------------------------------------------------
4. INSTALLATION
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
