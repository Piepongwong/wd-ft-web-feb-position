# Position

The 3 most important position values are:
*   fixed
*   absolute
*   relative


The naming of these values is, in my opinion, terrible. They are all relative to something;

Fixed means relative to the viewport.
Absolute means relative to the parent html element.
Relative means relative to it's normal position.

If you want to use absolute, there'se 1 catch. The parent element needs to have it's position set. You could for example set it to relative and do nothing with it.
