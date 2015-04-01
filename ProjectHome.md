wx-config is a helper tool used when compiling applications that makes use of the wxWidgets library.
It helps you insert the correct compiler options on the command line so an application can use
g++ -o test.exe test.cpp `wx-config --libs --cflags` for instance, rather than hard-coding
values on where to find wxWidgets and it's configurations (monolithic, debug, unicode, wxuniversal, etc).

Note that backticks is a property of the shell or the build system used.
Fortunately the Code::Blocks IDE supports backticks natively on windows.
For other Windows IDEs and build systems there are workarounds, commonly using **response files**.

Download latest release from here:
http://wx-config-win.googlecode.com/svn/binary/wx-config.exe

