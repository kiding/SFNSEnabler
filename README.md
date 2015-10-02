# SFNSEnabler

![screenshot](https://github.com/kiding/SFNSEnabler/raw/master/screenshot.jpg)

OS X El Capitan has introduced new system fonts, which are some variations of [San Francisco typeface](https://developer.apple.com/fonts/) known as _.SF NS Display_ and _.SF NS Text_. By default, they are "unlisted" in the Font Book, therefore unusable from applications like TextEdit, Pixelmator, etc. _SFNSEnabler_ allows those usage in a limited way.

## Installation

Simply download and install __[SFNSEnabler.otf](https://github.com/kiding/SFNSEnabler/raw/master/SFNSEnabler.otf)__. Now you should be able to choose the fonts from applications. If it's not visible in the application's usual dropdown menu, use the "Show Fonts (⌘T)" menu.

If you don't know how to install a font, see [how](https://support.apple.com/en-us/HT201749). Ignore "Font Validation" by checking "SFNSEnabler.otf" and clicking "Install Checked."

_.SF NS Text_ might not be visible, but you can still select most of them under _.SF NS Display_; G1, G2, G3 and the italics. Some application might behave clunky as the selected font name doesn't appear in the list properly.

## Is this dangerous?

Probably not. SFNSEnabler.otf is a simple blank otf file generated using [FontForge](https://github.com/fontforge/fontforge), with only one metadata "Family Name" colliding with the system fonts. It does not use any of Apple's font codes nor glyphs.

## Credits

Created by [Dongsung Kim](http://kiding.net)
