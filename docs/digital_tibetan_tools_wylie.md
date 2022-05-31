# Wylie conversion

For introduction how EWTS Wylie works, see [Teaching EWTS](https://www.thlib.org/reference/transliteration/teachingewts.pdf) by Alexandru Anton-Luca. If you want to learn, how to work with Tibetan computer keyboards, this is a useful resource.

```{image} Images/ewts_converter.jpg
:align: right
:width: 280
```
## Online tool

The following tool converts between Wylie EWTS (Extended Wylie) and Tibetan Unicode:

* [Bidirectional online converter between Wylie and Tibetan Unicode](https://www.lotsawahouse.org/Static/tools/ewts.html)

## Programming

### Python

Using Esukhia's [pyewts](https://github.com/OpenPecha-dev/pyewts), install with `pip install pyewts`:

```python
import pyewts
converter=pyewts.pyewts()
print(converter.toUnicode("oM AHhUM:"))
print(converter.toWylie("སེམས་ཉིད་"))
```
Output:
```
ཨོཾ་ཨཱཿཧཱུཾ༔
sems nyid 
```

For an example jupyter notebook, see: [computational dharma](computational_dharma.ipynb)

### Other implementations

- [Original perl implementation](https://www.lotsawahouse.org/Static/Lingua-BO-Wylie-dev.zip) by Roger Espel
- [Java port](https://github.com/buda-base/ewts-converter) maintained by the Buda organization
- [ewts-js Javascript repository](https://github.com/rogerespel/ewts-js) by Roger Espel.

### References

- [ewts-js Javascript repository](https://github.com/rogerespel/ewts-js) by Roger Espel.
- [pyewts Python port](https://github.com/OpenPecha-dev/pyewts) by Esukhia
- [Teaching EWTS](https://www.thlib.org/reference/transliteration/teachingewts.pdf) by Alexandru Anton-Luca
