# Odometer
 Original code from: https://github.com/HubSpot/odometer

 Odometer with additional options (currently WIP)

Specify options in `window.odometerOptions`

`animation` (String) the animation mode

- `byDigit` Each digit is animated on its own (like the YouTube Studio sub counter)
- `count` Increments the value without animation
- `minimal` Animation only shows the final value of the digit

`animationDirection` (String) If this is "down" then the direction of the animation is reversed.

`auto` (Boolean) automatically initialize things with class odometer

`directionByDigit` (Boolean) If true, the direction of each digit is determined by whether the digit itself goes up or down instead of being determined by the entire count

`downColor` (String) The color of the counter when it is counting down.

`duration` (Number) Duration of the animation in milliseconds

`el` (HTMLElement) HTML Element

`format` (String) digit format

`formatFunction` (Function) number format function with the number as a parameter

`selector` (String) HTML selector for the odometer to find things

`theme` (String) odometer theme

`value` (Number) odometer value

`upColor` (String) The color of the counter when it is counting up.
