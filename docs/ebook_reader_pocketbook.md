# Pocketbook ereader

```{image} Images/pocketbook.jpg
:align: right
:width: 320
```

Ebooks that come with embedded Tibetan font (like those from [Lotsawahouse](https://www.lotsawahouse.com)) display
correctly on latest Pocketbooks without additional configuration. In order to correctly display ebooks without embedded Tibetan
fonts, a new Tibetan font can be installed:

## New Tibetan fonts for the Pocketbook

Pocketbook uses Google's open Noto font family to display multilingual text. A Tibetan font is not installed by default,
so we add Tibetan from the Noto family:

- Download the Tibetan noto font from Google [Noto Serif Tibetan](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan)
- Connect the Pocketbook to a computer and open the folder `/system/fonts`
- Copy the `*.ttf` (currently: `NotoSerifTibetan-VariableFont_wght.ttf`) into the folder `/system/fonts` on the Pocketbook.

