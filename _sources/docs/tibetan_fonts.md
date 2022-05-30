# Tibetan fonts

Tibetan fonts are difficult to produce due to the unlimited number of possible glyphs. While there are only a well defined set of 'standard' Tibetan syllables, there exists many extensions because of Sanskrit transliterations (e.g. mantras), Chinese transliterations, and Dzongkha shortcuts. Due to all of those extensions, it is virtually impossible to generate a 'complete' Tibetan font by providing all possible glyphs.

Microsoft had develop a system that could dynamically render new glyph variants, but the resulting Himalaya font doesn't work on non-Windows platforms and lacks the esthetics of preconceived glyphs. 

So Tibetan fonts either look artificial or are incomplete...

## Using fonts with an open license is important

If you are working on Tibetan projects that involve Sanskrit stacks (mantras), Chinese transliterations or Dzongkha shortcuts, then there will be the situation that a given font doesn't correctly render a stack that is needed. In such a situation, it is possible to extend a given font by providing additional glyphs for such a special case. See [Tibetan font creation](tibetan_font_creation.md) for details.

If the font you are using is not under a free license, then you won't be able to distribute any changes that you have made to a font to add needed glyphs.

### Recommendation

The `Noto` and `Babelstone` families of fonts are currently under activate development, so updates, improvements and bug-fixes are more likely.

- [Google's Noto-Fonts project](https://github.com/googlefonts/noto-fonts)
- [Andrew West's Babelstone project](https://www.babelstone.co.uk/Fonts/)
## Overview of freely available Unicode Tibetan fonts

The following list contains a number of fonts with good coverage of the most common glyphs and open licenses.

| Font name | Sample | Glyphs | Comment |
| --------- | :----: | ------ | ------- |
| [Tibetan Machine Uni](https://www.thlib.org/tools/scripts/wiki/tibetan%20machine%20uni.html) | ![Tibetan Machine Uni](Images/Font_Tibetan_Machine_Uni.jpg) | 5110 | Version 1.901 2007 (beta for v 2.00), one of the first Unicode fonts |
| [DDC Uchen](https://sites.google.com/view/chrisfynn/home/fonts/ddc-uchen) | ![DDC Uchen](Images/Font_Uchen.jpg) | 3193 | Version 1.000 preliminary, Chris Fynn's font |
| [Jomolhari](https://sites.google.com/view/chrisfynn/home/fonts/jomolhari) | ![Jomolhari](Images/Font_Jomolhari.jpg) | 3333 |  Version 1.000, Chris Fynn's font |
| [Babelstone Tibetan](https://www.babelstone.co.uk/Fonts/Download/BabelStoneTibetan.ttf) | ![Babelstone Tibetan](Images/Font_Babelstone_Tibetan.jpg) | 4019 | Version 10.008 April 21, 2022, extended version of Jomolhari |
| [Babelstone Tibetan Slim](https://www.babelstone.co.uk/Fonts/Download/BabelStoneTibetanSlim.ttf) | ![Babelstone Tibetan Slim](Images/Font_Babelstone_Tibetan_Slim.jpg) | 4019 | Version 10.008 April 21, 2022, extended version of Jomolhari, slim |
| [Noto Serif Tibetan](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan?noto.query=tibetan&noto.lang=bo_Tibt&noto.continent=Asia&noto.script=Tibt) | ![Noto Serif Tibetan](Images/Font_Noto_Serif_Tibetan.jpg) | 1891 | Google's Noto font, with many different weights. Linked Release version 2.001 (2022) has bugs, see  comment[^bug] for a solution. |
| Noto Sans Tibetan | ![Noto Sans Tibetan](Images/Font_Noto_Sans_Tibetan.jpg) | 1296 | Subset based on outdated version of Google's Serif Tibetan, do not use. |

[^bug]: Current release-version of `Noto Serif Tibetan`, version 2.001, renders the glyph དྡྷི incorrectly. A fix is available at [noto development repository](https://github.com/googlefonts/noto-fonts/issues/2362#:~:text=https%3A//github.com/googlefonts/noto%2Dfonts/blob/main/hinted/ttf/NotoSerifTibetan/NotoSerifTibetan%2DRegular.ttf). See discussion at [bug report](https://github.com/googlefonts/noto-fonts/issues/2362).
## Remarks and History

[Chris Fynn](https://sites.google.com/view/chrisfynn/home) was one of the first Unicode font pioneers. His fonts Jomolhari and DDC Uchen, available with free Open SIL licenses, where the basis of many developments.

[The Babelstone Project](https://collab.its.virginia.edu/wiki/tibetan-script/Tibetan%20Fonts.html) by Andrew West has continued the work on Jomolhari and updated the font to newer Unicode standards and extended the glyph coverage.

[The Tibetan & Himalayan Library](https://www.thlib.org/tools/scripts/wiki/tibetan%20machine%20uni.html) at Virginia University had bought the rights on the proprietary Tibetan Machine font with help of the Trace Foundation and made it freely available as one of the first Unicode fonts.

[Google's Noto font family](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan) provides Tibetan support and free support for virtually every language on earth for a large number of platforms.

## External sources

- [Tibetan fonts at University of Virginia](https://collab.its.virginia.edu/wiki/tibetan-script/Tibetan%20Fonts.html)