# Cool Borders

Cool borders is a really small CSS library which can be used to add some gradient based border flair to your website.

It's inspired by the `explanation` class at the bottom of the CSS Tricks article [Web History Chapter 2: Browsers](https://css-tricks.com/chapter-2-browsers/). That class uses `background: linear-gradient()` and `border-left` rules on the acutal element being styled and an absolutely positioned`::after` pseudo-element with `background: linear-gradient()` to create the whole effect.

Cool Borders uses the same approach to create the same effect but from a variety of starting points and directions. 

There two types of effects - corners or three sided (like the one in the CSS Tricks article). 

All effects are created using two classes. All need the base class `.cool-border` and another which decides the effect type, origin and direction. 

Using Cool Borders to create the same effect takes two classes - `.cool-border` and `.cool-border-h-top-left`. 
