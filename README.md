UIColor+lightAndDark
====================

An API for UIColor to get a slightly lighter or darker color of an instance.

Code grabbed from: http://stackoverflow.com/a/11598127/3464699

Modified to ease the process of incorporating into projects (git submodule, etc.)

Usage
=====

```objc
#import "UIColor+lightAndDark.h"

UIColor* darkerGreen = [[UIColor greenColor] darkerColor];
UIColor* lightGreen = [[UIColor greenColor] lighterColor];
```
