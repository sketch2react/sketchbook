---
description: All of our most important milestones & releases since the very beginning
---

# Releases ✍️

## 1.0.10 - 2020-11-30

### Added

* Big Sur support

## 1.0.8 - 2020-05-13

### Added:

* A 10:th rule to Stratos Tokens. You can now name a Text Layer _style-dictionary-value_ to get the following output in Stratos Tokens App:

![Example in your design tool](../.gitbook/assets/ska-rmavbild-2020-05-13-kl.-10.11.10.png)

![Output in Stratos Tokens](../.gitbook/assets/ska-rmavbild-2020-05-13-kl.-10.08.30.png)

![Result when building for scss with Style Dictionary](../.gitbook/assets/ska-rmavbild-2020-05-13-kl.-10.28.51%20%281%29.png)

## 1.0.7 - 2020-05-05

### Added:

* Support for Sketch symbols
* Previously, in Stratos Tokens, you were "bounced back" to _**Start**_ artboard every time your design file changed/updated. This is no longer the case. 

### Fixes:

* Sketch, Figma and InVision projects are now displayed on the start screen
* Fixed minor type-o:s

## 1.0.6 - Never

This is not the version your looking for... \*Jedi hand move\*

## 1.0.5 - 2020-04-22

### Changes:

_Explorer view_ is now visible from the start.

### FIxes:

* Updated in-app documentation links.
* Artboards in _Explorer view_ are now sorted alphabetically.

## 1.0.4 - 2020-04-20

### Changes:

* The Stratos Tokens output of _Texts_ and _Rectangles_ which have names matching a CSS property is changed **from** displaying the property name e.g. _fontSize_

![In Sketch / Figma / InVision Studio](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.17.44.png)

![Previously generated output in Stratos Tokens ](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.12.00.png)

**to** displaying _value_

![New generated output in Stratos Tokens](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.06.35.png)

This change is made to better match the expected input of Style Dictionary.



* All values defined in px such as font size, line height etc in _Sketch_, _Figma_ and _InVision Studio_ is now translated into unitless values \(with a [base of 16px](https://learnui.design/blog/mobile-desktop-website-font-size-guidelines.html)\). E.g. 72px / 16 = 4.5 This will be translated by Style Dictionary into platform specific units during Style Dictionary's build process. You can change to another base value by, in the ._stratosproject_ file, change the property _baseFontSizeInPx_

![](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-15.55.45.png)

### **Added:**

* New demo file \(.sketch, .fig, .studio\) for getting started with [Ant Design System ](https://ant.design)to work with our Style Dictionary support

## 1.0.2 - 2020-03-20

### Added:

* Style Dictionary integration to support export to web, mobile and desktop
* Support for Figma
* Support for InVision Studio
* Support for variables in text nodes **{**color.base.primary.value**}** \(specified as **{{**color.base.primary.value**}}**\) in your design tool. This is used to reuse values in Style Dictionary
* New menu item “File &gt; Open project in Terminal”
* Artboards can now be named anything and will still be considered as “Token artboards”. Previously only artboards named “Template” were considered for design token generation. \(You still need an artboard named _**Start**_\)

### **Fixes:**

* Bugfixes to the _Explorer view_.

