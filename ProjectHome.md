# GIMP Extensions #
<strong><font color='red'>Please donate to support this project.</font></strong><br />
[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EFJPHHL3EC5WU)<br />

<strong><a href='http://sourceforge.net/projects/gimpextensions/files/GIMP_2.8/GIMP_Extensions_v2.8_latest.exe/download'>Download</a></strong>

## Contents ##
  * [Overview](#Overview.md)
  * [Features](#Features.md)
  * [Included Extensions](#Included_Extensions.md)
  * [Changes](#Changes.md)
  * [Extensions Sources](#Extensions_Sources.md)


---


## Overview ##
A Windows installer with a collection of extensions for GIMP that provides the ability to choose which Plug-ins, Scripts, Brushes, etc, that you want to install.

<p>Components selection page:</p>
<img src='http://gimp-extensions.googlecode.com/files/Screenshot_Components.png' alt='Screenshot' />

The installer will overwrite any extension selected that you may have already installed.

GIMP Extensions is not the author or maintainer of any of the extensions included in this package, they are mainly from [GIMP Plugin Registry](http://registry.gimp.org/). For details refer to the title [Extensions Sources](#Extensions_Sources.md) bellow.

This project is also hosted at:
  * [GIMP Plugin Registry](http://registry.gimp.org/node/27656)
  * [SourceForge](http://sourceforge.net/projects/gimpextensions/)
  * [Softpedia](http://www.softpedia.com/get/Multimedia/Graphic/Graphic-Plugins/GIMP-Extensions.shtml)
  * [CNET Download.com](http://download.cnet.com/gimp-extensions/3000-2192_4-75843801.html)



You can download GIMP for Windows from http://www.gimp.org/


---


## Features ##
  * 32-bit and 64-bit support
  * Components selection page
  * Uninstaller (via Control Panel)


---


## Included Extensions ##
**File Types Support**
  * APNG
  * Direct Draw Surface (DDS)
  * JPEG XR
  * pyexiv2
  * WebP Import/Export

**Gimp Animation Package (GAP)**
  * GAP
  * Extra Animation Scripts

**Gimp Paint Studio**
  * Brushes
  * Dynamics
  * Gradients
  * Palettes
  * Patterns
  * Splashes
  * tool-presets

**Plug-ins**
  * Adaptive Contrast Enhancement
  * AUMASK (Advanced Unsharp Mask)
  * BIMP. Batch Image Manipulation Plugin
  * btn4ws
  * Cartoonizer
  * CloneLayer Tool
  * Contact Sheet
  * Dynamic Range Transformer
  * EZ Perspective
  * Fix-CA
  * Focus Blur
  * GIMP Mask
  * G'MIC : GREYC's Magic Image Converter
  * IGLO - Images Grid LayOut
  * Image Registration
  * Indexprint
  * Layer Effects
  * Liquid Rescale
  * MathMap
  * Normalmap
  * PAL & VHS
  * Resynthesizer
  * Retro Computing
  * Save for Web
  * Separate+
  * ShellOut
  * Wavelet decompose
  * Wavelet denoise
  * Wavelet sharpen

**Scripts**
  * AnimStack
  * Auto rotate with a vector
  * Backup Working
  * BgMask
  * Black-and-White Film
  * diana-holga2
  * Egger Scripts
  * El Samuko
  * Fake HDR Effect
  * FIL
  * GIMP FX Foundry
  * gimphelp.org
  * Midnight Sepia
  * Shadows&Highlight
  * Split Studio 3
  * Traditional Orton
  * Warming and Cooling Filters


---

**[Back to Top](#GIMP_Extensions.md)**
## Changes ##
**Version 2.8.20150403**                (2015-04-03)

  * Updated Plug-in BIMP to version 1.13
  * Updated Plug-in G'MIC to version 1.6.1.0
  * Updated El Samuko GIMP scripts (Feb 3, 2015)


**Version 2.8.20141126**                (2014-11-26)

  * Updated Plug-in G'MIC to version 1.6.0.2
    * This version fixes libstdc++-6.dll issue with GIMP 2.8.14


**Version 2.8.20140902**                (2014-09-02)

  * Updated Plug-in BIMP to version 1.11
  * Updated Plug-in G'MIC to version 1.6.0.0
    * G'MIC is now installed in GIMP installation dir again, and both 32 and 64bit are included, since I was unable to find any issues any more
  * Updated Scripts package from gimphelp.org to 41st Release (02/20/2014)


**Version 2.8.20140204**                (2014-02-04)

  * Updated Plug-in BIMP to version 1.7
  * Updated Plug-in G'MIC to version 1.5.8.2
  * Updated Plug-in Direct Draw Surface (DDS)  to version 3.0.1


**Version 2.8.20131021**                (2013-10-21)

  * Updated Plug-in G'MIC to version 1.5.7.1
    * G'MIC is now installed in the user profile because the included version of libstdc++-6.dll was creating errors with other plug-ins (web-page, help-browser, file-pdf-load) during GIMP 2.8.6 start-up when installed to GIMP installation dir
    * Fixed issue caused by changing G'MIC installation to user profile: libfftw3-3.dll from MathMap replaced with the one from G'MIC because it was causing error in G'MIC during GIMP start-up. It seams MathMap works OK with libfftw3-3.dll from G'MIC. Because of this is now used only the 32bit version of G'MIC, even on 64bit systems
  * Added Script B&W Film Channels version 0.1 (Color/B&W Film Channels)
  * Updated Plug-in Indexprint to version 3.34
  * Updated Plug-in BIMP to version 1.6
  * Updated Script BgMask to version 0.3
  * Updated Script AnimStack to version 0.61
  * Updated El Samuko GIMP scripts to v24 (Aug 30, 2013)
  * Fix: Removed script jeschke-mats-and-frames.scm from FX Foundry because an updated version already exists (FU\_edges\_mats-and-frames.scm) in gimphelp.org package and it was causing conflict with it
  * Fixed problem related with Separate+ plug-in causing the error message "libtiff3.dll is missing" during GIMP start-up. Because of this is now used only the 32bit version of Separate+, even on 64bit systems


**Version 2.8.20130215**                (2013-02-15)

  * Added Script Split Studio 3 version 3.0r5 (Filters/RSS/Split Studio 3)
  * Added Script Up Down Curve to El Samuko group (Image/Up Down Analysis)
  * Fixed the Script Smart Separate Sharpen that was preventing it from being loaded (Filters/Eg/Sharpen (Smart Separate Redux))


**Version 2.8.20130201**                (2013-02-01)

  * Updated Plug-in BIMP to version 1.0
  * Plug-in G'MIC not updated to version 1.5.4.0 because many filters disappeared, and some crashes occurred in Windows XP 32-bit
  * Made improvements in the installer


**Version 2.8.20130115**                (2013-01-15)

  * Added Gimp Animation Package (GAP) version 2.6.0 32-bit and 64-bit
  * Added Plug-in APNG version 1.0 32-bit and 64-bit
  * Added Plug-in Adaptive Contrast Enhancement version 0.6.7 32-bit and 64-bit
  * Added Script AnimStack version 0.5
  * Added Script BgMask version 0.21
  * Updated Plug-in G'MIC to version 1.5.3.0
  * Updated Plug-in Indexprint to version 3.33
  * Made improvements in the installer


**Version 2.8.20130102**                (2013-01-02)

  * Added Plug-in Indexprint version 3.31 (to current user only)
  * Added pyexiv2 for manipulation of EXIF, IPTC and XMP image metadata used in Indexprint
  * Added Plug-in JPEG XR for file type support
  * Made some improvements in the installer
    * Rearrangement of components selection
    * Added/Updated components descriptions


**Version 2.8.20121208**                (2012-12-08)

  * Added Plug-in WebP Import/Export
  * Updated Plug-in G'MIC to version 1.5.2.4
  * Updated Plug-in Cartoonizer to version 0.8.0
  * Made some improvements in the installer (Added/Updated components descriptions)


**Version 2.8.20121201**                (2012-12-01)

  * Added Plug-in ShellOut
  * Added Plug-in Layer Effects
  * Added Plug-in Wavelet sharpen
  * Added Script Fake HDR Effect
  * Fix: Added missing components to Resynthesizer Plug-in and added 64-bit version
  * Replaced Save for Web Plug-in with the one from http://www.partha.com/ resulting in a greatly increased performance


**Version 2.8.20121123**                (2012-11-23)

  * Added Plug-in CloneLayer Tool version 0.2b
  * Added Script IGLO - Images Grid LayOut
  * Added source code to installer (Installdir\docs)
  * Updated Plug-in G'MIC to version 1.5.2.3
  * Updated Plug-in BIMP to version 0.9


**Version 2.8.20121119**                (2012-11-19)

  * Added Gimp Paint Studio v2.0 (A collection of brushes and accompanying tool presets)
  * Fix: Added 2 missing Egger scripts
    * Add Film Grain
    * DRI (Dynamic Range Extension)
  * Fix: Removed old Egger scripts from GIMP FX Foundry pack because they were preventing some of the updated ones from appearing in the Eg list
  * Change: Installer will now overwrite extensions you may already have installed


**Version 2.8.20121112**                (2012-11-12)

  * Updated Plug-in G'MIC to version 1.5.2.2
  * Updated Plug-in Cartoonizer to version 0.7.0
  * Made some improvements in the installer


**Version 2.8.20121107**                (2012-11-07)

  * Added Plug-in PAL & VHS
  * Added Plug-in Retro Computing v0.0.5
  * Added Plug-in Direct Draw Surface (DDS) v2.2.1 32-bit and 64-bit
  * Added Plug-in Cartoonizer v0.6.1 32-bit and 64-bit


**Version 2.8.20121104**                (2012-11-04)

  * Added README file to the installation directory
  * Added license page to the installer and license file to installation directory
  * Added Plug-in AUMASK (Advanced Unsharp Mask) v0.9.0 32-bit and 64-bit
  * Added Plug-in Resynthesizer
  * Added Script Backup Working
  * Added Plug-in Image Registration v0.5.5 32-bit and 64-bit
  * Added Plug-in Dynamic Range Transformer
  * Added Plug-in Save for Web
  * Added missing BIMP translations
  * Added missing Liquid Rescale batch script
  * Made some improvements in the installer


**Version 2.8.20121030**                (2012-10-30)

  * Added Plug-in Fix-CA v3.0.2 32-bit and 64-bit
  * Added Plug-in GIMP Mask 64-bit
  * Updated Plug-in Normalmap to version 1.2.3 32-bit and 64-bit
  * Updated Plug-in G'MIC to version 1.5.2.1 and added 64-bit version
  * Made some improvements in the installer


**Version 2.8.20121027**                (2012-10-27)

  * Added Plug-in MathMap 1.3.5. (I was unable to make it work in GIMP installation directory, so it will only be availlable in the current user account).


---

**[Back to Top](#GIMP_Extensions.md)**
## Extensions Sources ##

>>>>>>>>>>>> File Types Support <<<<<<<<<<<<

> APNG
> http://sourceforge.net/projects/gimp-apng/
> http://samjcreations.blogspot.pt/2011/12/liste-des-greffons-compiles-pour-gimp.html (64-bit)
> http://registry.gimp.org/node/24394

> Direct Draw Surface (DDS)
> http://code.google.com/p/gimp-dds/

> JPEG XR
> http://registry.gimp.org/node/25508

> pyexiv2
> http://tilloy.net/dev/pyexiv2/overview.html

> WebP Import/Export
> http://registry.gimp.org/node/25874

>>>>>>>>>>>> Gimp Animation Package (GAP) <<<<<<<<<<<<

> http://photocomix-resources.deviantart.com/art/GAP-2-6-for-Gimp-2-6-Windows-135464357
> http://samjcreations.blogspot.pt/2011/12/liste-des-greffons-compiles-pour-gimp.html

>>>>>>>>>>>> Gimp Paint Studio <<<<<<<<<<<<

> http://code.google.com/p/gps-gimp-paint-studio/

>>>>>>>>>>>> PLUG-INS <<<<<<<<<<<<

> Gimp Plugins installers for Win32
> http://registry.gimp.org/node/24520

> Adaptive Contrast Enhancement
> http://samjcreations.blogspot.pt/2011/12/liste-des-greffons-compiles-pour-gimp.html
> http://www.registry.gimp.org/node/20

> AUMASK (Advanced Unsharp Mask)
> http://registry.gimp.org/node/25326

> BIMP. Batch Image Manipulation Plugin.
> http://www.alessandrofrancesconi.it/projects/bimp/
> http://registry.gimp.org/node/26259

> btn4ws
> http://trac.dittberner.info/btn4ws/browser
> http://registry.gimp.org/node/22

> Cartoonizer
> http://code.google.com/p/cartooner-color-reducer/downloads/list

> CloneLayer Tool
> http://registry.gimp.org/node/25422

> Contact Sheet
> http://www.sullockenzlin.demon.nl/Gimp.html
> http://registry.gimp.org/node/120

> Dynamic Range Transformer
> http://registry.gimp.org/node/24520

> EZ Perspective
> http://registry.gimp.org/node/24537
> http://registry.gimp.org/files/ez-perspective.py.zip

> Fix-CA
> http://registry.gimp.org/node/24520
> http://registry.gimp.org/node/3726 (64-bit)

> Focus Blur
> http://registry.gimp.org/node/1444

> GIMP Mask
> http://registry.gimp.org/node/24496

> G'MIC : GREYC's Magic Image Converter
> http://gmic.sourceforge.net/
> http://registry.gimp.org/comment/15736

> Image Registration
> http://sourceforge.net/projects/gimp-image-reg/
> http://registry.gimp.org/node/24248 (64-bit)

> Indexprint
> http://www.sullockenzlin.demon.nl/Gimp.html

> Layer Effects
> http://registry.gimp.org/node/186

> Liquid Rescale GIMP plugin
> http://liquidrescale.wikidot.com/en:download-page

> MathMap
> http://registry.gimp.org/node/22298
> http://www.complang.tuwien.ac.at/schani/mathmap/
> https://sourceforge.net/projects/gimp-packagers/files/

> normalmap
> http://code.google.com/p/gimp-normalmap/
> http://registry.gimp.org/node/69

> PAL & VHS
> http://code.google.com/p/newoldtv/

> Resynthesizer
> http://registry.gimp.org/node/25219
> http://www.partha.com/

> Retro Computing
> http://code.google.com/p/newoldtv/

> Save for Web
> http://registry.gimp.org/node/33
> http://www.partha.com/

> Separate+
> http://cue.yellowmagic.info/softwares/separate-plus/index.html
> http://registry.gimp.org/node/471
> ICC profile downloads for bundlers (Windows)
> http://www.adobe.com/support/downloads/thankyou.jsp?ftpID=4077&fileID=3791

> ShellOut
> http://registry.gimp.org/node/24977

> Wavelet decompose
> http://registry.gimp.org/node/11742
> http://www.partha.com/

> Wavelet denoise
> http://registry.gimp.org/node/4235
> http://www.partha.com/

> Wavelet sharpen
> http://registry.gimp.org/node/9836
> http://www.partha.com/

>>>>>>>>>>>> SCRIPTS <<<<<<<<<<<<

>>>>>>> Egger Scripts <<<<<<<<
> http://registry.gimp.org/node/26250

> Add Film Grain
> http://registry.gimp.org/node/101
> http://registry.gimp.org/files/Eg-AddFilmGrain.scm

> Black&White
> http://registry.gimp.org/node/111
> http://registry.gimp.org/files/Eg-BlackandWhite.scm

> Color vibrance
> http://registry.gimp.org/node/107
> http://registry.gimp.org/files/Eg-ColorVibrance.scm

> Copyright text
> http://registry.gimp.org/node/109
> http://registry.gimp.org/files/Eg-Copyright.scm

> Duotone simulation
> http://registry.gimp.org/node/110
> http://registry.gimp.org/files/Eg-DuotoneSimulation.scm

> DRI (Dynamic Range Extension)
> http://registry.gimp.org/node/113
> http://registry.gimp.org/files/Eg-DynamicRangeIncrease.scm

> Digital Infrared
> http://registry.gimp.org/node/114
> http://registry.gimp.org/files/Eg-InfraredSimulation.scm

> IR channel switch
> http://registry.gimp.org/node/102
> http://registry.gimp.org/files/Eg-InfraredChannelswitch.scm

> ISO noise reduction
> http://registry.gimp.org/node/104
> http://registry.gimp.org/files/Eg-ISONoiseReduction.scm

> Borders
> http://registry.gimp.org/node/106
> http://registry.gimp.org/files/Eg-Border.scm

> Smart Separate Sharpen
> http://registry.gimp.org/node/24876
> http://registry.gimp.org/files/Eg-SmartSeparateSharpen.scm

> Shadow recovery
> http://registry.gimp.org/node/112
> http://registry.gimp.org/files/Eg-ShadowRecovery.scm

> Highpass Sharpen
> http://registry.gimp.org/node/103
> http://registry.gimp.org/files/Eg-HighPassSharpen.scm
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<

> AnimStack
> http://animstack.tumblr.com/

> Auto rotate with a vector
> http://registry.gimp.org/node/22910

> Backup Working
> http://registry.gimp.org/node/14246

> BgMask
> http://animstack.tumblr.com/

> Black-and-White Film
> http://registry.gimp.org/node/25060
> http://registry.gimp.org/files/adsr-bw-films.scm

> diana-holga2
> http://registry.gimp.org/node/252
> http://www.vide.memoire.free.fr/photo/textes/contrefacons/diana-holga2d.scm

> El Samuko
> https://sites.google.com/site/elsamuko/

> Fake HDR Effect
> http://gimp-registry.fargonauten.de/node/11776

> FIL
> http://registry.gimp.org/node/24639
> http://registry.gimp.org/files/fil_current_pub_eng.scm

> GIMP FX Foundry
> http://gimpfx-foundry.sourceforge.net/

> gimphelp.org
> http://www.gimphelp.org/

> IGLO - Images Grid LayOut
> http://iglo.svoboda.biz/

> Layer Effects
> http://registry.gimp.org/node/186

> Midnight Sepia
> http://registry.gimp.org/node/10980
> http://registry.gimp.org/files/midnightSepia_0.scm
> http://registry.gimp.org/files/functions.scm

> Shadows&Highlight
> http://registry.gimp.org/node/4000
> http://registry.gimp.org/files/shadow-highlight.scm

> Split Studio 3
> http://registry.gimp.org/node/21370

> Traditional Orton
> http://registry.gimp.org/node/24441
> http://registry.gimp.org/files/orton.scm

> Warming and Cooling Filters
> http://registry.gimp.org/node/24473
> http://registry.gimp.org/files/hdroberts-tone-adjust_0.scm


---


**[Back to Top](#GIMP_Extensions.md)**