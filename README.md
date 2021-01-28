# Frontend Mentor Testimonials Challenge

<https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7>


Just wanted to work on my CSS grid skills. As always, this is fully responsive to both changes in view port width and changes in text size. I did deviate from the specs just a little. In particular, some of the text/background color combos did not have enough contrast to be accessible and thus I had to alter them.

One thing I learned from this project is that Firefox is currently the only browser that allows you to use mixed units in calc() for media query break points. I usually do my primary development in FF and thus when I tested this in Chrome I was very surprised to see that it didn't work. This wasn't a showstopper, but I did have to settle for a close approximation on the break points instead of the perfect ones I had with FF.

A few details lacking from the specs for this challenge:

* It is not clear if there is a minimum width requirement for the wider cards. As you transition from a multi-column to single-column layout I didn't know if the wider cards were allowed to get skinnier until we reached the single-column break point. I decided to keep them a static width and thus when we reach the single-column break point there is some empty space on the sides.
* It would be nice to know a little more about how these cards would be generated and especially how the color order is determined. Is color based on position? Or is that information passed in with the card? It's a minor issue and doesn't prevent you from completing the challenge but it does have an impact on  CSS.
* We got a design image for a narrow view port and a very wide view port but not for a medium view port transition. Going from three columns to one column seems a little extreme so it would have been nice to know what was expected for an intermediate view port width, especially since having an odd number of items doesn't lend itself to an obvious answer. I decided to create a third row and put the odd one there, centered by itself.

Lastly, I usually do not impose a font size on my viewers but this challenge called for a body font size of 13px. Against my better judgement I acquiesced and I apologize to those of you who can't read this out of the box. Fortunately, I make all of my work responsive to text only zoom, so feel free to manually crank up the text size as much as you need.
