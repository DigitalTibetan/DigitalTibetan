# Digital Tibetan

Welcome to the Digital Tibetan v3.0

## The new home of Digital Tibetan v3.0

- This site is a collection of information and How-Tos on how to work with digital Tibetan information. For information on how to configure mobiles and computer for Tibetan fonts, [start here](docs/devices_tibetan.md). This site is a new version of the old DigitalTibetan wiki[^ref_old_site], and it is currently still under development.
- Additionally, the plan is to introduce tools for [computational dharma](docs/computational_dharma.ipynb), how modern tools inherited from data science can be used to efficiently create personal working environments that support working with, cross-referencing, and transforming large amounts of natural language data related to Tibetan. 

[^ref_old_site]: [Archive of the old DigitalTibetan v2 site at archive.org](https://web.archive.org/web/20210502044931/http://www.digitaltibetan.org/index.php/Digital_Tibetan).

## News

- 2024-07-24: Provide a version of [Noto Sans Tibetan.ttf](https://github.com/DigitalTibetan/FontRenamer) by internally renaming Google's [Noto Serif Tibetan](https://fonts.google.com/noto/specimen/Noto+Serif+Tibetan). The GUI of some ereaders require fonts of the "Noto Sans" family, and the renamed font allows displaying of Tibetan on these devices. See [Tibetan Fonts](docs/tibetan_fonts.md) for more information.
- 2023-12-11: Recent Kindle firmware updates (verson 5.16.x) support proper display of Tibetan on your Kindle e-reader. Check out the [Amazon Kindle](docs/ebook_reader_kindle.md) Tibetan support page and get some fresh Tibetan ebooks for your Kindle from [Lotsawa House](https://www.lotsawahouse.org)!
- 2023-04-20: An overview on the state of [Artificial intelligence and Tibetan](docs/tibetan_ai.md), [Tibetan OCR](docs/tibetan_ocr.md), and [Tibetan machine translation](docs/tibetan_machine_translation.md).
- 2022-12-08: Python source code for the conversion of ACIP to Unicode is now available at [ACIP to Unicode converter](https://github.com/OpenPecha/pyewts/blob/master/pyewts/ACIP.py). The converter is part of the [OpenPecha](https://github.com/OpenPecha) project. The ACIP documentation (see: [`ticode.pdf`](https://github.com/DigitalTibetan/DigitalTibetan/raw/main/docs/Resources/ticode.pdf)) was almost lost due to digital erosion, but has now been recovered due to the work of Elie Roux.
- 2022-11-13: Digital Tibetan is now on Mastodon at [`@digitaltibetan@social.linux.pizza`](https://social.linux.pizza/@digitaltibetan).
- 2022-10-04: A new conversion tool for PDFs using old Tibetan fonts is being [made available](https://github.com/buda-base/py-tiblegenc) by Elie Roux. Text within PDFs created with non-Unicode Tibetan fonts is difficult to recover, and this tool helps to extract the original Tibetan typing in modern Unicode encoding. Development is ongoing, and the sources are available at [Python Tibetan Legacy Encodings tool](https://github.com/buda-base/py-tiblegenc) at github. More conversion tools can be found at [Tibetan Pre-Unicode](docs/tibetan_pre_unicode.md).
- See the [news archive](docs/news/_news_archive.md) for what was previously news.

(contribute)=
## Contributions, suggestions, ideas and corrections

```{image} Images/quick_edit.jpg
:align: left
:width: 128
```

If topics are missing, or you have suggestions on how to improve the site, please use the github:

- For corrections, small additions or suggestions, please use the [Github issues](https://github.com/DigitalTibetan/DigitalTibetan/issues)
- For larger contributions, [Github pull-requests](https://github.com/DigitalTibetan/DigitalTibetan/pulls) are welcome!

The Github-icon on the top right gives easy access to the source-repository and has a quick-edit option. Each edit will be reviewed, so there is no danger of generating a mess. Documents use the [markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format.

This site is based on a [github repository](https://github.com/DigitalTibetan/DigitalTibetan) that basically consists of simple text-files in markdown. The markdown files are converted into this web site using [Jupyter-Book](https://jupyterbook.org/en/stable/index.html).

## Some random topics

- [Getting started: how to setup your devices for working with Tibetan](docs/devices_tibetan.md)
- [History of Tibetan script](docs/tibetan_script_history.md)
- [The Tibetan calendar](docs/tibetan_calendar.md)
- [On the fragility of digital information](docs/digital_dharma_is_fragile.md)
- [Digital Tibetan Tools](docs/digital_tibetan_tools.md)
