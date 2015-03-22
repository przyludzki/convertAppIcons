convertAppios/Icons
===============

convert iOS-App ios/Icons and Android-App ios/Icons from 1024x1024 png.

input:<br>
　1024x1024 png file.<br>

output:<br>
　iOS-App ios/Icons.<br>
　Android-App ios/Icons.<br>	
  WindowsPhone-App ios/Icons.<br>

requirements:<br>
　ruby.<br>
　ImageMagic.<br>

## Usage

```
Usage: convertAppios/Icons [options]
    -i input png-file. [1024x1024]
    -o output directory.

command example:
$ ./convertAppios/Icons -i sample_icon.png -o out

converted images:
##iOS
ios/Icon-29.png          : 29x29
ios/Icon-29@2x.png       : 58x58
ios/Icon-29@3x.png       : 87x87
ios/Icon-40.png          : 40x40
ios/Icon-40@2x.png       : 80x80
ios/Icon-40@3x.png       : 120x120
ios/Icon-50.png          : 50x50
ios/Icon-50@2x.png       : 100x100
ios/Icon-50@3x.png       : 150x150
ios/Icon-57.png          : 57x57
ios/Icon-57@2x.png       : 114x114
ios/Icon-57@3x.png       : 171x171
ios/Icon-60.png          : 60x60
ios/Icon-60@2x.png       : 120x120
ios/Icon-60@3x.png       : 180x180
ios/Icon-72.png          : 72x72
ios/Icon-72@2x.png       : 144x144
ios/Icon-72@3x.png       : 216x216
ios/Icon-76.png          : 76x76
ios/Icon-76@2x.png       : 152x152
ios/Icon-76@3x.png       : 228
ios/Icon-Small-50.png    : 50x50
ios/Icon-Small-50@2x.png : 100x100
ios/Icon-Small-50@3x.png : 150x150
ios/Icon-Small.png"      : 29x29
ios/Icon-Small@2x.png    : 58x58
ios/Icon-Small@3x.png    : 87x87
ios/Icon.png             : 57x57
ios/Icon@2x.png          : 114x114
ios/Icon@3x.png          : 171x171
ios/Icon-120.png         : 120x120
ios/iTunesArtwork.png    : 512x512
ios/iTunesArtwork@2x.png : 1024x1024
ios/iTunesArtwork@3x.png : 1536x1536

##Android
android/drawable-hdpi/ic_launcher.png    : 72x72
android/drawable-ldpi/ic_launcher.png    : 36x36
android/drawable-mdpi/ic_launcher.png    : 48x48
android/drawable-xhdpi/ic_launcher.png   : 96x96
android/drawable-xxhdpi/ic_launcher.png  : 144x144
android/drawable-xxxhdpi/ic_launcher.png : 192x192
android/playstore-icon.png               : 512x512
android/_128.png 				 : 128x128
android/_144.png 				 : 144x144
android/_16.png 				 : 16x16
android/_192.png 				 : 192x192
android/_24.png 				 : 24x24
android/_32.png 				 : 32x32
android/_36.png 				 : 36x36
android/_48.png 				 : 48x48
android/_64.png 				 : 64x64
android/_72.png 				 : 72x72
android/_96.png 				 : 96x96
android/_512.png 				 : 512x512

#WindowsPhone
windowsphone/_24.png 				 : 24x24
windowsphone/_48.png 				 : 48x48
windowsphone/_110.png 				 : 110x110
windowsphone/_159.png 				 : 159x159
windowsphone/_202.png 				 : 202x202
windowsphone/_336.png 				 : 336x336

````

## Expects
- Platform has ImageMagic `convert` command.
- Input file must be 1024x1024 PNG format.

## License
MIT Lincense.
