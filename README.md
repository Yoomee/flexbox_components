# Flexbox components

A library of flexbox components, or blocks, with graceful fallback support for IE8+.

Vendor prefixes aren't used as [Autoprefixer](https://github.com/postcss/autoprefixer) should be used.


## Equal height cards

Cards will display in rows at the same height as the tallest sibling on that row.

[CodePen example](http://codepen.io/yoomee/pen/pgKoYv?editors=1100)

Usage:

```haml
.card-container
  .card-outer
    .card
```

## Media object

Used for displaying an image to one side, with descriptive content to the other.

[CodePen example](http://codepen.io/yoomee/pen/wMXaZy?editors=1100)

Usage:

```haml
.media
  %a{href: '#', class: 'media__object media__object--left'}
    %img{src: 'http://placehold.it/60x60'}
  .media__body
    Descriptive content
```
