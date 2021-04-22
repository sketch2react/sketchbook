---
description: All you need to know about Sketch2React's different ways of exporting to code.
---

# Exporting to Code 🚚

## Export to Capacitor.js 

![Wanna go directly to iOS &amp; Android? Who wouldn&apos;t &#x1F63A;&#x1F4AA;](../.gitbook/assets/s2r202121-update-2.png)

You now also can export directly to iOS & Android project via something awesome called [Capacitor.js](https://capacitorjs.com)

1. Make sure you have [all links between pages](https://sketch2react.io/blog/tutorial-from-sketch-to-xcode-the-no-code-way/) working and that you have visited each page once \(it gets added to our export bundle that way\)
2. Click on the Download button 👉 **Download Capacitor project**
3. Unzip the folder we created for you
4. Make sure you compress the images, we 🧡 [TinyPNG](https://tinypng.com/)
5. Drag the entire folder onto e.g., Visual Studio Code
6. Open up a New Terminal in VSC
7. Type `npm install` and hit enter
8. Done!

### Install Xcode Command Line Tools & CocoaPods

This is **crucial** to do before you go to the next step of installing either the iOS or Android platforms.

* Download and install the **Xcode Command Line tools**. You can do this directly from [within Xcode](https://capacitorjs.com/docs/v3/getting-started/environment-setup) or you can just fire up the mighty Terminal app and add this installation snippet:

```text
xcode-select —install
```

* Download and install [CocoaPods](https://cocoapods.org/), easiest is just by adding this snippet directly in the Terminal:

```text
sudo gem install cocoapods
```

### Choose between iOS or Android

Now comes the part where you choose which platform to install for use with Capacitor. You can choose between iOS or Android, we have added both to the config.json file. 

#### **For iOS**

Just follow [these instructions](https://capacitorjs.com/docs/v3/ios#adding-the-ios-platform).

#### **For Android**

Just follow [these instructions](https://capacitorjs.com/docs/v3/android#adding-the-android-platform).



## How to export to React

Follow these instructions to the point and you’ll be exporting to React code and components in super little time. We promise 👍

### Adding things to export

1. Open up **Sketch2React** app. 
2. Go to **File, Link Sketch-file** \(⌘L\) or just **drag and drop** the Sketch file
3. Your Sketch file needs to have our markup rules \(components etc\)
4. Before anything can be exported to code, you need to **add each artboard/page to our export bundle.** You do that by visiting each page in your design, it adds itself automagically to our bundle after each page load. _Neat right?_
5. Press **Download** icon
6. Press React and save the .zip somewhere locally on your computer.

### Known issues

**Don’t save to Dropbox, OneDrive or Google Drive.** Or use at your own risk of being really annoyed 😅

Once you begin installing all the packages that are included in our React export, these services will most likely hickup. Or send you automated emails complaining you have to many files 😸

This is because we use [Create React App](https://github.com/facebook/create-react-app) \(among other things\) and it contains an amazingly amount of really small files. Size-wise we’re talking about approx 220MB of downloaded packages.

**iCloud** seems to be working fine with these many small files, no crash so far and the syncing seems to be working great between computers linked to the same Apple ID.

🏎️ Cool, now let’s move on to the really exciting part…

Now comes a couple of steps that first can seem very odd and very unfamiliar. Specially if you have never installed thingies via the Terminal. We have streamlined this as much as we can but hey, this is a real design to code environment, you can’t cheat your way through this 😸

## 🖐️ Node.js

For our **React export** to work you first need to install **Node.js**.

* Node.js is an open source server environment
* Node.js is free
* Node.js runs on various platforms \(Windows, Linux, Unix, Mac OS X, etc.\)
* Node.js uses JavaScript on the server

Download the latest build [from here](https://nodejs.org/en/download/)

## How to export to React \(Terminal\)

First of all, make sure you have **admin rights** to your computer or nothing of the below things will ever work. 

1. Open **Terminal app**. You know that weird little app you maybe have been in contact with when doing funky stuff to your Mac 😆 It’s actually really friendly, don’t be afraid. But weird yes.
2. Write **cd** and do a blank space
3. Go to your dl Sketch2React .zip, unzip and drag drop the entire folder onto your Terminal window. Drop it precisely after the words cd + your blank space. It should look something like this cd /users/
4. Hit Enter **↩︎**

## How to install all required packages \(Terminal\)

1.  Write **npm install** and hit enter **↩︎**
2. Since you have entered the correct cd installation of all required packages should begin

## How to start your development server \(Terminal\)

1. Write **npm start** and hit enter **↩︎**
2. It will take up to one minute and then you will see this message in the Terminal will open up your default browser with localhost:3000
3. Done! Now continue with your development outside of Sketch, do all changes directly in code.

## How to create a build \(Terminal\)

* If the server is running, press **Control+C** to stop it

{% hint style="warning" %}
You can’t create a build while the server is running!
{% endhint %}

* Write **npm run build** and hit enter **↩︎**

It will create a optimized build of your entire project. It takes a bit of time, just chill, stand up, look out your window or something 😄

## Building for Relative Paths

By default, **Create React App** produces a build assuming your app is hosted at the server root.

{% hint style="info" %}
Here’s how you [change that](https://facebook.github.io/create-react-app/docs/deployment#building-for-relative-paths). 
{% endhint %}

Open up **package.json** and enter this very path below version:

```text
"homepage": "http://mywebsite.com/relativepath",
```

![In our case here, we changed it to our own relative path.](../.gitbook/assets/relativepaths.png)

## Export to HTML

![](../.gitbook/assets/2019-09-10-13.38.52.gif)

1. First of all, make sure you _visit each and every page_ within our code app that you want to be included in your **Export Bundle.** Wait for the **Your Artboard was added to the export bundle** message to appear, it will take a few seconds per artboard, we're just making sure all the good stuff gets included 😺
2. Go to the **Side Bar** in our app and click **Download**
3. Save to great place
4. You know have a **.zip file** with all of your files, assets neatly organized in separate folders

