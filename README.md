# sticky-footer

This code is based on code from Ryan Fait, who's code I've used extensively in my designs.
But I found that the original code had been duplicated on other sites with minor changes but somehow didn't work as intended.
So I made this repository to be used as an archive for a working template.

Keep in mind that when you copy this into your code you need to make sure the right content is in between the intended `<div>` tags.
I hope the `<!-- remarks -->` are clear about what code to put where.


# notice
## Regarding `#wrapper` bottom-margin.

If you have more `<div>` sections underneath `#footer-wrap` you need to include the total height of those sections into the `margin-bottom` value of `#wrapper` in de style.css file. Otherwise your sections underneath `#footer-wrap` will disappear beneath the view window.
