[JSCover](http://tntim96.github.com/JSCover) - A JavaScript code coverage measurement tool.
================================

JSCover is an easy-to-use JavaScript code coverage measuring tool. It is based on the popular
[JSCoverage](http://tntim96.github.com/JSCover)
tool which is no
longer maintained. It's big distinguishing factor from other JavaScript tools is that it runs in browser allowing
coverage measurement of tests that include DOM interaction. It can be run with most tools (e.g. Jasmine, QUnit, etc...)
and is browser independent.

Development
-----------

Before checking-out, make sure your git client has "Auto CrLf convert" turned off.
If not, this will cause some tests to fail on Windows machine (the tests may be altered to over-come this if it
proves to be a common problem).

Development with JSCover is simple. It is a fairly standard Ant and Java build.
Most development has been done with IntelliJ community edition, and some with Eclipse.
Project files for both IDEs are checked in, but any editor can be used.
Before checking in any changes, be sure to run the build files `pre-commit`.
Some care needs to be taken as coverage is currently only just above 80%  - this needs to be improved.


