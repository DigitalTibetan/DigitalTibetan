# Linux KDE and Tibetan script

## Tibetan keyboards

### Tibetan (PRC) 

By default linux desktops come with a Tibetan keyboard compliant to GB/T 22034-2008, a Chinese norm. This keyboard is also used by Microsoft Windows. 

To install, simply search for `Tibetan` when adding the new keyboard.

See [Tibetan keyboards](tibetan_keyboards.md) for more information.

### Wylie EWTS

```{image} Images/kde_ibus_setup_keyboard.jpg
:align: right
:width: 480
```

To add a Wylie keyboard, install the packages `ibus` and `ibus-m17n` with the package manager of your distribution. Then either make sure to start the `ibus` daemon, or simply restart your computer.

Now run `ibus_setup` once to add Tibetan Wylie EWTS keyboard: select `Tibetan EWTS (m17n)` (not 'Wylie', which is an old version).

### Trouble-shooting

If the Tibetan input doesn't appear in some of your applications, make sure that the following environment variables are set (e.g. in `.bashrc`):

```bash
GTK_IM_MODULE=ibus
QT_IM_MODULE=ibus
XMODIFIERS=@im=ibus
```
