What is it
==========
Here is the unofficial precompiled Windows executable binary for aha - Ansi HTML Adapter

Converts ANSI escape sequences of a unix terminal to HTML code.

Original source code homepage:  
https://github.com/theZiz/aha


How to use
==========
Go to Releases page,
click ```aha-*-windows-*.zip``` download link,
unzip,
open a command prompt,
enjoy
```bat
cd /d DOWNLOADED_FOLDER
aha --help
```
with no other DLL required.

How to compile
==============
1. Install MSYS2 from https://www.msys2.org/
2. Download source code from https://github.com/theZiz/aha
3. Start -> MSYS2 MinGW x64
```bat
cd SOURCE_CODE_FOLDER
make
```
4. See the result file aha.exe

In fact, the executable only depends on KERNEL32.dll and msvcrt.dll,
which are alreadey shipped with Windows.
