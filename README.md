# screen.css
A complete media query framework for CSS, to apply specific properties in specific screen

## CDN
Copy and paste the code to your page inside head tag.
```html
Link
```
### Usage
Always use type with dash scope (max or min) in the last of class with size, `-max300`, `-min600`.
```html
{class}{type}
hide-on{type}
hide-on-max900
```
### Classes for Hide & Show
|Class|Example|Description
|-----|--------|----------|
|hide-on-{type}{width}|hide-on-max600|hide specific content
|show-on-{type}{width}|show-on-max600|show specific content

### Classes for Color
|Class|Example|Description
|-----|--------|----------|
|fcolor-{color}-on-{type}{width}|fcolor-red-on-max400|Color the font
|bcolor-{color}-on-{type}{width}|bcolor-red-on-max400|Color on Background

### Classes for Size
|Class|Example|Description
|-----|--------|----------|
|fsize-{size}-on| fsize-20-on-max700| Resize font
|height-{size}-on | height-400-on-min400 | Resize Height of elements
|weight-{size}-on | width-300-on-max400 | Resize Width of elements

## Note
In the first version this framework is only have classes for
show & hide, font-color, font-size, height, width, background, text-align, align-contents, align-items, margins, paddings.

Create an issue if you want more feature or any property, thank you. 
