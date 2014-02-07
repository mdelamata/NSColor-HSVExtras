NSColor-HSVExtras
=================

Objective-C Category for NSColor allowing to use and convert to HSV space.

Inspired by https://github.com/mateagar/Color-Picker-for-iOS



Examples of use
------------

Firstly, import the `NSColor+HSVExtras.h` at the header of your file.

  	#import "NSColor+HSVExtras.h"

For example, if you would need to change a parameter of a color using the HSV space color it should be like this:

    NSColor *color = [NSColor red];
    color = [NSColor colorWithHue:color.hue saturation:color.saturation brightness:color.brightness-0.2 alpha:color.alpha];
    

You can get the following parameters from NSColor:

    -(CGFloat)hue;
    -(CGFloat)saturation;
    -(CGFloat)brightness;
    -(CGFloat)value;
    -(CGFloat)red;
    -(CGFloat)green;
    -(CGFloat)blue;
    -(CGFloat)white;
    -(CGFloat)alpha;
    
    
##License

Free use. Don't hesitate adding things, please.
