## Class 8 Notes

**CSS - Flexbox**

1. The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

  This is the ideal layout model for this sidebar pattern. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. 
  Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.
  
2. The key to understanding flexbox is to understand the concept of a main axis and a cross axis. The main axis is the one set by your flex-direction property.
If that is row your main axis is along the row, if it is column your main axis is along the column.

Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.
The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

3. You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this
The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

//--source: https://web.dev/learn/css/flexbox/

**CSS - Layout Flexbox**

1.  or a long time, the only reliable cross-browser compatible tools available for creating CSS layouts were features like floats and positioning. These work, but in some ways they're also limiting and frustrating.

The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

Vertically centering a block of content inside its parent.
Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
As you'll see in subsequent sections, flexbox makes a lot of layout tasks much easier.

//--source: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox#summary

2. This will allow me to have more tools at my disposal whenever I go into the field.  I can more confidently and expediently achive the results I want whenever designing websites etc.
