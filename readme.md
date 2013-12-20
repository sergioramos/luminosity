# luminosity

luminosity functions from [harthur/color](https://github.com/harthur/color)

## install

```bash
component install ramitos/luminosity
```

## api

The WCAG luminosity of the color. 0 is black, 1 is white.
#### .luminosity(array: rbg)

The WCAG contrast ratio to another color, from 1 (same color) to 21 (contrast b/w white and black).
#### .contrast(array: rgb1, array: rgb2)

Get whether the color is "dark"/"light"
#### .dark(array: rgb) / .light(array: rgb)

## license

MIT