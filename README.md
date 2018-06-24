# Web Animation API Timeline Demo

The web animation API (WAPI) is an experimental browser API that combines both advantages of JS & CSS based animations into one. Popular library like EaseJS & React Sprint take a function approach to animations, where an animation is a pure function that takes in the time & returns the appropriate CSS styles. The disadvantages of the javascript based approaches are loss of hardware acceleration & no agreed upon standard, like with CSS animations.

The web animations API promises to combine the best of both worlds. It has a similar conceptual model to libraries like greensocket tween lite where animations can be staggered, sequenced & grouped. Animations can be paused, slowed down, reversed, or programmatically scrubbed.

In this demo I have used some polyfill code provided by Google & created a demo with 2 independent animations. The play button plays & pauses each animation separately. The scrubber allows manually scrubbing through the animation.

I found that in the official web animations API polyfill github repository, it did not support 2 independant timelines on the same page, only a global timeline. This proof of concept implements independant timelines as promised by the spec. All credit goes to Google

# Links 
- https://github.com/daneden/animate.css
- https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API
- https://drafts.csswg.org/web-animations/
- https://github.com/web-animations/web-animations-js