# build-plugin-envar

Test fixture for [nsis-dev/build-plugin](https://github.com/nsis-dev/build-plugin).

**Covers:** The common case. One C file, all four targets, msvc release build plus a mingw check build.

**Changed from upstream:** Dropped the bundled `nsis/` Plugin API copy and prebuilt `.lib`s; `#include "nsis\pluginapi.h"` became `#include <nsis/pluginapi.h>`.
