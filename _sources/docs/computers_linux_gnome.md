# Linux Gnome and Tibetan script

## Tibetan keyboards

### Tibetan (PRC) 

By default linux desktops come with a Tibetan keyboard compliant to GB/T 22034-2008, a Chinese norm. This keyboard is also used by Microsoft Windows. 

To install, simply search for `Tibetan` when adding the new keyboard.

See [Tibetan keyboards](tibetan_keyboards.md) for more information.

### Wylie EWTS

```{image} Images/gnome_keyboard.jpg
:align: right
:width: 480
```

Gnome already has the `ibus` input method installed by default, which is a considerable advantage over KDE. You might need to install the `ibus-m17n` package, which provides the Wylie keyboard.

Then, when opening gnome `settings`, a three new Tibetan keyboards should be available: select `EWTS (m17n)` (not 'Wylie', which is an old version).

