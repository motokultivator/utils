# UTILS

This is a set of *helper functions* and algorithms written in C, which have *libc* as their only dependency. They can be used on various platforms/OS and linked with other programming languages (C++, rust, java, go, python, ...).

This is a subset of a closed-source, proprietary software, project called *ViP-common* that I worked on in the early 2000s. Here I publish parts of which I am the sole author and to which I claim the rights. You may use this content under the terms of the LICENSE file.

In its original form, this has been widely used/tested on the following platforms: *x86 Linux*, *x86_64 Linux*, *ARM Linux*, *ARM64 Linux*, *MIPS32R2 Linux*, *MIPS64R2 Linux*, *x86_64 Windows*, *x86_64 MAC OSX*, *ARM Android*, *ARM IOS* and some microcontrollers, but always on Little-endian hardware. As far as I know, these functions have never been tested on Big-endian machines.

Since I'm refactoring now (taking code from one project and putting it into another project), there's an opportunity to make minor mistakes. I am only able to test on Linux. If that happens, the fixes are probably trivial, and please send a PR.
