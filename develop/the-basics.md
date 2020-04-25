---
description: The fundamental basics of Stratos Tokens
---

# The basics

## The basic rules

There are **nine design rules** that you **need to follow.**

* The structure of nested Groups in the design document defines the structure of the output JSON data

![](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.35.38.png)



* Rectangles represent a color value based of the rectangle’s fill value

![](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.37.14.png)

* Rectangles without a fill results in border formatting.
* Text layers represent text formatting
* Text layers with values within _**{ }**_ are evaluated

![](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.39.43.png)

* Text nodes with values within **{{ }}** are considered as Style Dictionary references / shortcuts to be able to reuse values. 
* Text layers with names that matches a CSS property will have only that CSS property’s value \(as opposed to plain Text layers which will contain all CSS properties; see bullet 4 above\)

![](../.gitbook/assets/ska-rmavbild-2020-04-17-kl.-16.41.37.png)

* You need to have a frame/artboard named **Start.** It can be empty but it needs to be there for our app to work its magic
* You need to have a page called **Start here** where all of your design tokens artboards/frames are created. This is also where the Start artboard/frame needs to be

