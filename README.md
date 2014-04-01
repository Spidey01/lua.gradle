
This is a container project for building Lua with Gradle. Both as a evaluation of Gradle, possible utility for projects needing to do this, etc.

At the top level it is possible to run the 'populate' task to download and explode Lua into ./lua. From there it is possible to build the project as if Lua was a Gradle project rather than a Make project.


NOTE: While this repo's build scripts are covered by the COPYING file here, the Lua code is covered under it's own license, etc. Insert common sense disclaimers here!


If you have issues building for an alternate platform, e.g. both linux\_i386 and linux\_amd64 targets. You probably need the gcc-multiarch package for your compiler/distribution. Either Google how to setup compiling 32-bit AND 64-bit binaries on your host, use explicit build targets, or comment out the relevant platform block in lua/build.gradle.
