# Working with Linux Gnome and Tibetan script

## Tibetan keyboards

By default linux desktops come with a Tibetan keyboard compliant to GB/T 22034-2008, a Chinese norm. This keyboard is also used by Microsoft Windows. See [Tibetan keyboards](tibetan_keyboards.md) for more information.

### Wylie EWTS

```{image} Images/gnome_keyboard.jpg
:align: right
:width: 480
```

To add a Wylie keyboard, installed the packages `ibus` and `ibus-m17n` with the package manager of your distribution. Then either make sure to start the ibus daemon, or simply restart your computer.

Then, when opening gnome `settings`, a three new Tibetan keyboards should be available: select `EWTS (m17n)` (not 'Wylie', which is an old version).

