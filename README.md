# Snowfall Animation
This application is a simple CSS animation that simulates a snowfall. It uses Sass to generate random values for the position, size, and color of snowflakes, and assigns these values to the box-shadow property of three classes: .layer1, .layer2, and .layer3.

## How to use
To use this animation, include the CSS file in your HTML file, and add the class snow to the element you want the snowfall to appear on. The animation is set to infinite iteration, so it will continue to run indefinitely.

You can adjust the animation-duration, animation-delay, and animation-name properties to change the animation's speed, delay and the falling motion respectively.

## Customization
You can customize the snowflakes' color by adjusting the color value in the box-shadow property of the .layer1, .layer2, and .layer3 classes.

You can also change the size of the snowflakes by adjusting the width and height properties of the .layer1, .layer2, and .layer3 classes.

Additionally, you can adjust the blur effect of the snowflakes by adjusting the value of the filter: blur(value) property in the .layer2 and .layer3 classes.

## Browser Compatibility
This animation uses CSS animation and Sass, which are widely supported by modern browsers. However, if you need to support older browsers, you may need to use a fallback or a polyfill.

## Conclusion
This is a simple yet elegant snowfall animation that can be easily integrated into your website to add a touch of winter magic. With a few adjustments, you can customize the animation to match your website's design.
