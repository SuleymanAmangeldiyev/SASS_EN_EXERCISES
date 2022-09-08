
Add a new section to the layout as the picture displays. 
The boxes are squares of 45px per side (to be converted into rem) and their alignment is performed with flex rules.
The background color, the color, and the font-size can be handled using the flow control (@for, @if, etc...) and the darken and lighten methods (the numbers have a multiplier equal to 5) 
In particular, you need to create the classes .fs-1rem, .fs-2rem e .fs-3rem using @each
The added colors are black and white only


**Suggerimento (da inserire a parte e quindi da rimuovere dal readme)**
@for $var from 1 to 20 {
...
@if $var == 10 {
...


    }
}


-------------------------------

P.code for the section 2.

need to make...
step = s.

-------
keep to adding o;
s.1 = fz, 16 : o, 0;
s.2 = to add fz, and p-t;
s.3 = to add fz, and p-t;
--
to stop adding fz, and p-t;
s.4 = to start again to adding fz, p-t;
s.5 = (to use your own real programming k...);
s.6 = (...)