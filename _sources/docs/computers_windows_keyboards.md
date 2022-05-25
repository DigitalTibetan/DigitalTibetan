# Tibetan keyboards for Windows
## Overview

There are several options to type Tibetan on Windows

- [Denjong TibType Wylie keyboard](keyboard_denjong)
- [TISE Wylie keyboard](keyboard_tise)
- Windows' built-in Tibetan input method `Tibetan (PRC)`

```{Admonition} General overview
:class: tip
For different keyboards and their support on different platform see: [Tibetan keyboards](tibetan_keyboards.md)
```

## Windows Tibetan input method `Tibetan (PRC)`

```{image} Images/windows_keyboard_config.jpg
:align: right
:width: 480
```

`Tibetan (PRC)` can be installed via Windows settings. Simply add a keyboard `Tibetan`. Note that `Tibetan (PRC)` is not Wylie compliant, see below for alternatives.

(keyboard_tise)=
## Extended Wylie-Keyboard: TISE

[**TISE**](https://tise.mokhin.org/) (pronounced 'tee-say') is a Tibetan input utility for Windows XP, Vista, 7, 8, and 10.

TISE is a free Wylie input method that runs on XP, Vista and Windows 7 (32 and 64 bit (since version 2.0)). You can download the software from:

http://tise.mokhin.org/ (version 2.0, Nov. 2012, supports both 32 and 64 bit)

### A short introduction: Typing Tibetan with TISE[^1]

```{image} https://tise.mokhin.org/tise.png
:align: right
```
Start the TISE program: you will see a Mount-Kailash icon on the right side of Windows task-bar.

TISE can be switched on and off with `<shift><space>`, or by clicking on the Mount-Kailash icon on the right side of Windows task-bar. Note that the sun in the icon indicates the activity-state of TISE.

Make sure to familiarize yourself with EWTS (extended Wylie) using [Teaching EWTS](https://www.thlib.org/reference/transliteration/teachingewts.pdf) by Alexandru Anton-Luca.

Note: TISE seems to be incompatible with some applications, if TISE doesn't work in your application, the recommended input method would be [Denjong](keyboard_denjong). Alternatively, if you want to use TISE with GoldenDict, you can type the search-phrase in some other program (e.g. notepad) and then copy&paste the search term into GoldenDict.

#### Basic letters

- All basic Tibetan and Tibetan Sanskrit represented by EWTS scheme are supported by Tise. Often typing the final `a` as in `ka` ཀ is not necessary, `k` followed by a tsheg `<space>` is enough.
- Longer vowels (with a subjoined small letter achung) are typed as `aa` ཨཱ, `ii` ཨཱི, `uu` ཨཱུ, `ee` ཨཱེ, `oo` ཨཱོ, or `A` ཨཱ, `I` ཨཱི, `U` ཨཱུ, `E` ཨཱེ, `O` ཨཱོ.
- Retroflex i ྀ is typed as `-i`, and retroflex i with achung as `-I` ཱྀ, e.g. `k-i` ཀྀ, `k-I` ཀཱྀ.
- `au` ཨཽ, `ai` ཨཻ are implemented.

#### Tibetan punctuation

- As per EWTS, asterisk `*` types non-breaking tsheg (0x0f0c) `་`.
- Typing `_` (underscore) gives 0xa0 (non-breaking space).
- Regular space (0x20) is typed by `x` key.

#### Tibetan Sanskrit letters

- As per EWTS, they are usually typed as capital letter (with Shift key pressed). Implemented are the following Tibetan Sanskrit letters: `Ta` ཊ, `Tha` ཋ, `Da` ཌ, `Na` ཎ, `Sha` ཥ (the latter can be type as `S`) `R+` ཪ, `+W` ྺ, `+Y` ྻ, `+R` ྼ, (fixed form ra, wa, ya, e.g. ཪྟ་ རྻ་ མྺ་ ཡྼ་)
- `H` ཿ, `M` ཾ, `&` ྅, `?` ྄.
- For the sake of simplicity, EWTS `~M` and `~M` are typed as `q`  ྃ and `Q`  ྂ respectively.

#### Complex stacks

This is the major improvement of EWTS compared to previous approaches, and Tise fully takes advantage of this. In Tise stacks are typed using `+` symbol to stack glyphs vertically. If vertical stack is not what is desired, it is possible to quit vertical stacking mode by typing `.` (or just type a vowel or a tsheg if the syllable is complete).

#### Examples

- `gya` གྱ is stacked, but `g.ya` གཡ isn't.
- to type _siddhi_ use: `si.ddhi` or `sid+d+hi`. In many cases, as with all standard Wylie EWTS sequences like `brdza` བརྫ, for example, typing extra `+` sign is not required, Tise tries to be user friendly by minimizing the number of key hits needed for typing.
- More examples: `hUq` ཧཱུྃ་, `hUQ` ཧཱུྂ, `d+hIH` དྷཱིཿ, `oMAHhUQ` ཨོཾ་ཨཱཿཧཱུྂ.

[^1]: taken from TISE readme.

(keyboard_denjong)=
## Extended Wylie keyboard: Denjong Tib-Type

[**Denjong Tib-Type**](https://github.com/thubtenrigzin/DenjongTibType) is a free Tibetan Unicode typing system based on Wylie that works on all Windows platforms including 32 & 64 bits versions. The website and a more detailed documentation are on elaboration but you can, by now, download and install the product from:

https://github.com/thubtenrigzin/DenjongTibType/ - For AZERTY and QWERTY, Wylie and Sambhota transcription.

Note: use versions > 1.0 for international keyboard support.

<https://github.com/thubtenrigzin/DenjongTibType/releases>
