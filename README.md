# Odometer
 Original code from: https://github.com/HubSpot/odometer

 Odometer with additional options (currently WIP)

Specify options in `window.odometerOptions`

`animation` (String) The animation mode

- `byDigit` Each digit is animated on its own (like the YouTube Studio sub counter)
- `count` Increments the value without animation
- `minimal` Animation only shows the final value of the digit

`auto` (Boolean) Automatically initialize things with class odometer

`directionByDigit` (Boolean) If true, the direction of each digit is determined by whether the digit itself goes up or down instead of being determined by the entire count

`downColor` (String) The color of the counter when it is counting down.

`duration` (Number) Duration of the animation in milliseconds

`el` (HTMLElement) HTML Element

`format` (String) The digit format.

`formatFunction` (Function) Number format function with the number as a parameter

`removeLeadingZeros` (Boolean) If true, leading zeros will not show during the animation if the number of digits changes.

`reverseAnimation` (Boolean) If true, the direction of the animation is reversed.

`selector` (String) HTML selector for the odometer to find things

`theme` (String) Odometer theme

`value` (Number) Odometer value

`upColor` (String) The color of the counter when it is counting up.
