Stanford CS 144 Networking Lab
==============================

open-source git commit for CS144 networking class submitted by juli huang. includes my changes for what to improve for a cs144 assignment. Listed in this branch:
https://github.com/TheClassicTechno/minnow2/commit/756541aacfb8b3c56c0efc9703a6f837631289b0

These labs are open to the public under the (friendly) request that to
preserve their value as a teaching tool, solutions not be posted
publicly by anybody.

Website: https://cs144.stanford.edu

To set up the build system: `cmake -S . -B build`

To compile: `cmake --build build`

To run tests: `cmake --build build --target test`

To run speed benchmarks: `cmake --build build --target speed`

To run clang-tidy (which suggests improvements): `cmake --build build --target tidy`

To format code: `cmake --build build --target format`
