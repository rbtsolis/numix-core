# Numix Core
This repository powers the generation of the all the Numix app icon themes accross all platforms. This new method is designed to make keeping themes on different platforms on feature parity easier as well as making it as simple as possible to add support for new platforms. Licensed under the GPL-3.0+


## Artwork

### Icon Requests
Please report icon requests in this repo, providing all the details required. For normal applications follow [this video tutorial](https://plus.google.com/+NumixprojectOrg/posts/DkRmhFZuWez), for Steam games follow [this one](https://www.youtube.com/watch?v=BuUy4CzCoXc) and for Chrome apps just post a link to the webstore page. When filing your request please be respectful, patient, and remember that development is done solely on the back of donations.

### Hardcoded Icons
To deal with hardcoded application icons Numix uses the [hardcode-fixer](https://github.com/Foggalong/hardcode-fixer) script. A list of the applications supported by the script can be found [here](https://github.com/Foggalong/hardcode-fixer/wiki/App-Support).


## Script

### Dependencies
The script needs Python 3.x to run. The exporting-to-PNG part of the script currently uses [Cairo](https://cairographics.org/) or [Inkscape](https://inkscape.org/). The OSX packaging needs [libicns](http://icns.sourceforge.net/) for the `png2icns` command.

### How To Use
1. Download the repo
2. Run `gen.py --theme {square,circle} --platform {linux,osx,android}`
3. Get your generated package
