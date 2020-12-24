#Flexbox

What is flexbox?
CSS Flexible Box Module is a one dimensional layout model which makes it easy to build flexible and efficient layouts, distribute space among items, control their alignment.

Before Flexbox, the following layout modes were present:
Layout Modes
1. Block, for sections in a webpage
2. Inline, for text
3. Table, for two dimensional table data
4. Positioned, for explicit position of an element


Why Flexbox?
1. A lot of flexibility
2. Arrange items
3. Spacing
4. Alignment
5. Order of items
6. Bootstrap 4 is built on top of the flex layout

Terminology
Flex Container - Parent element
Flex Items - Children elements

Flexbox Axes
Main Axis - Left to right - Main start is the starting point and Main end is the ending point and length from main start to main end is called the main size
Cross Axis - Top to bottom - Cross start is the starting point and Cross end is the ending point and length from cross start to cross end is called the cross size


Flex Container Properties
1. display - block level or inline level flex container - flex or inline-flex
2. flex-direction - sets the direction of the main axis - row, row-reverse, column, column-reverse
3. flex-wrap - Control the wrapping of flex items within the container - nowrap, wrap, wrap-reverse
4. flex-flow - Shorthand for flex direction and flex wrap - <flex-direction><flex-wrap>
5. justify-content - Align items and distribute any extra spacing in the parent container. The alignment is always along the main axis - flex-start, flex-end, center, space-between, space-around, space-evenly
6. align-items - Align items along the cross axis - flex-start, flex-end, center, baseline, stretch
7. align-content - Aligns lines of content along the cross axis and distribute any extra spacing in the parent container - flex-start, flex-end, center, space-between, space-around, stretch
