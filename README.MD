This is one of several projects to demonstrate usage of vanilla usage of JS. No frameworks like JQuery, etc. Just plain old JS. This project associates a sound and HTML transition with a particular keycode. There are some feeble attempts in the styling to handle both mobile and larger screens. 

See this website for a quick and easy way to display keycode values: http://keycode.info/

This project originates from and is largely based on a tutuorial from Wes Bos. I've added a few comments, reorganized some styling, added (weak) support for mobile, added mouse click support, etc. But the original idea and structure is from him.

This project demonstrates a few things:

* Adding event listeners for mouse clicks, keydown, and transitionend (as opposed to using a timer function) events. 
* Node List foreach loops (instead of arrays)
* JS query selection on classes (.key) and HTML tags, and examples of the JS attribute selector [] syntax
* Playing an audio tag
* Example of using "event.currentTarget". Also see, https://github.com/rmemory/VanillaJSTargetVsCurrentTarget.
* Adding and removing a class from a tag using <element>.classList.add and <element>.classList.add.
* Simple usage of CSS Flex, and mobile support
* CSS transforms and transitions. 
  
To view this project, simply clone it, and open index.html in your browswer. No databases, routing, or any backend required.
