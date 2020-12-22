# FYLO LANDING PAGE

## About Project

Hi, I've used Html5, Css3 and Sass in this project. And of course without using any framework, I've tried to write pure Css using flexbox, grid technologies. In the Sass I've created reusable code block such as:

'@mixin flex($flex-directon, $justify-content, $align-items, $display: 'flex');'

## Responsiveness

Device dimensions tend to change over time. Therefore I've used content-based media queries not device-based. And I've tried to call them declarative in Sass such as:

'@mixin for-tablet-landscape-up{
    @media (min-width: 56.25em) //900px {@content;}
}
