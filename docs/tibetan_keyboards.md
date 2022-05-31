# Tibetan keyboards

```{warning}
Keyboards are a primary attack vector on computer integrity. Never, ever install keyboards from unvalidated sources, neither on computer nor on mobile.
```

## What's the standard?

Unfortunately there is no single system or standard that's available on all platforms. 

- In June of 2005, the Chinese Institute of Electronic Technology Standardization organized a national expert group to develop the national standard for Tibetan keyboard layout,[^std] described in standard GB/T 22034-2008 (`Tibetan PRC`). It's supported by Linux and Windows, but not by MacOS.[^mackbd]
- Researchers with Western background usually use Wylie, since the keyboard layout directly corresponds to the main Tibetan transliteration method. Wylie implementations are available for Windows, Linux and macOS. An the other hand: Tibetan native speakers almost never use Wylie.
- Additionally, there's a vast number of custom layouts and tools used by different communities and are suitable only for specific operating systems and/or applications.

### Recommendation

- If missing macOS support is not a concern, `Tibetan PRC` might be the most future-proof keyboard system. Linux and Windows support this keyboard without any extra configuration steps required.

- Westerners might want to use Wylie-keyboards, but OS-support seems to be slowly declining over the years, and installation requires extra configuration-steps and/or third-party tools (Windows).

## Overview: Computers and laptops

| Keyboard | Windows | macOS | Linux |
| - | :----: | :----: | :----: |
| Wylie | + + (3rd party) | + (bug ridden) | + + (requires config effort) |
| Tibetan (PRC) | + + | - - | + + |
| Tibetan (qwerty) | - - | + + | - - |
| Monlam | + +[^mondist] | + +[^mondist] | - -|

## Mobile devices

| | Android | iOS |
| - | :----: | :----: |
| Google Gboard | + + | - -[^gboard] |
| iOS | - - | + +[^tibq] |

```{admonition} You know of other or better keyboards?
:class: tip
If you are using different keyboards or have comments to make, [let us know!](https://github.com/DigitalTibetan/DigitalTibetan/issues)
```
## Standard Tibetan keyboard: `Tibetan (PRC)`

```{image} Images/windows_tibetan_keyboard.jpg
:align: right
:width: 400
```

Available on Linux and Windows, `Tibetan (PRC)` stems from some initial efforts to standardize Tibetan keyboards.

```{image} Images/windows_tibetan_keyboard_shift.jpg
:align: right
:width: 400
```

The following article describes the keyboard and it's history well:

- <http://www.yalasoo.com/English/docs/yalasoo_en_MStbKb.html>

Unfortunately, Apple did not adopt this standardization effort.


[^mondist]: Many mirrors of the monlam installers are circulating, some of them infected with compromising viruses.
[^gboard]: While the Gboard app is available for iOS too, the Tibetan keyboard is not included on iOS.
[^tibq]: The iOS Tibetan keyboard mirrors the layout of Apple macOS's `Tibetan QWERTY` keyboard.
[^std]: [National Standard for Tibetan Keyboard Layout](http://www.yalasoo.com/English/docs/yalasoo_en_national_keyboard_standard.html)
[^mackbd]: Request for support suggested with Apple in 2022-05.