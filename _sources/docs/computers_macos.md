# Working with macOS and Tibetan script

The Mac comes with Tibetan fonts preinstalled. For more fonts, see [Tibetan fonts](tibetan_fonts.md).

(macos_keyboard)=
## Tibetan keyboard

```{image} Images/macos_keyboard.jpg
:align: right
:width: 480
```
 To activate a Tibetan keyboard, start `System Preferences` and select `Keyboard`, `Input Sources`. Press the `+`-Icon (marked in red in the image) and add the `Tibetan - Wylie` keyboard.

 ```{image} Images/macos_input_source_select.jpg
 :align: left
 :width: 150
 ```

Make sure that `Show Input menu in menu bar` is enabled so that you can easily switch keyboards by clicking the input-menu icon in the menu bar.

Newer Mac hardware keyboards have a globe icon 🌐 that can be used to switch between the Tibetan keyboard and your usual keyboard. 

```{warning}
macOS implementation of Wylie is currently quite broken. The `<shift>`-key to access Sanskrit variants doesn't work currently, and one needs to use `CAPS LOCK` to access those. Additionally, the `=` is used as non-standard stacking-key. So make sure that `CAPS LOCK` is not assigned to other functionality, like switching input methods.
```

```{image} Images/macos_input_sources.jpg
:align: right
:width: 480
```
### Chose a keyboard-switcher hotkey

You can assign an arbitrary hotkey to switch between the keyboards: In `System Preferences`, `Keyboard`, select `Shortcuts` and `Input Sources`. There either enable the suggested shortcut, or click on the proposed shortcut to enter a new key-combination.

## Activating the Tibetan keyboard

You should now be able to either select the current keyboard by hotkey, or by clicking the input-source icon in the menu bar.

## How to type Tibetan Wylie EWTS

```{image} Images/macos_keyboard_viewer.jpg
:align: right
:width: 480
```

Since macOS Wylie input method is Wylie in name-only, it makes sense to activate the `Show Keyboard Viewer` in the input selector menu-bar icon.

The `Caps lock` key makes Sanskrit and special symbols available, while the `=` key supports non-standard stacking.
It might be necessary to experiment a bit with the keyboard viewer active.

Here are the special layouts:

After selecting `caps-lock`:
```{image} Images/macos_keyboard_viewer_caps.jpg
:width: 320
```

after selecting `caps-lock` and `=`:

```{image} Images/macos_keyboard_viewer_caps_=.jpg
:width: 320
```

after selcting `caps-lock`, `=`, and `caps-lock`:
```{image} Images/macos_keyboard_viewer_caps_=_caps.jpg
:width: 320
```
So currently, to type ཌྜྷི, one types `<caps lock> d = d = <caps lock> h i`. Not _quite_ the standard way to do things...

Apple is working on a bug-report...

## Sanskrit diacritics

