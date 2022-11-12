# Conversion of old Tibetan texts

## Offline conversion

### Conversion of old Tibetan PDFs

The github project [Python Tibetan Legacy Encodings tool](https://github.com/buda-base/py-tiblegenc) by Elie Roux provides a python-based toolset to convert old PDFs that were created with old (pre-Unicode) Tibetan fonts. 

You'll find an email address on the github project page that offers support with the conversion!

Supported formats are:

- Tibetisch dBu-can
- DBu-can
- Youtsoweb (TCRC)
- Youtso (TCRC)
- Bod-Yig (TCRC)
- Ededris
- Dedris
- Drutsa
- Khamdris
- Sama / Esama
- LTibetan, LTibetanExtension and LMantra
- TibetanMachine
- TibetanMachineWeb
- TibetanMachineSkt
- TibetanChogyal (PKTC)
- TibetanClassic (PKTC)
- DzongkhaCalligraphic (PKTC)
- TB-Youtso, TB-TTYoutso, TB2-Youtso, TB2-TTYoutso (LTWA)
- Monlam ouchan and Monlam yigchong

### UTFC converter

-   The trace foundation has supported the development of a Tibetan text converter [Yalasoo UTFC](http://www.yalasoo.com/English/docs/yalasoo_en_utfc.html):

 | encodings                  | txt | unicode txt | rtf | html |
 | -------------------------- | --- | ----------- | --- | ---- |
 | ACIP Transliteration       | yes | yes         | yes | yes  |
 | ALA-LC Transliteration     | yes | yes         | yes | yes  |
 | Bandrida                   | yes | no          | yes | yes  |
 | Beida Founder              | yes | no          | no  | no   |
 | Huanguang                  | yes | no          | no  | no   |
 | LTibetan                   | no  | no          | yes | yes  |
 | National Standard Extended | no  | yes         | yes | yes  |
 | Sambhota 1.0 (Sama)        | no  | no          | yes | yes  |
 | Sambhota 2.0 (Dedris)      | no  | no          | yes | yes  |
 | TCRC Bod-Yig               | no  | no          | yes | yes  |
 | THDL Wylie                 | yes | yes         | yes | yes  |
 | Tibetan Machine            | no  | no          | yes | yes  |
 | Tibetan Machine Web        | no  | no          | yes | yes  |
 | Tongyuan                   | yes | no          | yes | yes  |
 | Unicode                    | no  | yes         | yes | yes  |
 | Wylie Transliteration      | yes | yes         | yes | yes  |
 

### Attu

The makers of [PechaMaker](http://www.pechamaker.com/) have developed a Windows program that converts RTF documents that use a large number of legacy Tibetan fonts into Unicode: [Attu](http://www.pechamaker.com/attu/).

Attu currently supports the conversion of the following legacy fonts into Unicode:[^ref_attu]

- Monlam: Monlam ouchan 1, Monlam ouchan 2, Monlam ouchan 3, Monlam ouchan 4, Monlam yigchong
- Nitartha International (Sambhota): Dedris, Drutsa, Ededris, Khamdris, Sama
- Tibetan Computer Company (TCC): TibetanMachine, TibetanChogyal, TibetanClassic, TibetanCalligraphic, DzongkhaCalligraphic
- Tibetan Computing Resource Center (TCRC): TCRC Bod-Yig, TCRC Youtso, TCRC Youtsoweb
- Tibetan Library of Works and Arts (TLWA): TB-Youtso, TB-TTYoutso, TB2-Youtso, TB2-TTYoutso
- Others: LTibetan, LTibetanExtension, LMantra

See the [Attu website](http://www.pechamaker.com/attu/) for more information.

While Attu is a Windows program, is does run on Mac and Linux with [Wine](http://www.winehq.org/).

### UDP

#### Tibetan/Dzongkha Font Based Formats[^ref_udp]

A very useful conversion program for legacy Tibetan text formats is [UDP](http://udp.leighb.com/). UDP converts the following legacy Tibetan text formats into Tibetan Unicode:

- TibetanMachine
- TibetanMachineWeb
- Tibetan Modern A
- Robillard (Ltibetan, etc)
- Sambhota including Dedris, Eedris, Esama/b/c, Sama/b/c, Samw
- TIBETBT
- fonts derived from the "P.R.C. National Standard for Tibetan (Extension A)" (aka "Set A"). For a documentation see Chris Fynn's website: [Tibetan Extension A](https://sites.google.com/view/chrisfynn/home/tibetanscriptfonts/standardization/precomposedtibetan-parta). Chris Fynn's Jomolhari supports this standard.
- TCRC Bod-Yig, TCRC Youtsoweb, TCRC Youtso
- All Tibetan Unicode fonts (of course).

Checkout [Pre-Unicode font list](pre_unicode_font_list) for download sources for most of those fonts.

#### How to use UDP

##### First time configuration

1.  Get a copy of UDP from [UDP website](http://udp.leighb.com/download.htm) and install the application. UDP can be installed on computers running Windows or on computers running Linux and [Wine](http://www.winehq.org/).
2.  Start UDP and select `Options/Font...` Select `Unicode` and chose a Unicode Tibetan font.
3.  Select `Options/Advanced...` and select `Document are saved by default in: Unicode RTF`.

Now every document you will load into UDP will be displayed using a Unicode font and will be saved by default as RTF Unicode. RTF Unicode files can be directly edited using OpenOffice or Microsoft word.

##### Converting files

**Note:** _This conversion procedures work best with Windows, but it is also possible to run UDP using Wine for Linux (see below)._

**TibetDoc documents:**

1.  No conversion needed, continue with: _Steps common to TibetDoc and Word documents_

**Word documents**

1. **Export as RTF:** Save the document containing legacy Tibetan fonts as RTF document.
2. **Simplify the RTF encoding:** Many word processors (like Microsoft Word) create RTF files whose encoding is too complex for UDP to understand and that might cause UDP to crash. It is possible to simplify the RTF encoding by loading the RTF file with `wordpad` (comes with Windows) and directly saving the file in wordpad again. Wordpad writes the file in a format that is easier to process for UDP. Steps: (1) Load RTF file created in step 1 with `wordpad`. (2) Save it without changes in `wordpad`.

**Steps common to TibetDoc and Word documents**

1. **Load into UDP:** Load the TibetDoc or RTF file that has been saved in steps above into UDP
2. **Create a Tibetan Unicode RTF file:** In UDP, chose `File/Save as...` and select "Rich text Unicode" as output format.
3. **Done:** Use any Unicode application (e.g. LibreOffice) to work with the resulting file.

##### Using UDP in Linux or OS-X with Wine

UDP can be installed in Linux if [Wine](http://www.winehq.org/) is installed. Simply start the installation program for UDP which can be downloaded from the [UDP website](http://udp.leighb.com/download.htm).

Mac OS-X users need to install wine first, using for example [homebrew](https://brew.sh/).

## Converting between Wylie and Tibetan Unicode

See [Digital Tibetan tools - Wylie](digital_tibetan_tools_wylie.md)

## Converting Tibetan Unicode into phonetics

See [Digital Tibetan tools - phonetics](digital_tibetan_tools_pronunciation.md)

## Other converters

THDL offers a table with several Converters & Reverters For Tibetan: [Tabular Survey Of Converters & Reverters For Tibetan](http://www.thlib.org/tools/scripts/wiki/Tabular%20Survey%20Of%20Converters%20%7Camp%7C%20Reverters%20For%20Tibetan.html)

## Resources

### ACIP

- A backup of the _ACIP Tibetan Input Code Standards as of July 1998_ ([`ticode.pdf`](https://github.com/DigitalTibetan/DigitalTibetan/raw/main/docs/Resources/ticode.pdf)) can be downloaded [here](https://github.com/DigitalTibetan/DigitalTibetan/raw/main/docs/Resources/ticode.pdf).[^acipbck]


[^ref_attu]: List is taken from [Attu's website](http://www.pechamaker.com/attu/)
[^ref_udp]: Table taken from [UDP website](http://udp.leighb.com/convert.htm)
[^acipbck]: Retrieved from <https://web.archive.org/web/20080828031427/http://www.asianclassics.org/download/tibetancode/ticode.pdf> on 2022-11-12.