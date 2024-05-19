# C adoption of C++ `ok_color.h` reference implementation

Originally made by Björn Ottosson

Blog post: https://bottosson.github.io/posts/colorpicker/

Source: http://bottosson.github.io/misc/ok_color.h

## usage:
```c
#define OK_COLOR_IMPLEMENTATION
#include "ok_color.h"
```

## notable changes:
- Introduced `Linear_RGB` Struct to make the type more explicit
- removed redundant calls to `find_cusp`
