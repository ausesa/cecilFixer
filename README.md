#cecilFixer

Fixes the CECIL to remove annoying popups.

Compatibile with Chrome, Safari and Firefox (see below).

If this breaks patches are welcome.

##Safari 

To build for Safari simply run safariBuild.sh then open Safari and navigate to Develop > Show Extension Builder menu, click + > Add Extension... and select cecilFixer/cecilFixer.safariextension, [sign it with a Safari developer certificate] (https://developer.apple.com/library/safari/documentation/Tools/Conceptual/SafariExtensionGuide/ExtensionsOverview/ExtensionsOverview.html#//apple_ref/doc/uid/TP40009977-CH15-SW26) and then click build package.

##Firefox

To build for Firefox run firefoxBuild.sh and follow [Mozilla's guide](https://developer.mozilla.org/en-US/Add-ons/SDK) for packaging an extension.

##Info
Author: [Scott Goodhew](https://github.com/sgoo)

Maintainer: [Saren Currie](https://github.com/SarenCurrie)

Contributors: [Thomas Paulin](https://github.com/thomaspaulin)
