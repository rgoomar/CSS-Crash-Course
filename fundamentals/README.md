# Examples of some fundamental CSS attributes

## Display
I highly recommend you read [MDN - Display](https://developer.mozilla.org/en-US/docs/Web/CSS/display) about what each display type does  
The given example shows what the display property can do with a few different display properties.

If you look at the example, you will notice that the area where ```display: inline``` is used isn't displaying anything. Why is that?

## Padding vs Margin
Padding is typically used to add in space between the element's edges and the content within the element.  
Margin is typically used to add in a gap between different elements.

Go through the files and change some of the ```padding``` values to ```margin``` and watch what happens.

Also, open up your browser debugger and see how the padding or margin changes the element.

## Alignment
There are many different ways to do alignments. You can add in ```float```, ```text-align```, and many more. But, this example focuses on those two for the time being.  
I encourage you to experiment and try to align your elements in whichever way you like.

You will notice that ```Box #1``` is now on the right even though it is declared before ```Box #2```. Floats ignore the direct order and go immediately to the far left or right
of the parent element depending on which float you used.

## Pseudo Selectors (See the CSS in alignment.html)
The ```.box:first-child``` pseudo class is saying the first instance of the ```box``` class. This is a little confusing because you would think that it would mean
that the parent element should have the ```:first-child``` pseudo class, but CSS is weird.  
See [this link](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) for more information.

## Scrollable
There are many times (like a chat room) that you would want to setup a fixed space that the user sees,
which they can then scroll through to view the rest of the messages.  
See [MDN - Overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)

## Positioning Elements
Look at the html file and the CSS within there. There are a lot of comments that can help you determine how those positioning values work.

I would say the most important thing to take out of it is how ```relative``` and ```absolute``` positioning work with eachother.   
It can help you create drawings and more intricate designs.  
