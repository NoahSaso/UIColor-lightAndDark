UIColor+lightAndDark
====================

An API for UIColor to get a slightly lighter or darker color of a pre-existing one

Code grabbed from: http://stackoverflow.com/a/11598127/3464699

Re-made by Sassoty to make it easier to incorporate in your projects (git submodule, etc.)

Usage
=====

```objc
#import "UIColor+lightAndDark.h"

UIColor* darkerGreen = [[UIColor greenColor] darkerColor];
UIColor* lightGreen = [[UIColor greenColor] lighterColor];
```
