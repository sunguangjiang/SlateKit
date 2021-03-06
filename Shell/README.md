# SlateKit Shell
Qt5/QML WebKit Browser with a Hamburger Button

![Drawer](https://raw.github.com/penk/SlateKit/master/Shell/screenshot.png)

More information: [http://penkia.blogspot.com/2013/05/slatekit-shell-qt5qml-webkit-browser.html](http://penkia.blogspot.com/2013/05/slatekit-shell-qt5qml-webkit-browser.html?view=classic)
## Features 

- Based on Qt5/QtQuick2, written entirely in QML/JavaScript
- Sliding-Drawer UI with [side-tab support](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/drawer.gif)
- Basic search [suggestion and highlight](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/suggestion.png) via LocalStorage 
- Custom event binding including [Open in New Tab](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/new_tab.gif)
- Custom popover for [select elements](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/popover.png)
- Built-in virtual keyboard for [English](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/keyboard.png) and [Chinese Handwriting](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/handwriting.png) 
- [Reader mode](https://raw.github.com/penk/SlateKit/master/Shell/screenshots/reader.png) based on [readability.js](http://code.google.com/p/arc90labs-readability/source/browse/trunk/js/readability.js)

## Usage

    export QTWEBKIT_INSPECTOR_SERVER=9222
    qmlscene ./qml/Shell.qml

Or compile executable by:

    qmake && make && ./slatekit

## License 
The source codes are, unless otherwise specified, distributed under the terms of the MIT License

Copyright © 2013 Ping-Hsun Chen ([@penk](http://twitter.com/penk)) <[penkia@gmail.com](mailto:penkia@gmail.com)>
[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/fbf22fe6e291e9f9a1c76036c8766f5e "githalytics.com")](http://githalytics.com/penk/SlateKit)
