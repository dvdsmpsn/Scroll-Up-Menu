# Scroll Up Menu - a jQuery plugin for mobile

## Born out of annoyance

Fixed headers and menus are everywhere on mobile sites. I hate then. On iOS for example, they really get in the way if you're viewing a page in a WebView for some application. This isn't a big deal on Android because the browser takes control.

Either way, fixed headers are really annoying, especially when paired with fixed footers for advertisments.

## Scroll up for menu pattern

Having browsed [wired.com](http://wired.com/) on iOS, I noticed that their menu/header disappears out of the way when you're reading an article. Scrolling up slightly conveniently activates the header menu immediately.

This is a great pattern for mobile sites. It maximises the available space for content yet makes navigation a doddle.

I couldn't find any mention of this pattern elsewhere, so leaped ahead and built the code to achieve this.

Usage:

````
$('#top').scrollUpMenu();
````

This assumes that the header is contained in a `#top` selector.

[Fork me on Github](https://github.com/dvdsmpsn/Scroll-Up-Menu).