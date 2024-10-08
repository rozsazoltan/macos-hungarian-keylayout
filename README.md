## Installation

- Download the `HungarianQwertz.bundle.zip` file.
- Right-click the `HungarianQwertz.bundle.zip` file and select the "Extract" option, or double-click to open it.
- Right-click the `HungarianQwertz.bundle` and select the "Open with..." using `Keyboard Installer` application, or double-click to open it (by default).
- Logout and Login again, or restart your PC.
- In the keyboard settings, you will find the `Hungarian - QWERTZ` keyboard layout in the `Hungarian` folder.

_In case of a new version release of the keylayout, you do not need to remove the already installed keylayout for the update; simply install the new version according to the instructions provided above._

## Why?

### Known macOS issues with default Hungarian keyboard layouts

macOS comes with two Hungarian keyboard layouts by default, neither of which is fully functional:
- Hungarian (the special characters are accessible in completely different ways; <kbd>Í</kbd> and <kbd>0</kbd> are swapped)
- Hungarian QWERTY (the special characters are accessible in completely different ways; <kbd>Z</kbd> and <kbd>Y</kbd> are swapped)

### How created a universal Hungarian keyboard layout

This (Hungarian QWERTZ) layout puts the most important (for programming) characters back to where they usually are on a PC keyboard (as Windows and Linux systems).

- <kbd>0</kbd> is now right left to <kbd>1</kbd> (instead of <kbd>Í</kbd>, which moved to <kbd>Alt</kbd><kbd>J</kbd>)
- On international QWERTZ layouts you can type <kbd>Í</kbd> with the key located between the <kbd>Left Shift</kbd> and the <kbd>Y</kbd>. Use this <kbd>Alt</kbd><kbd>Í</kbd> key with <kbd>Alt</kbd><kbd>Y</kbd> for `<` and `>` symbols, as on Hungarian keyboards.213122
- <kbd>Alt</kbd> is the primary method for symbols:
    - <kbd>Alt</kbd><kbd>Q</kbd> = `\`
    - <kbd>Alt</kbd><kbd>V</kbd> = `@`
    - <kbd>Alt</kbd><kbd>F</kbd> = `[`
    - <kbd>Alt</kbd><kbd>G</kbd> = `]`
    - etc.

In general, everything should be where it belongs on a PC keyboard.

## Known Issues

- On JP keyboards, you can still use <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>0</kbd> to enter <kbd>0</kbd> (since there's a missing key to the left of <kbd>1</kbd>).

## Uninstall

- Navigate to the `~/Library/Keyboard Layouts` folder.
- Find the appropriately named (`HungarianQwertz.bundle`) bundle file and delete it.

## License

You are free to use this software for any purpose. However, it is provided "as is" without any warranties or guarantees. I am not liable for any issues or damages that may arise from its use.
