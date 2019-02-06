---
description: All you need to know about Sketch2React's code export
---

# Exporting to Code

{% hint style="warning" %}
**Disclaimer - React export is not yet available**, we're in closed/private pilot mode for the whole of February 2019 and maybe more.
{% endhint %}

## How to export to React \(paid\)

Follow these instructions to the point and you’ll be exporting to React code and components in super little time. We promise 👍

### Adding things to export \(Code App\)

1. Open up our **Code App**. Make sure you have activated the React Export module by entering the license key from **React Export Guide - License & Code App**
2. Go to **File, Link Sketch-file** \(⌘L\)
3. Link to one of our demo files our your own
4. In our left sidebar menu click the **Download** icon. You should now see the **React export option** below HTML
5. Before anything can be exported to code, you need to **add each artboard/page to our export bundle.** You do that by pressing **Add to export** \(left side menu\) on each and every page you want to be included in the export.
6. Press **Download** icon. If everything worked when activating you should see **React** below HTML.
7. Press React and save the .zip somewhere locally on your computer.

### Known issues

**Don’t save to Dropbox, OneDrive or Google Drive.** Once you begin installing all the packages that are included in our React export, these services will most likely crash/hang. Or send you automated emails complaining you have to many files 😸

This is because we use [Create React App](https://github.com/facebook/create-react-app) \(among other things\) and it contains an amazingly amount of really small files. Size-wise we’re talking about approx 220MB of downloaded packages.

**iCloud** seems to be working fine with these many small files, no crash so far and the syncing seems to be working great between computers linked to the same Apple ID.

🏎️ Cool, now let’s move on to the really exciting part…

Now comes a couple of steps that first can seem very odd and very unfamiliar. Specially if you have never installed thingies via the Terminal. We have streamlined this as much as we can but hey, this is a real design to code environment, you can’t cheat your way through this 😸

### 🖐️ Node.js

For anything to work you first need to install **Node.js**.

* Node.js is an open source server environment
* Node.js is free
* Node.js runs on various platforms \(Windows, Linux, Unix, Mac OS X, etc.\)
* Node.js uses JavaScript on the server

Download the latest build [from here](https://nodejs.org/en/download/)

### How to export to React \(Terminal\)

First of all, make sure you have **admin rights** to your computer or nothing of the below things will ever work. 

1. Open **Terminal app**. You know that weird little app you maybe have been in contact with when doing funky stuff to your Mac 😆 It’s actually really friendly, don’t be afraid. But weird yes.
2. Write **cd** and do a blank space
3. Go to your dl Sketch2React .zip, unzip and drag drop the entire folder onto your Terminal window. Drop it precisely after the words cd + your blank space. It should look something like this cd /users/
4. Hit Enter **↩︎**

### How to install all required packages \(Terminal\)

1.  Write **npm install** and hit enter **↩︎**
2. Since you have entered the correct cd installation of all required packages should begin

### How to start your development server \(Terminal\)

1. Write **npm start** and hit enter **↩︎**
2. It will take up to one minute and then you will see this message in the Terminal will open up your default browser with localhost:3000
3. Done! Now continue with your development outside of Sketch, do all changes directly in code.

### How to create a build \(Terminal\)

* If the server is running, press **Control+C** to stop it

{% hint style="warning" %}
You can’t create a build while the server is running!
{% endhint %}

* Write **npm run build** and hit enter **↩︎**

It will create a optimized build of your entire project. It takes a bit of time, just chill, stand up, look out your window or something 😄

### Building for Relative Paths

By default, **Create React App** produces a build assuming your app is hosted at the server root.

Here’s how you [change that](https://facebook.github.io/create-react-app/docs/deployment#building-for-relative-paths). 

Open up **package.json** and enter this very path below version:

```text
"homepage": "http://mywebsite.com/relativepath",
```

In our case here, we changed it to our own relative path.

## Export to HTML \(free\)

1. Go to the **Side Bar** in our app and click **Add to Export**
2. Do this for each artboard you want exported to HTML5
3. Go to **Download** and choose where to save
4. You know have a **.zip file** with all of your files, assets neatly organized in separate folders

