This project is forked from 2.5.0 SQLite, and fixed for modern C compilers like GCC.

Earlier SQLite is perfect source for code reading, and for database design and implementation.
For SQLite 2.5.0, it has a core code base less than 20000 LOC in ANSI C which is easy to understand.

I digged into historical versions of SQLite, and fixed this version against GCC on MacOS 10.13 and Debian 8.

$sloccount SQLite-2.5.0-for-code-reading
SLOC	Directory	SLOC-by-Language (Sorted)
20914   src_top_dir     ansic=19895,yacc=584,tcl=435
6831    top_dir         sh=6831
6363    www             tcl=6363
4051    tool            ansic=3606,tcl=372,awk=73
156     test            tcl=156
0       doc             (none)


    SQLite: An SQL Database Engine in a C Library

To compile the project, first create a directory in which to place
the build products.  It is recommended, but not required, that the
build directory be separate from the source directory.  Cd into the
build directory and then from the build directory run the configure
script found at the root of the source tree.  Then run "make".

For example:

    tar xzf sqlite.tar.gz    ;#  Unpack the source tree into "sqlite"
    mkdir bld                ;#  Build will occur in a sibling directory
    cd bld                   ;#  Change to the build directory
    ../sqlite/configure      ;#  Run the configure script
    make                     ;#  Run the makefile.

The configure script uses autoconf 2.50 and libtool.  If the configure
script does not work out for you, there is a generic makefile named
"Makefile.template" in the top directory of the source tree that you
can copy and edit to suite your needs.  Comments on the generic makefile
show what changes are needed.

The windows binaries on the website are created using MinGW32 configured
as a cross-compiler running under Linux.  For details, see the ./publish.sh
script at the top-level of the source tree.

Contacts:

   http://www.hwaci.com/sw/sqlite/
   http://groups.yahoo.com/group/sqlite/
   drh@hwaci.com
