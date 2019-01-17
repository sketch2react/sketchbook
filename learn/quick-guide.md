# How it works
![](S2RHowItWorks.jpg)
A very brief overview on how our framework works just to get you started.

## Step 1 - Do your design magic
**First design your stuff. ** Then it's time to analyze your design and mentally (or on paper) divide them into Containers, Rows and Columns. We use Bootstrap so a basic understanding of how the grid works is very very recommended. 

Then you can go two ways: either you do it all by hand (recommended for advanced users) or you use our plugin to create folders containing things like rows, columns, paddings and margins. Our plugin is NOT REQUIRED for this to work, but it will help you in the very beginning speeding up your understanding of how things need to be setup inside of Sketch.

> 🎓Important! The page (in Sketch) needs to be named **Start here** and the first artboard needs to be named **Start** or our code app will not read your .sketchfile.

## Step 2 - Moving and naming stuff
**This step is the most important one.** It’s now that you begin giving your Sketch design file the super power of **Bootstrap 4** and **React** without even leaving the document. You are enhancing your design with real code components and the **amazing responsive** grid (we love you Bootstrap 4).

You add our components to Sketch by using very familiar built in Sketch tools like the Text Node (T), Grouping (⌘+G) and the shapes we support. 

> Number one rule: You need to **name each layer and group** with our component names or it will not work at all in code!

## Example on how you create a {container} in Sketch
1. Create a **text node (T)**
2. **Group** that text node (⌘+G)
3. Rename group **{container}**
4. Delete text node or name it {text} - Now the text you add to this very text node will show up in code. Awesome! Style to your likings, our .css automagically overrides Bootstraps with your delicious styles

Check our [Components](https://sketch2react.gitbook.io/sketch2react-io/develop/components%20) or [Cheat Sheet](https://sketch2react.gitbook.io/sketch2react-io/learn/cheat-sheet). And please study our demo files.

## Step 3 - Link to our Desktop Code App
👨🏻‍💻**Now comes the really fun part**, seeing your static Sketch design file starting to come alive!

We recommend you using our **desktop Code App** for this. [Read here](https://sketch2react.gitbook.io/sketch2react-io/develop/code-app) why this is like 10000% better than our web based Previewer App.

If you have done your homework of **Step 2**, you will see your design file beautifully rendered and fully responsive based on what you have set up.

## How to use install & use our Code App
Once you have downloaded the app you install it like any other Mac app on your computer. After that follow these simple steps to get up and running: 
1. Open up our **Sketch2React Code App **
2. Go to **File---\>Open (⌘O) **
3. **Open up the .sketchfile** you are working on
4. That same file is now linked with our **Code App** 
5. Happy makings!

## Sketch2React Code App features
- **Hot Reload** - Every time you save in Sketch it automatically reloads that file in our code app
- **Offline Mode** - Everything that does not require an internet connection in your design file will work offline
- **Mobile View** = Opens up another responsive window of your design with the start width of 576px
- It’s super fast 
- Use CSS plugins
- Handy shortcuts to our documentation & tutorials (requires internet connection to work)

## How to download HTML5 from our Code App

1. Go to the **side bar** in our app and click **Add to Export**
2. Do this for each artboard you want exported to HTML5
3. Go to **Download** and choose where to save
4. You know have a .zip file with all of your files, assets neatly organized in separate folders
> If you have set everything up correctly inside of Sketch, the only thing you need to do now is drag all of these files onto your own server and your done! 💥
> 
## Handy shortcuts in our Code App
**⌘O** = Link to your .sketchfile
**⌥⌘M** = Mobile View, opens up a new responsive window with start width 576px
**⌘D** = Documentation
**⌘T** = Tutorials 
**⌘F** = Demo files
**⌘P** = Publications on our blog

## Web app?
We still have our web app [(Previewer App](https://sketch2react.io/sketch2reactpreviewer/)), it’s really great to quickly show folks what our framework can do. Perfect also for sending devs your enhanced Sketch files to quickly show them your responsive designs. It supports the same framework that our Code App does.

But once you start using our native Mac Code App you will most likely understand the strengths of having a desktop app for this. And you can do stuff with our Code App that you can't do with the web version. Like adding **custom CSS plugins**, and that is very exciting news friends. We'll do a simple tutorial on how to later on.

