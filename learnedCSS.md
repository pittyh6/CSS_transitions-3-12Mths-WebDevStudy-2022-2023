# Web Developer Study
## 12 months web developer study. I decided to dedicate at least 12 months to learn web development.

![Begin Banner](/Documentation/top-1200x350.gif)

* Online courses, challenges and creation of my own projects.

## What I learned/used 
### CSS 
* Cascading Style Sheets (CSS) 
    * transition
        * The property that we want to transition & The duration of the transition.
            * transition-property: background-color/color;
                * Color values, like color and background-color, will blend to a new color.
                * Length values like font-size, width, and height will grow or shrink.
            * transition-duration: 2s;
                * Duration is specified in seconds or milliseconds, such as 3s, 0.75s, 500ms.
            * transition-timing-function
                * ease-in — starts slow, accelerates quickly, stops abruptly
                * ease-out — begins abruptly, slows down, and ends slowly
                * ease-in-out — starts slow, gets fast in the middle, and ends slowly
                * linear — constant speed throughout
            * transition-delay.
                * transition-delay: 250ms;
            * Shorthand
                * Because these four properties (transition-property, transition-duration,transition-timing-function,  transition-delay ) are so frequently declared together, CSS provides a property that can be used to declare them all in one line: transition. This shorthand property describes each aspect of the transition puzzle in a single declaration. The properties must be specified in this order: transition-property, transition-duration, transition-timing-function, transition-delay.
                    * transition: color 1.5s linear 0.5s;
            *   * Combinations
                    * The shorthand transition rule has one advantage over the set of separate transition-<property> rules: you can describe unique transitions for multiple properties, and combine them.
                        * To combine transitions, add a comma (,) before the semicolon (;) in your rule. After the comma, use the same shorthand syntax. For example:
                            * transition: color 1s linear, font-size 750ms ease-in 100ms;
                            * transition: width 750ms ease-in 200ms, left 500ms ease-out 450ms, font-size 950ms linear;
            *   * all
                    * all means every value that changes will be transitioned in the same way. You can use all with the separate transition properties, or the shorthand syntax. This allows you to describe the transition of many properties with a single line:
                        * transition: all 1.5s linear 0.5s;
        * CSS Transitions have 4 components:
            * A property that will transition.
            * The duration which describes how long the transition takes.
            * The delay to pause before the transition will take place.
            * The timing function that describes the transition’s acceleration.
        



![End Banner](/Documentation/botton-1200x350.gif)