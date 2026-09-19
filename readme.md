 % = height&width according to parent
px = fixed 
vh & vq = height & width according to screen 


vmax = viewport maximum (when there will be a time when width will be smaller than the height , so at that time the height deimensions will be applied to the width) or (when anyone of height or width will be less than the other the maximum will be applied automatically )

vmin = viewport minimum (vice-versa of the vamax )


em = takes the font-size according to parent 
example : let suppose we give parent the fontsize 20px
          and the child is h1 in the parent if we given 
          that child 2em font size than the font size of 
          that child will be 20px*2 = 40px ...

rem = takes the font-size 16px 
So:
#box font-size = 16px
Now the browser has built-in styles roughly like:
h1 {
    font-size: 2em;
}
h2 {
    font-size: 1.5em;
}
p {
    font-size: 1em;
}


ch = character wise width 
means suppose 20ch than a line will have max. 20 characters null will also be counted

lh = leaving space according to how much the line takes
     like if a line height is something like 2px than if we 
     give margin-top = 2lh than it will leave space between the 
     upper para and lower para with 2line height 4px 
     (image-1.png)->normal without lh
     (image.png)->with 2lh