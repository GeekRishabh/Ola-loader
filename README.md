<h1 align="center">OLA/Uber nearby Driver loader for React Native</h1>
<p align="center">Uber driver request loader for your react native app</p>


### API

| Property       | Type          | Default             | Description |
| -------------  |:-------------:|:------------:       | ----------- |
| interval       | number        | 2000                | action buttons visible or not
| size           | number        | 100                 | width and height of the avatar
| pulseMaxSize   | number        | 250                 | maximum size of the pulse in the background
| avatar         | string        | undefined           | **required** avatar url to display
| pressInValue   | number        | 0.8                 | should be between 0 and 1. scale of the avatar, when pressed in
| pressDuration  | number        | 150                 | duration of the scale animation
| pressInEasing  | Easing        | Easing.in           | easing type of the press in animation
| pressOutEasing | Easing        | Easing.out          | easing type of the press out animation
| borderColor    | string        | "#0F517F"           | border color of the pulse
| backgroundColor| string        | "#1b557a"         | background color of the pulse
| getStyle       | function      | undefined           | override the styling of the pulse. gets as parameter the Animated variable. e.g. (anim) => ({ backgroundColor: 'yellow' })
