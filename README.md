# SFNSEnabler

![screenshot](https://github.com/kiding/SFNSEnabler/raw/1/screenshot.jpg)

_OS X El Capitan_ has introduced new system fonts, which are some variations of [San Francisco typeface](https://developer.apple.com/fonts/) known as _.SF NS Display_ and _.SF NS Text_. By default, they are "unlisted" in the Font Book, therefore unusable from applications like TextEdit, Pixelmator, etc. _SFNSEnabler_ allows those usage in a limited way.

## Installation

Simply download and install __[SFNSEnabler.otf](https://github.com/kiding/SFNSEnabler/raw/1/SFNSEnabler.otf)__. Now you should be able to choose the fonts from applications; go to the __"Show Fonts (⌘T)"__ menu, and __search__ for __"SF"__. The font might not be visible until you __search__ for them.

The family name of the fonts varies by the language preference of your system, for example, in Korean you need to search for "시스템 서체." The complete list of the names is following.

* English __.SF NS Display__
* Arabic (Egypt) __خط النظام__
* Catalan __Tipus de lletra del sistema__
* Chinese (PRC) __系统字体__
* Chinese (Taiwan) __系統字體__
* Croatian __Font sustava__
* Czech __Systémové písmo__
* Danish __Systemskrift__
* Dutch __Systeemlettertype__
* Finnish __Järjestelmäfontti__
* French __Police système__
* German __Systemschrift__
* Greek __Γραμματοσειρά συστήματος__
* Hebrew __גופן מערכת__
* Hungarian __Rendszerbetűtípus__
* Indonesian __Fon Sistem__
* Italian __Font di sistema__
* Japanese __システムフォント__
* Korean __시스템 서체__
* Malay __Fon Sistem__
* Polish __Czcionka systemowa__
* Portuguese (Brasil) __Tipo de letra do sistema__
* Portuguese (Portugal) __Fonte do Sistema__
* Romanian __Font de sistem__
* Russian __Системный шрифт__
* Slovak __Systémové písmo__
* Spanish (Modern) __Tipo de letra del sistema__
* Swedish (Sweden) __Systemtypsnitt__
* Thai __แบบอักษรระบบ__
* Turkish __Sistem Fontu__
* Ukranian __Системний шрифт__
* Vietnamese __Phông chữ Hệ thống__

If you don't know how to install a font, see [how](https://support.apple.com/en-us/HT201749). Ignore "Font Validation" by checking "SFNSEnabler.otf" and clicking "Install Checked."

_.SF NS Text_ fonts are _merged_ with _.SF NS Display_ for some reason, but you can still select most of them under _.SF NS Display_; G1, G2, G3 and the italics do not belong to _.SF NS Display_. I also don't know what Gs are for...

Some application might behave clunky as the selected font name doesn't appear properly in the list.

## Disclaimer

_Use it at your own risk._ But does this harm the system? Probably not. SFNSEnabler.otf is a simple blank otf file generated using [FontForge](https://github.com/fontforge/fontforge), with only one metadata "Family Name" colliding with the system fonts. It does not use any of Apple's font codes nor glyphs.

## Credits

Created by [Dongsung Kim](http://kiding.net)
