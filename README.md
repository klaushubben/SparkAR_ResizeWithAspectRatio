# Resize With Aspect Ratio for Facebook's Spark AR
A patch for Spark AR which resizes your rectangle to fill the window while maintaining it's native aspect ratio.

Simply connect the inputs with the Device node's 'Screen Size' and 'Screen Scale' and connect to a 2D Rectangles 'Size' node.

## Inputs
• Screen Size : Vec2 from Device/Screen Size
• Screen Scale : Number from Device/Screen Scale
• Image Width/Height : Vec2 which (in most cases) you can manually enter your texture's native width and Height

## Output
• a Vec2 which should be connected to the 'Size' node of a Rectangle (or anything else that makes sense!)
