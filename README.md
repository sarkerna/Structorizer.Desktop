# Structorizer

Structorizer is a little tool to create Nassi-Shneiderman Diagrams (NSD).

Beyond mere editing, it even allows to execute and debug them (within certain restrictions), to control a painting turtle on a drawing canvas, and to export the formed algorithms to several programming languages (still requiring postprocessing, of course).

The debugging features include stepwise execution, highlighting, pausing, breakpoints, variable display (with value editing), and configurable running speed, and eventually the possibility to call other diagrams as subroutine.
The newest feature is a "Run Data Tracker" collecting and visualising execution counts and test coverage.

The website can be found at http://structorizer.fisch.lu


# Why having started this project?

In fact, I was not satisfied by the result of other NSD-editors, so I started writing my own one. I think I started drawing the first schemes and thinking about it\'s internal structure in july 2006. The first lines of code were written during the summer and for september a first more of less functional version was available.


# Project history

I will not draw the entire changelog here, but just a few lines that, I think so, could be of interest:

* The first version, called "Structorizer 2006", was written in "Delphi 6 PE".
* In january 2007 I decided to rename the project to "Structorizer", as "2006" did no longer apply and a lot of new features waited to be integrated.
* Somewhat later in 2007 I ported the project for e first time to "Lazarus". I published a Linux version as well as the source code under the terms of the PGL license and called this sub-project "openStructorizer".
* I got my first Mac in may 2007 and wanted to have the application run in native mode. I did a second and this time complete port of the project to "Lazarus". Waiting for the next release to be published, I renamed the old project to "Structorizer (Delphi)" and stopped both of them.
* I will publish Windows, Linux and Mac OSX (intel) ports of the new "Structorizer (Lazarus)" project. This will be completely open-source this time!
* After the release of the Lazarus version, major problems were detected for the Windows port. This is why I came back to the Delphi code and continued developping "Structorizer (Delphi)", which will be published as freeware.
* Due to to many problems with Lazarus, I decided to implement a Structorizer version in JAVA in december 2007. This version, which has also been released under the terms of the GPL, became version number 3.x.
