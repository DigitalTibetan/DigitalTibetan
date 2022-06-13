# Tibetan fonts

Tibetan fonts are difficult to produce due to the unlimited number of possible glyphs. While there are only a well defined set of 'standard' Tibetan syllables, there exists many extensions because of Sanskrit transliterations (e.g. mantras), Chinese transliterations, and Dzongkha shortcuts. Due to all of those extensions, it is virtually impossible to generate a 'complete' Tibetan font by providing all possible glyphs.

Microsoft had develop a system that could dynamically render new glyph variants, but the resulting Himalaya font doesn't work on non-Windows platforms and lacks the esthetics of preconceived glyphs. 

So Tibetan fonts either look artificial or are incomplete...

For more information about the history and development of the Tibetan scripts, see [History of Tibetan script](tibetan_script_history.md).
## Using fonts with an open license is important

If you are working on Tibetan projects that involve Sanskrit stacks (mantras), Chinese transliterations or Dzongkha shortcuts, then there will be the situation that a given font doesn't correctly render a stack that is needed. In such a situation, it is possible to extend a given font by providing additional glyphs for such a special case. See [Tibetan font creation](tibetan_font_creation.md) for details.

If the font you are using is not under a free license, then you won't be able to distribute any changes that you have made to a font to add needed glyphs.

### Recommendation

The `Noto` and `Babelstone` families of fonts are currently under activate development, so updates, improvements and bug-fixes are more likely.

