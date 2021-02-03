.Utilities  
----------
like borders,
        padding,margin,
        Width,height,
        Vertical Align,
        Display,Visibility,
        Float and Clearfix,
        Position,
        Close icon,
        Colors,background-colors.

i)Colors

Bootstrap 4 has some contextual classes
 .primary           (blue)
.success             (green)
.info                   (light-blue)
.warning           (orange)
.danger             (red)
.secondary        (gray)
.light                 (light-gray)
.dark                 (dark-gray)
.white                (white)

->if you want text to colored...then we can use like these below
 syntax : text-{one of contextual classes}
 
ex :text-primary

->Contextual text classes can also be used on links like ...
eg :<a href="#" class="text-danger">Danger link.</a>

ii)background-colors

->if you want background to colored...then we can use like these below
  syntax :bg-{one of contextual classes}

eg :bg-secondary

iii)Borders
Use border utilities to quickly style the
                                                     border and 
                                                     border-radius of an element. Great for images, buttons, or any other element.
  .border,
  .border-0,
  .border-top-0,
  .border-right-0,
  .border-bottom-0,
  .border-left-0

.COLOR to the border with any of the contextual border color classes
  .border-primary
  .border-success
  .border-info
  .border-warning
  .border-danger
  .border-secondary
  .border-light
  .border-dark
  .border-white


Border Radius
Add rounded corners to an element with the rounded classes

 .rounded
 .rounded-sm
 .rounded-lg
 .rounded-top
 .rounded-right
 .rounded-bottom
 .rounded-left
 .rounded-circle/pill
 .rounded-0

iv)Spacing

Bootstrap 4 has a wide range of responsive margin and
                                            padding utility classes. 
They work for all breakpoints: xs (<=576px),
                               sm (>=576px), 
                               md (>=768px), 
                               lg (>=992px) ,
                               xl (>=1200px)):

The classes are used in the format:  
                                             {property}{sides}-{size} for xs,
                                             {property}{sides}-{breakpoint}-{size} for sm, md, lg, and xl.

   eg :
         .m-# / m-*-# /                         {# -size,* -breakpoint}
         .m(l/b/r/t)-#
         .m(x/y)-# / m(x/y)-*-#           {x,y-axis}    

         .p-# / p-*-# /                           {# -size,* -breakpoint}
         .p(l/b/r/t)-#
         .p(x/y)-# / p(x/y)-*-#           {x,y-axis}  



Where property is one of:
    m - sets margin
    p - sets padding

Where sides is one of:
    t - sets margin-top or padding-top
    b - sets margin-bottom or padding-bottom
    l - sets margin-left or padding-left
    r - sets margin-right or padding-right
    x - sets both padding-left and padding-right or margin-left and margin-right
    y - sets both padding-top and padding-bottom or margin-top and margin-bottom
    blank - sets a margin or padding on all 4 sides of the element

Where size is one of:
    0 - sets margin or padding to 0
    1 - sets margin or padding to .25rem (4px if font-size is 16px)
    2 - sets margin or padding to .5rem (8px if font-size is 16px)
    3 - sets margin or padding to 1rem (16px if font-size is 16px)
    4 - sets margin or padding to 1.5rem (24px if font-size is 16px)
    5 - sets margin or padding to 3rem (48px if font-size is 16px)
    auto - sets margin to auto

Note: margins can also be negative, by adding an "n" in front of size:

    n1 - sets margin to -.25rem (-4px if font-size is 16px)
    n2 - sets margin to -.5rem (-8px if font-size is 16px)
    n3 - sets margin to -1rem (-16px if font-size is 16px)
    n4 - sets margin to -1.5rem (-24px if font-size is 16px)
    n5 - sets margin to -3rem (-48px if font-size is 16px)

v)Sizing
.Easily make an element as wide or as tall (relative to its parent) with our width and height utilities.
         .Width
        .height   

  .Width         : w-* classes
                        .w-25,
                        .w-50, 
                        .w-75,
                        .w-100,
                       .mw-100

  .height         : h-* classes
                       .h-25,
                       .h-50,
                       .h-75,
                       .h-100,
                       .mh-100

vi)Display & Visibility
  The classes are named using the format:                             
                                     .d-{value} for xs
                                     .d-{breakpoint}-{value} for sm, md, lg, and xl.

Where value is one of:

    none
    inline
    inline-block
    block
    table
    table-cell
    table-row
    flex
    inline-flex

Visibility
.Control the visibility. The classes are
                                                         .visible 
                                                         .invisible 



vii)Float and Clearfix
.Float an element to the right with the .float-right class or
                                               to the left with .float-left, and 
                                              clear floats with the .clearfix class.

.float-{left/right/none}
.float-{breakpoint}-{left/right/none}
.clearfix

viii)Position

.Quick positioning classes are available, though they are not responsive.
.position-static
.position-relative
.position-absolute
.position-fixed
.position-sticky


.Use these shorthand utilities for quickly configuring the position of an element.
.fixed-top
.fixed-bottom
.sticky-top

ix)Close icon
.Use the .close class to style a close icon.

x)Vertical Align
Use the align- classes to change the alignment of elements
 .align-baseline
 .align-top
 .align-middle
 .align-bottom
 .align-text-top
 .align-text-bottom
