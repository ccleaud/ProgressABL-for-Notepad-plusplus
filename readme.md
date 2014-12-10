Progress | OpenEdge for Notepad++
=================================

Syntax highlighting and functions listing for Progress | OpenEdge files in Notepad++.


Description
-----------
There are 2 [Notepad++](http://notepad-plus-plus.org/) add-on features in this repository:

1.
An XML file that gives you syntax highlighting/coloring for .p .w .i and .cls files and brings you ability to fold code structure.
A recent version of [Notepad++](http://notepad-plus-plus.org/) is required (one of those supporting the [User Defined Language](http://udl20.weebly.com/ "User Defined Language")).

2.
An XML delta-file to make Notepad++ able to detect Progress | OpenEdge functions, procedures, external procedures, event triggers and even AppBuilder sections.


Syntax highlighter features
---------------------------
- keywords (many OpenEdge keywords are recognized and classified in 2 colors: statements and methods/properties)
- comments
- nested comments (yes, Progress can do this)
- strings
- numbers
- preprocessor directives
- outlining of blocks like DO, PROCEDURE, FUNCTION


Functions list features
-----------------------
- detection of internal procedures
- detection of external procedures (such as functions in .so or .dll)
- detection of functions and function forwards
- detection of triggers
- detection of definition sections
- detection of main block section
- detection of procedure settings section



How to use the syntax highlighter
---------------------------------
 - download the `progress_openedge.xml` file
 - open Notepad++
 - go to  `Language -> Define your language...`,  click on  `Import...` and select the `progress_openedge.xml` file you've downloaded
 - close and restart Notepad++
 - finished


How to use the function-list configuration
------------------------------------------
 - download the `functionlist-delta.xml` file
 - close all instances of Notepad++
 - go to settings directory of Notepad++ (can be either %APPDATA% or installation directory, according to the presence of `doLocalConf.xml`)
 - open `functionlist.xml` and manually merge `functionlist-delta.xml` in it (sorry, I don't know any other way to do this) - don't use Notepad++ to do this or you might lose your changes
 - delete `functionlist-delta.xml` as it is no longer necessary
 - finished


Notes
-----
 - the color scheme is built for the default theme (white background)
 - some keywords are missing and are planed to be added on the fly


Previews
--------

Syntax highlighter:

![](preview-syntax.png)


Functions List:

![](preview-functions.png)


And now ....
------------
Enjoy!
