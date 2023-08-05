my prject file:----------------->
https://manuhegde198924.github.io/background1/

Relative Position: Setting the top, right, bottom, and left properties of an element with position: relative;
property will cause it to adjust from its normal position. The other objects or elements will not fill the gap.

Syntax:

position: relative;

Absolute Position: An element with position: absolute; will cause it to adjust its position with respect to its parent.
If no parent is present, then it uses the document body as parent.

position: absolute;

Fixed Position: Position: fixed; property applied to an element will cause it to always stay in the same place even if the page is scrolled.
To position the element we use top, right, bottom, left properties.

CSS Margins: CSS margins are used to create space around the element. We can set the different sizes of margins for individual sides(top, right, bottom, left).

Margin properties can have the following values:

    Length in cm, px, pt, etc.
    Width % of the element.
    Margin calculated by the browser: auto.

Syntax: 

body {
    margin: value;
}

The margin property is a shorthand property having the following individual margin properties:

    margin-top: It is used to set the top margin of an element.
    margin-right: It is used to set the right margin of an element.
    margin-bottom: It is used to specify the amount of margin to be used on the bottom of an element.
    margin-left: It is used to set the width of the margin on the left of the desired element.

Note: The margin property allows negative values.

We will discuss all 4 properties sequentially.

If the margin property has 4 values: 

margin: 40px 100px 120px 80px;

    top = 40px
    right = 100px
    bottom = 120px
    left = 80px
CSS Color property is used to set the color of HTML elements. This property is used to set font color, background color, etc. The color of an element can be defined in the following ways:

    Built-In Color
    RGB Format
    RGBA Format
    Hexadecimal Notation
    HSL
    HSLA
        Fixed position: Any HTML element with position: fixed property will be positioned relative to the viewport. An element with fixed positioning allows it to remain in the same position even we scroll the page. We can set the position of the element using the top, right, bottom, and left.
    Static: This method of positioning is set by default. If we don’t mention the method of positioning for any element, the element has the position: static method by default. By defining Static, the top, right, bottom, and left will not have any control over the element. The element will be positioned with the normal flow of the page.
    Relative: An element with position: relative is positioned relatively with the other elements which are sitting on top of it. If we set its top, right, bottom, or left, other elements will not fill up the gap left by this element. An element with its position set to relative and when adjusted using top, bottom, left, and right will be positioned relative to its original position.
    Absolute: An element with position: absolute will be positioned with respect to its nearest Non-static ancestor. The positioning of this element does not depend upon its siblings or the elements which are at the same level.
    Sticky: Element with position: sticky and top:0 played a role between fixed & relative based on the position where it is placed. If the element is placed in the middle of the document then when the user scrolls the document, the sticky element start scrolling until it touched the top. When it touches the top, it will be fixed at the top place in spite of further scrolling. 
    we can stick the element at the bottom, with the bottom property.
