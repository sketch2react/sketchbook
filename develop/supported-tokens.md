---
description: >-
  Here we'll list all of the current supported design tokens and how to create
  them inside your awesome design application, Sketch, Figma or InVision Studio
  are currently supported.
---

# Supported Tokens \(WIP\)

## A couple of rules to follow

There are **seven design rules** that you **need to follow.**

1. The structure of nested Groups in the design document defines the structure of the output JSON data
2. Rectangles represent a color value based of the rectangle’s fill value
3. Text layers represent text formatting
4. Text layers with values within _**{ }**_ are evaluated
5. Text layers with values within _**{ }**_ and matches a CSS property will have only that CSS property’s value \(as opposed to plain Text layers which will contain all CSS properties; see bullet 3 above\)
6. The page were the tokens are created need to be named **Start here**
7. You need to have a frame/artboard named **Start.** It can be empty but it needs to be there for our app to work its magic

![This is the top level structure for setting up Material-UI tokens. The frame Themes can be called anything.](../.gitbook/assets/figmabasicsetupmaterialdesign.png)

