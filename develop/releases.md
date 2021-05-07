---
description: All of our most important milestones & releases since the very beginning
---

# Releases ✍️

## 2021.3.0 2021-05-08

### Added

* Support for Style Dictionary 3.0
* Link to our Sketch assistant in the help menu

### Fixes

* Cleaned up the design token view
* Cleaned up README view
* Minor UI improvements

## 2021.2.0 2021-04-20

### Added

* You can now name your **Texts** and **Rectangles** as css properties \(e.g. fontSize\) and only that value will be displayed in Stratos Tokens App. 

![Note that the names are in camelCase e.g. fontSize](../.gitbook/assets/image.png)

_Please note that the matching css property will be named "value" in Stratos Tokens App. This is to better match the expected input of Style Dictionary._

Supported css properties for **Text layers** are:

* * color
  *  fill \(is always transparent for text layers\)
  *  fontFamily 
  * fontSize 
  * fontWeight 
  * lineHeight 
  * letterSpacing 
  * opacity

![E.g. weight outputs only the weight/width of the border](../.gitbook/assets/image%20%282%29.png)

_Please note that the matching css property will be named "value" in Stratos Tokens App. This is to better match the expected input of Style Dictionary._

Supported css properties for **Rectangles with borders** are:

* * weight
  * color 
  * radius

## 2021.1.10 - 2021-04-08

### Added

* Support for a more visual way of outputting design tokens for **breakpoints**, **spacing**, **padding** etc - use the width of the line tool
* Support for multiple **shadows** - just add shadows to rectangles
* No more need for a page named Start here and an artboard named Start
* [Demo version](https://marketplace.sketch2react.io/product/stratos-tokens-demo/) of Stratos Tokens
* Windows version
* Dark mode support
* We now have a little 🕵️‍♀️ that helps you re-link your designfile if you have moved it 
* Possibility to register a bug from within the app
* Extended help menu containing links to documentation, tutorials and more

### Breaking changes

* **Use { } for all your design tokens \(artboards + layer + group names\)** – mix them with regular design elements

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

