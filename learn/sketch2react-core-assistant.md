---
description: Here's all of our awesome Sketch assistant rules explained. For normal humans.
cover: ../.gitbook/assets/frame-horizontal-1920x1080.png
coverY: 0
---

# Sketch Assistant Rules Explained 📐

{% hint style="success" %}
Download our [Sketch assistant](https://www.sketch.com/extensions/assistants/@sketch2react/sketch2react-assistant/)
{% endhint %}

## Document must contain one artboard named “Start” on a page named “Start here”

![](<../.gitbook/assets/Skärmavbild 2020-10-05 kl. 14.22.08 (2).png>)

Behind the scenes this artboard actually becomes your **very first page in code**, aka index.html 🤖💪

## Document must contain one page named “Start here”

![](<../.gitbook/assets/Skärmavbild 2020-10-05 kl. 14.35.05.png>)

We call this the **code page**. You can have several pages in your Sketch file but only the things that are on this super important page comes out to code in Sketch2React. ✅

## Group name may contain zero or one pair of square brackets

![In this example we added a margin top of 16px to this text block ](<../.gitbook/assets/Skärmavbild 2020-10-05 kl. 15.45.27 (1).png>)

**Square brackets** **\[ ] **are used for adding CSS rules to specific parts of your design. Read more about them [here](https://app.gitbook.com/@sketch2react/s/sketch2react-io/learn/cheat-sheet#classes).

## Group name must contain one pair of curly brackets

![](<../.gitbook/assets/Skärmavbild 2020-10-06 kl. 14.57.23.png>)

**Curly brackets** **{ } **are used within the Sketch2React framework to define component name i.e. **{container}**. Incorrect number of square brackets will cause parsing errors.

## Text name must contain one pair of curly brackets

![Here we have created a {text} component and saved it as a symbol aka reusable component](<../.gitbook/assets/Skärmavbild 2020-10-06 kl. 15.02.51.png>)

**Curly brackets** **{ } **are used within the Sketch2React framework to define component name i.e. **{text}**. One neat trick is that if you convert your Sketch2React components to symbols, you don't need to follow our naming convention for the parent, in above case we have called the symbol **H1**.

## Text name may contain zero or one pair of square brackets

![Here we use the CSS class for using view height 100% for a nice flex layout of the whole container](<../.gitbook/assets/Skärmavbild 2020-10-06 kl. 15.10.32.png>)

Square brackets are used within the Sketch2React framework to define css-classes i.e. \[css-class-name1 css-class-name2].

## Artboards must contain at least one text layer named {externalasset.css}

![](<../.gitbook/assets/Skärmavbild 2020-10-06 kl. 15.16.07.png>)

**{externalasset.css} **is used within the Sketch2React framework to target external CSS assets (fonts, local CSS-files, animation libraries etc.) that should be included in the generated output. Make sure to copy them to all your pages where you have external dependencies.
