# Editing and creating Tibetan fonts

INCOMPLETE DRAFT

## Unicode Tibetan

### The Unicode code page for Tibetan: `0x0F00 - 0x0FFF`[^uni_tib_ref]

|        | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | A | B | C | D | E | F |
| ------ | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - |
| **U+0F0x** | ༀ | ༁ | ༂| ༃ | ༄ | ༅ | ༆ | ༇ | ༈ | ༉ | ༊ | ་ | ༌$_{\tiny{NB}}$ | ། | ༎ | ༏ |
| **U+0F1x** | ༐ | ༑ | ༒ | ༓ | ༔ | ༕ | ༖ | ༗ | ༘  | ༙ | ༚ | ༛ | ༜ | ༝ | ༞ | ༟ |
| **U+0F2x** | ༠ | ༡ | ༢ | ༣ | ༤ | ༥ | ༦ | ༧ | ༨ | ༩ | ༪ | ༫ | ༬ | ༭ | ༮ | ༯ |
| **U+0F3x** | ༰ | ༱ | ༲ | ༳ | ༴ | ༵ | ༶ | ༷ | ༸ | ༹ | ༺ | ༻ | ༼ | ༽ | ༾ | ༿ |
| **U+0F4x** | ཀ | ཁ | ག | གྷ | ང | ཅ | ཆ | ཇ | 	 | ཉ | ཊ | ཋ | ཌ | ཌྷ | ཎ | ཏ |
| **U+0F5x** | ཐ | ད | དྷ | ན | པ | ཕ | བ | བྷ | མ | ཙ | ཚ | ཛ | ཛྷ | ཝ | ཞ | ཟ |
| **U+0F6x** | འ | ཡ | ར | ལ | ཤ | ཥ | ས | ཧ | ཨ | ཀྵ | ཪ | ཫ | ཬ | |  |  |
| **U+0F7x** |  | 	ཱ | ི | ཱི | ུ | ཱུ | ྲྀ | ཷ | ླྀ | ཹ | ེ | ཻ | ོ | ཽ | ཾ | ཿ |
| **U+0F8x** | ྀ | ཱྀ | ྂ | ྃ | ྄ | ྅ | ྆ | ྇ | ྈ | ྉ | ྊ | ྋ | ྌ | ྍ | ྎ | ྏ |
| **U+0F9x** | ྐ | ྑ | ྒ | ྒྷ | ྔ | ྕ | ྖ | ྗ |  |  ྙ | ྚ | ྛ | ྜ | ྜྷ | ྞ | ྟ |
| **U+0FAx** | ྠ | ྡ | ྡྷ | ྣ | ྤ | ྥ | ྦ | ྦྷ | ྨ | ྩ | ྪ | ྫ | ྫྷ | ྭ | ྮ | ྯ |
| **U+0FBx** | ྰ | ྱ | ྲ | ླ | ྴ | ྵ | ྶ | ྷ | ྸ | ྐྵ | ྺ | ྻ | ྼ  | | 	྾  | 	྿ | 
| **U+0FCx** | ࿀ | ࿁ | ࿂ | ࿃ | ࿄ | ࿅ | ࿆ | ࿇ | ࿈ | ࿉ | ࿊ | ࿋ | ࿌ | 	 | ࿎ | ࿏ |
| **U+0FDx** | ࿐ | ࿑ | ࿒ | ࿓ | ࿔ | ࿕ | ࿖ | ࿗ | ࿘ | ࿙ | ࿚ |  |  |  |  |  |	
| **U+0FEx** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 	
| **U+0FFx** |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 

