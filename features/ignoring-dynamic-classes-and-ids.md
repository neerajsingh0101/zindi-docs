
## Ignoring Dynamic Classes and Ids

CSS classes are added to elements dynamically as the user is interacting with the web application. For example a class can be added to an element as you hover over it, or a class can be added based on the state (open/close ) of the element when you interact  with it.

The Trinity Chrome Extension tracks all the classes that are added to the elements dynamically ( after page load ) and ignores them for generating the CSS selector.

This results in css selectors which are robust and less brittle.
