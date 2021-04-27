---
description: The fundamental basics of Stratos Tokens
---

# The basics

{% hint style="success" %}
We now have a splendin [Sketch assistant](https://www.sketch.com/extensions/assistants/stratos-tokens-assistant/) for the most important rules
{% endhint %}

## The basic rules

There are **a couple of great rules** that you need to follow.

* The structure of nested Groups in the design document defines the structure of the output JSON data

![](../.gitbook/assets/cleanshot-2021-04-06-at-09.18.33-2x%20%281%29.png)



* Rectangles represent a color value based of the rectangle’s fill value

![](../.gitbook/assets/cleanshot-2021-04-06-at-09.19.38-2x.png)

* Rectangles without a fill results in border formatting.
* Text layers represent text formatting
* Text layers with values within _**{ }**_ are evaluated

![](../.gitbook/assets/cleanshot-2021-04-06-at-09.21.32-2x.png)

* Text nodes with values within **{{ }}** are considered as Style Dictionary references / shortcuts to be able to reuse values. 

![Here we have different border formatting values such as radius, weight and color](../.gitbook/assets/ska-rmavbild-2021-04-14-kl.-10.35.56.png)

* Text layers with names that matches a **CSS property** will have only that CSS property’s value \(as opposed to plain Text layers which will contain all CSS properties; see bullet 4 above\)

![How this looks in code](../.gitbook/assets/ska-rmavbild-2021-04-14-kl.-10.37.38.png)

