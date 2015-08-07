snw-cordova-imagePicker
=======================

```
This is a fork of https://github.com/wymsee/cordova-imagePicker with minor fixes.

Fixes:
    - Adaptive layout that support iPhone 6, 6+ and possibly future model
    - Cosmetic changes reflecting iOS 8
    - Android short fileanme crash
```

You should read the document from the upstream about how to use the plugin.

## Installing the plugin

The plugin conforms to the Cordova plugin specification, it can be installed
using the Cordova / Phonegap command line interface.

    phonegap plugin add https://github.com/pawee/snw-cordova-imagePicker.git

    cordova plugin add https://github.com/pawee/snw-cordova-imagePicker.git

## Libraries used

#### ELCImagePicker

For iOS this plugin uses the ELCImagePickerController, with slight modifications for the iOS image picker.  ELCImagePicker uses the MIT License which can be found in the file LICENSE.

https://github.com/B-Sides/ELCImagePickerController

#### MultiImageChooser

For Android this plugin uses MultiImageChooser, with modifications.  MultiImageChooser uses the BSD 2-Clause License which can be found in the file BSD_LICENSE.  Some code inside MultImageChooser is licensed under the Apache license which can be found in the file APACHE_LICENSE.

https://github.com/derosa/MultiImageChooser

#### FakeR

Code(FakeR) was also taken from the phonegap BarCodeScanner plugin.  This code uses the MIT license.

https://github.com/wildabeast/BarcodeScanner

## License

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.