[^uni_tib_ref]: After [Wikipedia](https://en.wikipedia.org/wiki/Tibetan_(Unicode_block))

Looking at the Unicode table one notices that all Tibetan letters are contained in it, and they are all contained twice, e.g. `ཀ` (at position `U+0F40`) and ` ྐ` (at position `U+0F90`). The second variant is used to construct compounded stacks, e.g. `གྱི`, which is a sequence of Unicode characters `ག`, ` ྱ`, ` ི`, or `U+0F41`,`U+0FB1`,`U+0F72`. The circles simply indicate, if the subsequent glyphs are 'pasted' below (as in ` ྱ`) or above (as in ` ི`).

### Encoding glyphs

A Tibetan font contains two major areas:

```{image} Images/FontForge.jpg
:align: right
:width: 480
```

* First, it contains all the glyphs defined by the Unicode Tibetan table as shown in the table above. An example for such a standard entry would be `ག`.
* Secondly, it needs to contain a _ligature table_, containing the glyphs and an OpenType descriptions for each glyph for _any possible Tibetan stack_. So there needs to be a glyph for `གི`, `གྱ`, `གྱི` and so on. Every single possible stack needs to be designed and included into the font. Due to the multiple different use-cases of Tibetan for Sanskrit transliteration (mantras, e.g. `ཧྲཱིཿ`), Chinese transliteration and Dzongkha shorthand contractions[^dzongkha_shorthand_examples] (e.g. `དཀོོག་` for `དཀོན་མཆོག་`), the number of possible stacks is basically unlimited.

[^dzongkha_shorthand_examples]: For examples, see [here](https://www.babelstone.co.uk/Tibetan/Contractions.html)

## Example: Jomolhari and FontForge

To learn more about the encoding and creation of Tibetan fonts, is best to look at an example. Download:

- [Jomolhari font](https://fonts.google.com/specimen/Jomolhari#type-tester)
- [FontForge](https://fontforge.org/en-US/), a powerful free and open font editor that can be used to extend existing Tibetan fonts or create new ones. It available for Linux, macOS and Windows.

Now start FontForge and open `Jomolhari-Regular.ttf`. Once Jomolhari is loaded, select `Encoding / Compact (hide unused glyphs)` to make navigation easier.

```{image} Images/FontForgeKa.jpg
:align: right
:width: 180
```

Then `View / Label glyph by / Unicode`. That will display the numeric code of each glyph above it's graphical representation. This code is later required in order to construct new Tibetan stacks or ligatures.

Double-click `ཀ` at `0F40`, and a vector-graphics editor for the `ཀ`-glyph will open. Each glyph in the Unicode table for Tibetan is defined by a vector outline.

It becomes a bit more complicated for compound stacks, so called _ligatures_. We will again look at the example of `གྱི`.

```{image} Images/FontForgeGya.jpg
:align: right
:width: 240
```

First, scroll down to position `f360`. It contains the glyph `གྱ`, the intermediate between `ག` and `གྱི`. In the outline editor window of `གྱ`, select `Element / Glyph info`, and `Ligatures`. This describes the OpenType rules, how the glyph `གྱ` is composed of the two unicode characters `ག` (at `U+0F41`) and ` ྱ` (at `U+0FB1`): the ligature is a `blws` 'Below Base Substitution' which means a `གྱ` is composed of a `ག` with subjoined ` ྱ`.





<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
# OUTDATED:

Indic scripts and Tibetan create stacks by using the OpenType feature 'Below base substitution ligatures' (`blws`). The font contains the image of a Tibetan stack ('a glyph') together with a definition which letters do compose this stack. A Unicode font would for example contain an image of the glyph `rgyu`, རྒྱུ together with a ligature definition how this glyph is composed of single letters. A very good description how to encode Unicode stacks can be found at [THLib](https://www.thlib.org/tools/scripts/wiki/Encoding%20model%20of%20the%20Tibetan%20script%20in%20the%20UCS.html).



## Using FontForge to create Tibetan fonts



### Editing Tibetan fonts and creating Sanskrit stacks for existing fonts

To update an existing Tibetan font, load the font into FontForge and create a new empty font. Use the THDL Tibetan Machine Uni font as an example if you in doubt about settings. Name your font using "Element / font info".

Standard range Tibetan 0x0f00 - 0x0fff
Get a definition of the Tibetan Unicode font range (characters 0x0F00 to 0x0FFF) and copy the standard characters from your existing font into the standard range. You can simply load Tibetan Machine Uni into FontForge and take this as reference to see which character is expected where in the range of 0x0f00 to 0x0fff. Note that only a few stacks are within the standard range. Stacks are handled differently.

`FontForgeLigatureCode.jpg`

Since Unicode knows that Tibetan fonts are aligned at the upper border of a character, you need to move the characters upwards. Select them and your Transform/move to adjust the zero line. Again it is a good idea to use Tibetan Machine Uni as an example.

### Tibetan Stacks

Tibetan Stacks are implemented as ligatures. The Unicode sequence for rgyu is defined as a ligature-glyph that represents the corresponding stack. This way the font itself has all the knowledge how to represent those stacks. In the example of rgyu, the Unicode encoding is: uni0F62 (ra from upper half of unicode area 0F00-0FFFF), uni0F92 (ga and all following letters from lower half, since they are subjoined letters to ra), uni0FB1 (yata), uni0F74 (vowel marker for u). Note that Unicode does not know about root letters in Tibetan alphabet. The encoding always marks the uppermost letter (not including vowel signs, nadas and so on) by encoding it from the Unicode range of 0F40-0F79 and all lower letters of a stack ('subjoined') are encoded from range 0F90-0FBC. See THDL for a very good description on how to compose Tibetan Unicode glyphs.

To create a stack, in FontForge create a new encoding slot ('Encoding / Add Encoding Slot') and copy the graphical representation of a stack into that new slot. Note that this slot does not have a standard Unicode ID. At this point there would be no way for any computer program to actually use the stack. In order to make the stack known, we need to define a ligature: Select a stack and select 'Element / Glyph Info'. Now select 'OT Glyph class' = Base Lig. Then select ligatures on the left and create a 'New' ligature. You need to enter the Unicode Values of the stack components: the first letter of a stack is from the upper half of the Unicode range, all following ('subjoined') letters are from the second range. See THDL for detailed explanation. Select as Tag: 'Below base substitution' blws and select 'Ignore combining marks'.

To create a Mac OS 10.4.8 compatible font, you would either only or additionally create a rlig ligature entry. Fontforge supports more than one ligature entry per glyph. To make the font Linux compatible, you would additionally create a CCMP ligature with identical information.

FontForge also has a useful function to replace all BLWS tags by RLIG tags. (See FontForge 'Typographic features'). This can be used to easily convert fonts that were created for only one of the platforms.

At this point you should have a font that can be used for a first test:

Save your work in FontForge, then select 'File / Generate Font' and generate a TrueType or OpenType font (both seem to work for Windows). Create 'OpenType' for Mac. Drag the font into control panel / fonts and launch a Unicode aware application (e.g. notepad, OpenOffice, Microsoft Word) to test your new font. Use TextEdit for Mac OS-X 10.4.8 and above.

## Material:

https://fontforge.org/en-US/downloads/
https://github.com/fontforge/fontforge

https://docs.microsoft.com/en-us/typography/script-development/tibetan