- [Google's Noto-Fonts project](https://github.com/googlefonts/noto-fonts)
- [Andrew West's Babelstone project](https://www.babelstone.co.uk/Fonts/)
## Overview of freely available Unicode Tibetan fonts

The following list contains a number of fonts with good coverage of the most common glyphs and open licenses.

| Font name | Sample                | Glyphs | Comment |
| --------- | --------------------- | ------ | ------- |
| [Tibetan Machine Uni](https://www.thlib.org/tools/scripts/wiki/tibetan%20machine%20uni.html) | <img src="Images/Font_Tibetan_Machine_Uni.jpg" alt="Tibetan Machine Uni" width=640px /> | 5110 | Version 1.901 2007 (beta for v 2.00), one of the first Unicode fonts |
| [DDC Uchen](https://sites.google.com/view/chrisfynn/home/fonts/ddc-uchen) | ![DDC Uchen](Images/Font_Uchen.jpg) | 3193 | Version 1.000 preliminary, Chris Fynn's font |
| [Jomolhari](https://sites.google.com/view/chrisfynn/home/fonts/jomolhari) | ![Jomolhari](Images/Font_Jomolhari.jpg) | 3333 |  Version 1.000, Chris Fynn's font |
| [Babelstone Tibetan](https://www.babelstone.co.uk/Fonts/Download/BabelStoneTibetan.ttf) | ![Babelstone Tibetan](Images/Font_Babelstone_Tibetan.jpg) | 4019 | Version 10.008 April 21, 2022, extended version of Jomolhari |
| [Babelstone Tibetan Slim](https://www.babelstone.co.uk/Fonts/Download/BabelStoneTibetanSlim.ttf) | ![Babelstone Tibetan Slim](Images/Font_Babelstone_Tibetan_Slim.jpg) | 4019 | Version 10.008 April 21, 2022, extended version of Jomolhari, slim |
| [Noto Serif Tibetan](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan?noto.query=tibetan&noto.lang=bo_Tibt&noto.continent=Asia&noto.script=Tibt) | ![Noto Serif Tibetan](Images/Font_Noto_Serif_Tibetan.jpg) | 1891 | Google's Noto font, with many different weights. Linked Release version 2.001 (2022) has bugs, see  comment[^bug] for a solution. |
| Noto Sans Tibetan | ![Noto Sans Tibetan](Images/Font_Noto_Sans_Tibetan.jpg) | 1296 | Subset based on outdated version of Google's Serif Tibetan, do not use. |

[^bug]: Current (2022-06) release-version of `Noto Serif Tibetan`, version 2.001, renders the glyph དྡྷི incorrectly. A fix is available at [noto development repository](https://github.com/googlefonts/noto-fonts/issues/2362#:~:text=https%3A//github.com/googlefonts/noto%2Dfonts/blob/main/hinted/ttf/NotoSerifTibetan/NotoSerifTibetan%2DRegular.ttf). See discussion at [bug report](https://github.com/googlefonts/noto-fonts/issues/2362).

### Text samples[^ref_lotsawahouse]

Longer text samples, created with Scribus.
* [Scribus document](https://digitaltibetan.github.io/DigitalTibetan/TibTest.sla)
* [PDF version](https://digitaltibetan.github.io/DigitalTibetan/TibTest.pdf)

| Samples |  |
| ------- | ------- |
| ![Tibetan Machine Uni](Images/TextSample_TibetanMachineUni.jpg) | ![DDC Uchen](Images/TextSample_DDCUchen.jpg) |
| ![Jomolhari](Images/TextSample_Jomolhari.jpg) | ![Babelstone Tibetan](Images/TextSample_BabelstoneTibetan.jpg) |
| ![Noto Serif Tibetan](Images/TextSample_NotoSerifTibetan.jpg)

[^ref_lotsawahouse]: Sample text by Nāgārjuna taken from [Lotsawa House](https://www.lotsawahouse.org/bo/indian-masters/nagarjuna/essence-dharmadhatu)
## Qomolangma Tibetan Unicode Fonts

These fonts are [free for non-commercial use](http://www.yalasoo.com/English/docs/yalasoo_en_qomolangma_fonts.html) only.

Download the Qomolangma collection [here](http://www.yalasoo.com/files/CTRCfonts.rar). (at [Yalasoo font page](http://www.yalasoo.com/English/docs/yalasoo_en_qomolangma_fonts.html))
### Uchen fonts

| Font name | Sample | Glyphs | Comment |
| --------- | :----: | ------ | ------- |
| Qomolangma-Subtitle | ![Qomolangma-Subtitle](Images/Font_Qomolangma_Subtitle.jpg) | 1561 | Version 1.00, 2013, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Title | ![Qomolangma-Title](Images/Font_Qomolangma_Title.jpg) | 1561 | Version 1.00, 2013, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Uchen Sarchen | ![Qomolangma-Uchen Sarchen](Images/Font_Qomolangma_Uchen_Sarchen.jpg) | 1563 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Uchen Sarchung | ![Qomolangma-Uchen Sarchung](Images/Font_Qomolangma_Uchen_Sarchung.jpg) | 1563 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Uchen Suring | ![Qomolangma-Uchen Suring](Images/Font_Qomolangma_Uchen_Suring.jpg) | 1564 | Version 2.00, 2009, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Uchen Sutung | ![Qomolangma-Uchen Sutung](Images/Font_Qomolangma_Uchen_Sutung.jpg) | 1477 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |

### Artistic variations

| Font name | Sample | Glyphs | Comment |
| --------- | :----: | ------ | ------- |
| Qomolangma-Art | ![Qomolangma-Art](Images/Font_Qomolangma_Art.jpg) | 1562 | Version 1.00 June 18, 2014, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Dunhang | ![Qomolangma-Dunhang](Images/Font_Qomolangma_Dunhang.jpg) | 1562 | Version 1.00, 2015, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Woodblock | ![Qomolangma-Woodblock](Images/Font_Qomolangma_Woodblock.jpg) | 1561 | Version 2.00, 2014, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |

### Cursive variants

See [Tibetan calligraphy](https://en.wikipedia.org/wiki/Tibetan_calligraphy).

| Font name | Sample | Glyphs | Comment |
| --------- | :----: | ------ | ------- |
| Qomolangma-Betsu | ![Qomolangma-Betsu](Images/Font_Qomolangma_Betsu.jpg) | 1404 | `dbu med` script ([Umê](https://en.wikipedia.org/wiki/Um%C3%AA_script)) used for scriptures. Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Drutsa | ![Qomolangma-Drutsa](Images/Font_Qomolangma_Drutsa.jpg) | 1415 | `dbu med` script ([Umê](https://en.wikipedia.org/wiki/Um%C3%AA_script)) used for documents. Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Chuyig | ![Qomolangma-Chuyig](Images/Font_Qomolangma_Chuyig.jpg) | 1655 | Version 2.00, 2009, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Tsumachu | ![Qomolangma-Tsumachu](Images/Font_Qomolangma_Tsumachu.jpg) | 1526 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Tsutong | ![Qomolangma-Tsutong](Images/Font_Qomolangma_Tsutong.jpg) | 1562 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Edict | ![Qomolangma-Edict](Images/Font_Qomolangma_Edict.jpg) | 1562 | Version 1.00, 2013, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |
| Qomolangma-Tsuring | ![Qomolangma-Tsuring](Images/Font_Qomolangma_Tsuring.jpg) | 1562 | Version 2.00, 2008, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab |

### Mongolian, `'phags-pa` (Tibetan variant)

| Qomolangma-horyig |  |  |
| ----------------- | :- | - |
| <img src="Images/Font_Qomolangma_Horyig.jpg" width="30px" /> | **Qomolangma-horyig**<br><br>A vertical `'phags pa ` script that uses Tibetan letters. 1562 glyphs. Version 1.00, 2013, China Tibetology Research Center, Tashi Tsering and Wangdra Gyab<br>Note: this font encodes `'phags pa` incorrectly on the Unicode-pages of Tibetan (`0x0f00`), whereas `'phags pa` has it's own Unicode page at `0xA840`. Due to the use of the Tibetan page, horyig must be manually turned 90&deg;.  | <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Liu_Yigong_1324.jpg" width=240px /><br>A `'phags pa` inscriptions on an Italian tombstone of the 14th century.[^jesus_silkroad][^mongol_western] |

See also: [`'Phags-pa` Wikipedia](https://en.wikipedia.org/wiki/%CA%BCPhags-pa_script)

[^jesus_silkroad]: ([Jesus on the Silk Road by Dale A. Johnson p.73](https://books.google.com/books?id=kWTDfRythVkC&pg=PA73))
[^mongol_western]: [Mongol elements in Western medieval art](https://en.wikipedia.org/wiki/Mongol_elements_in_Western_medieval_art)

## OS-specific fonts

* [macOS only fonts Kokonor, Kailasa](fonts_macos)
* [Windows only fonts, Himalaya](fonts_windows)
## Remarks and History

For more information about the history and development of the Tibetan scripts, see [History of Tibetan script](tibetan_script_history.md).

[Chris Fynn](https://sites.google.com/view/chrisfynn/home) was one of the first Unicode font pioneers. His fonts Jomolhari and DDC Uchen, available with free Open SIL licenses, where the basis of many developments.

[The Babelstone Project](https://collab.its.virginia.edu/wiki/tibetan-script/Tibetan%20Fonts.html) by Andrew West has continued the work on Jomolhari and updated the font to newer Unicode standards and extended the glyph coverage.

[The Tibetan & Himalayan Library](https://www.thlib.org/tools/scripts/wiki/tibetan%20machine%20uni.html) at Virginia University had bought the rights on the proprietary Tibetan Machine font with help of the Trace Foundation and made it freely available as one of the first Unicode fonts.

[Google's Noto font family](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan) provides Tibetan support and free support for virtually every language on earth for a large number of platforms.

[The Qomolangma font project](http://www.yalasoo.com/English/docs/yalasoo_en_qomolangma_fonts.html) at Yalasoo, created with support by the Central Tibetan Relief Committee, [CTRC](https://centraltibetanreliefcommittee.net/).

## Pre-Unicode fonts

Old digital Tibetan files often use ancient pre-Unicode fonts. The following list contains the most frequent types. All of those fonts use their own proprietary encoding, check [Conversion of old Tibetan text](tibetan_pre_unicode.md) for information on how to convert old documents to modern Unicode.

(pre_unicode_font_list)=
- TibetanMachine (free download: [pktc.org](http://www.pktc.org/pktc/download.htm#FreeTypeface)) and TibetanCaligraphic, TibetanClassic, DzongkhaCaligraphic (commercial fonts: [www.pktc.org](http://www.pktc.org/pktc/SFTtypefaces.htm))
- TibetanMachineWeb (free download: [www.pktc.org](https://pktc.org/tibetan-software/free-downloads/#FreeTypeface))
- Tibetan Modern A (free download: [virginia.edu](https://collab.itc.virginia.edu/access/wiki/site/26a34146-33a6-48ce-001e-f16ce7908a6a/tibetan%20modern%20a.html).)
- Robillard (Ltibetan, etc) (free download: [UDP website](http://udp.leighb.com/robillard.exe)).
- Sambhota including Dedris, Eedris, Esama/b/c, Sama/b/c, Samw (was a free download if only used to view [ACIP](http://www.asianclassics.org/) documents, otherwise commercial license required, see updated at: [nitartha.net](http://www.nitartha.net/).)
- TIBETBT (free download via [THDL](https://collab.itc.virginia.edu/access/wiki/site/26a34146-33a6-48ce-001e-f16ce7908a6a/tibetbt.html)
(extension_a)=
- fonts derived from the "P.R.C. National Standard for Tibetan (Extension A)" (aka "Set A"). For a documentation see Chris Fynn's website: [Tibetan Extension A](https://sites.google.com/view/chrisfynn/home/tibetanscriptfonts/standardization/precomposedtibetan-parta). Chris Fynn's Jomolhari supports this standard.
- TCRC Bod-Yig, TCRC Youtsoweb, TCRC Youtso (free download: [www.tchrd.org](http://www.tchrd.org/tibetan/download/)

## External sources

- [Tibetan fonts at University of Virginia](https://collab.its.virginia.edu/wiki/tibetan-script/Tibetan%20Fonts.html)
- [Qomolangma Tibetan Unicode Fonts](http://www.yalasoo.com/English/docs/yalasoo_en_qomolangma_fonts.html)
