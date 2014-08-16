# EffG

Efficient Ganglia modules to collect metrics appropriately, with lower
overhead, and better tested than the Python module equivalents I want
to use.

What is the point of using a high level language when you aren't reaping
any benefits of it? (e.g. like using better testing frameworks, having higher
code quality, etc.)

## Overview

This is partly a re-education for myself in C and I might also write some
Haskell/C FFI modules to see how well that works with Ganglia and write about
it.

*WARNING: These are all tested on "modern" Linux. If you would like to submit
patches back to make these modules more cross platform (POSIX), feel free, but
the primary purpose of these are to support "modern" Linux servers (kernel
2.6+).*

## Background

In our experience we have found a lot (if not all) of the already contributed
and open source Python ganglia modules to be both unstable and to be of low
quality in terms of code readability, robustness, and efficiency.

## License

This is open sourced under the BSD 3-clause license. Please see LICENSE file
for more details.

