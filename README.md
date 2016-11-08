# barcodeWebChrome
A Chrome extension designed to be used in conjunction with [barcodeWeb](https://github.com/hschreck/barcodeWeb)

## Setup:
Note: barcodeWeb must be setup *before* using barcodeWebChrome.

1. Download the latest version of the extension from the 'Releases' page
2. Drag the downloaded extension and drag it onto the 'chrome://extensions' page to install.
3. Configure your extension on the options page, point your address to your previously setup barcodeWeb setup.
4. Done!

## Features:

* Uses highlighted text to make a SKU (useful with keyboard commands)
* Has a nifty keyboard shortcut (CTRL+B/CMD+B, configurable)
* Lightweight
* Context Menu service


## Options:
![Options in 'chrome://extensions'](https://github.com/128keaton/barcodeWebChrome/blob/master/repo-assets/options.png?raw=true)

**Address:** e.g. `10.0.0.15/printer/`. Must be directory which contains `printers.php`, along with the rest of the barcodeWeb suite.


## Print Window:

![Print window](https://github.com/128keaton/barcodeWebChrome/blob/master/repo-assets/print-window.png?raw=true)


**SKU:** e.g. `129ASDJ12389FASD`, limited to barcodeWeb's maximum characters (e.g. 19)

**Quantity:**  (default '1'), option to configure another default coming at a later date.

**Printer:** The default is saved in your browser whenever you print. Pulled from `printers.php`.

## Keyboard Shortcuts:

![Keyboarad](https://github.com/128keaton/barcodeWebChrome/blob/master/repo-assets/kb-shortcuts.png?raw=true)

**Activate the extension:** (default "CMD+B" on OS X, "CTRL+B" on Windows and Linux). Activates the extension.


