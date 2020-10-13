# antlr4-c3 The ANTLR4 Code Completion Core

This is a port of the antlr4-c3 library to Java that is again ported to with minimal changes to GWT.

Original source from: https://github.com/mike-lischke/antlr4-c3

Please see the parent readme.md for an explanation of the library and for examples. 

The only changes with respect to the original typescript implementation are:

- use of Java logging framework for debug messages
- CandidatesCollection has a new field which returns information about encountered preferred rules

Changes to GWTize are:
- Added gwt.xml file
- Also the sources have been compiled

### Making releases

We use the nexus-staging maven plugin.

You will need authorization from nexus to release artifacts.

The nexus-staging maven plugin instructions are here:

http://central.sonatype.org/pages/apache-maven.html

