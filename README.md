<p align="center">
<img src="https://i.postimg.cc/Qtck3Nzc/MgEEygn7.gif" width="300"/>
  </br>
  </br>
A complete media query framework for CSS, to apply specific properties in specific screen</br>
Note: Size of every media query is `50px, 100px, 150px, 200px, 250px ....... 2500px`
</br>
</br>
  <img src="https://i.postimg.cc/KYwJbH8h/rohit-screen.gif" width="600"/>
</p>

## CDN
<img width="200" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/JsDelivr_Logo.svg/1200px-JsDelivr_Logo.svg.png"/>
### All-in-one
This is all-in-one CSS, its may make your site slow, We recommanded to use single css for each class. see below.

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rohit-chouhan/screen.css/dist/screen.css" type="text/css"/>
```
### For Single
`screen-max-show-hide.css`, `screen-min-show-hide.css`, `screen-max-color.css`,`screen-min-color.css`,`screen-max-font-size.css`, `screen-min-font-size.css`, `screen-max-height-width.css`, `screen-min-height-width.css`
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/rohit-chouhan/screen.css/dist/<css-file-here>" type="text/css"/>
```

### Usage
Always use type with dash scope (max or min) in the last of class with size, `-max300`, `-min600`.

```html
{class}{type}
hide-{type}
hide-max900 or hide-min900
```
### Classes for Hide & Show
|Class|Example|Description
|-----|--------|----------|
|hide-{type}{width}|hide-max600|hide specific content
|show-{type}{width}|show-min600|show specific content

### Classes for Color
|Class|Example|Description
|-----|--------|----------|
|fcolor-{color}|fcolor-red-max400|Color the font
|bcolor-{color}|bcolor-red-max400|Color on Background

### Classes for Size
All size will denotes as pixel (px) only. font max size is 854px. height-width max size is 1193px.
|Class|Example|Description
|-----|--------|----------|
|fsize-{size}| fsize-20-max700| Resize font
|height-{size} | height-400-min400 | Resize Height of elements
|weight-{size} | width-300-max400 | Resize Width of elements

<!-- ### Classes for Margin
`r` is the nagative value, thats mean if normal size of 20px, and you are using with `r` it will be -20px.
|Class|Example|Description
|-----|--------|----------|
|mall-{size}| mall-20-max700| Margin 20px from all side
|rmall-{size}| rmall-20-max700| Margin -20px from all side
|mt-{size}| mt-20-max700| Margin-top 20px
|rmt-{size}| rmt-20-max700| Margin-top -20px
|ml-{size}| ml-20-max700| Margin-left 20px
|rml-{size}| rml-20-max700| Margin-left -20px
|mb-{size}| mb-20-max700| Margin-bottom 20px
|rmb-{size}| rmb-20-max700| Margin-bottom -20px
|mr-{size}| mr-20-max700| Margin-right 20px
|rmr-{size}| rmr-20-max700| Margin-right -20px

### Classes for Padding
`r` is the nagative value, thats mean if normal size of 20px, and you are using with `r` it will be -20px.
|Class|Example|Description
|-----|--------|----------|
|pall-{size}| pall-20-max700| Padding 20px from all side
|rpall-{size}| rpall-20-max700| Padding -20px from all side
|pt-{size}| pt-20-max700| Padding-top 20px
|rpt-{size}| rpt-20-max700| Padding-top -20px
|pl-{size}| pl-20-max700| Padding-left 20px
|rpl-{size}| rpl-20-max700| Padding-left -20px
|pb-{size}| pb-20-max700| Padding-bottom 20px
|rpb-{size}| rpb-20-max700| Padding-bottom -20px
|pr-{size}| pr-20-max700| Padding-right 20px
|rpr-{size}| rpr-20-max700| Padding-right -20px
-->
## Note
In the first version this framework is only have classes for
show & hide, font-color, font-size, height, width, background, text-align, align-contents, align-items.

Create an issue if you want more feature or any property, thank you. 

Created by <a href="https://rohitchouhan.com">Rohit Chouhan</a>
