Javascript is the language of the web. See some examples below of Javascript games using a variety of tools.

# Table of Contents:

* [Phaser](#phaser)
* [P5js](#p5js)
* [The House](#the-house)

----

# Phaser

**Phaser** is a 2D game framework for making 2D web games. It uses javascript, and there are a lot of resources online to help you figure out the details. Find the example code here: [https://github.com/HarrisonburgHighSchool/Phaser-Template](https://github.com/HarrisonburgHighSchool/Phaser-Template)

### How to Start

Setting up Phaser is a little complicated if you have never created a web server before. Here is a step-by-step process for getting everything set up. You can also use the instructions at [this link](https://phaser.io/tutorials/getting-started-phaser3) if you prefer.

### Step 0: Tools

You will need a few pieces of software before you are ready to write web games with Phaser. Here is a list of some options:

1. A text editor (like [Atom](https://atom.io/) or [VSCode](https://code.visualstudio.com/)
2. A web server (Node or Python recommended, see below)
3. The [Phaser library](https://phaser.io/download)
4. [GitHub Desktop](https://desktop.github.com/) *optional*

You can also follow the steps below for more detailed information on downloading everything.

### Step 1: Text Editor

The text editor is the software you will use to write your code. Click one of the links below to download:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://atom.io/)

Both are free. Choose one, they are very similar so don't get too worried about it.

### Step 1.5: GitHub Desktop

GitHub Desktop is an excellent tool for sharing code and managing versions. We strongly recommend that you download it if you have not already. Use the link below:

* [GitHub Desktop](https://desktop.github.com/)

You don't need it, but it makes things very simple for you.

### Step 2: Phaser

Phaser is simply a bunch of Javascript files you can put in your project folder. There are many ways to download the files, but we recommend that you **clone the Game Jam Phaser Example** using GitHub Desktop. Here are instructions for that:

1. Open **GitHub Desktop**
2. Click `Clone a Repository` (if you don't see a button, go to `File > Clone a Repository`)
3. Click the `URL` tab
4. Paste this link into the text box: [https://github.com/HarrisonburgHighSchool/Phaser-Template](https://github.com/HarrisonburgHighSchool/Phaser-Template)
5. Click `Clone`

### Step 3: Open the Code

The cloning process will download all the files for you, and package them up into a folder called a **repository**. You can then **open the code by clicking the button** that says `Open in Atom` or `Open in Visual Studio Code`, depending on which one you chose.

### Step 4: Run the Code

To quickly run the code, find the project folder you downloaded and double-click the `index.html` file. Here are some more specific instructions:

#### With GitHub Desktop

1. Open **GitHub Desktop**
2. Go to `Repository > Show in Explorer` (for Mac, `Repository > Show in Finder`)
3. Double-click the `index.html` file

#### Without GitHub Desktop

1. Open your the File Explorer (Windows) or Finder (Mac)
2. Search for `phaser-example`
3. Open the `phaser-example` folder
4. Double-click `index.html`

### Step 4.5: Run the Code Using the Web Server *optional*

The code you downloaded is an example that already works. This is the tricky part; there are two ways of accomplishing this task. Choose one:

#### Method 1: Python

1. Make sure you have download [Python](https://www.python.org/downloads/)
2. Open up a **Command Prompt** or **Terminal**
  * For Windows: type `cmd` into the `Start` search box, and press `Enter`.
  * For Mac: Type `Cmd + Space` to open up the launcher, and type `terminal`. Press `Enter`.
3. Use `cd` commands to enter your project folder, then enter `python -m SimpleHTTPServer` in the terminal or prompt.
4. 6. Open your browser (we recommend [Chrome](https://www.google.com/chrome/) and go to [localhost:8000](localhost:8000) to see your game.

#### Method 2: Node

1. Make sure you have downloaded [NodeJS](https://nodejs.org/en/download/). Use the free version, which requires you to make an account.
2. Open up a **Command Prompt** or **Terminal**
  * For Windows: type `cmd` into the `Start` search box, and press `Enter`.
  * For Mac: Type `Cmd + Space` to open up the launcher, and type `terminal`. Press `Enter`.
3. In the terminal or prompt window, type `npm -v` to check to see if NodeJS is installed correctly.
4. If NodeJS is installed, run the following command to download the server: `npm install http-server -g`.
5. Use `cd` commands to enter your project folder, then enter `http-server` in the terminal or prompt.
6. Open your browser (we recommend [Chrome](https://www.google.com/chrome/) and go to [localhost:8080](localhost:8080) to see your game.

### Step 5: Make a Game!

There are a lot of resources online for you to look at and try. Explore the links below for some ideas:

* Phaser Beginner Tutorial: [https://phaser.io/tutorials/making-your-first-phaser-3-game/part1](https://phaser.io/tutorials/making-your-first-phaser-3-game/part1)
* Breakout Game: [https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_breakout_game_Phaser](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_breakout_game_Phaser)
* [Phaser API](https://phaser.io/docs)
* [Tutorials](https://phaser.io/learn/community-tutorials)

### Demos

Here are some games made with **Phaser**:

* Curvatron: [http://bravebunny.github.io/curvatron/](http://bravebunny.github.io/curvatron/)
* Sasquash: [http://www.davidbrind.co.uk/toemv1.0/index.html](http://www.davidbrind.co.uk/toemv1.0/index.html)
* Hexagonia: [https://play.google.com/store/apps/details?id=com.spa.hexagonia](https://play.google.com/store/apps/details?id=com.spa.hexagonia)
* Ramp Lab: [http://www.kongregate.com/games/toweld/ramp-lab](http://www.kongregate.com/games/toweld/ramp-lab)

----

# P5js

**P5js** is a Javascript framework for making visual and sonic art with code. It is very easy to get started; there are two methods:

### Method 1: The P5js Web Editor

P5js has a web editor, which means you can write and test code on their website and download the project later. This is the easiest way to get started.

1. Go to [https://editor.p5js.org/](https://editor.p5js.org/)
2. Press the `Play` button in the upper left corner to test the code!

This is the best way to get familiar with P5js. If you are used to writing and testing Javascript using a text editor and your browser, use **Method 2:**

### Method 2: Using a Text Editor

You can also edit code offline using a text editor, and testing code in your browser. This is a little more complicated, and we recommend this method only if you are familiar with writing and testing Javascript using your web browser.

### Step 0: Tools

You will need a few pieces of software before you are ready to use P5js outside of the web editor. Here is a list of some options:

1. A text editor (like [Atom](https://atom.io/) or [VSCode](https://code.visualstudio.com/)
2. The [P5js library](https://p5js.org/download/)
3. [GitHub Desktop](https://desktop.github.com/) *optional*

You can also follow the steps below for more detailed information on downloading everything.

### Step 1: Text Editor

The text editor is the software you will use to write your code. Click one of the links below to download:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://atom.io/)

Both are free. Choose one, they are very similar so don't get too worried about it.

### Step 1.5: GitHub Desktop

GitHub Desktop is an excellent tool for sharing code and managing versions. We strongly recommend that you download it if you have not already. Use the link below:

* [GitHub Desktop](https://desktop.github.com/)

You don't need it, but it makes things very simple for you.

### Step 2: P5js

Next, you need to download a P5js template to get started with. There are several ways to do this. The easiest is to download the [P5js Template](https://github.com/HarrisonburgHighSchool/p5-starter) repository and use GitHub Desktop to **clone** it to your computer. Here are some detailed steps:

#### Method 1: With GitHub Desktop

1. Open **GitHub Desktop**
2. Click `Clone a Repository` (if you don't see a button, go to `File > Clone a Repository`)
3. Click the `URL` tab
4. Paste this link into the text box: [https://github.com/HarrisonburgHighSchool/p5-starter](https://github.com/HarrisonburgHighSchool/p5-starter)
5. Click `Clone`

This process downloads all the required files to your computer.

#### Method 2: Without GitHub Desktop, Downloading a Web Project

1. Go to [https://editor.p5js.org/](https://editor.p5js.org/)
2. Click `Log In` in the top-right corner of the screen
3. Log in with a Google or GitHub account, or create an account.
4. Back in the editor window, go to `File > Save`
5. Then, click `File > Download`
6. The computer will download a 'zip' file with the library and `sketch.js` file all packaged up for you
7. Extract the files from the zip file, and then open the project folder in your text editor

Run the code by following these steps:

1. Open your the File Explorer (Windows) or Finder (Mac)
2. Search for the folder containing your project files
3. Open the project folder
4. Double-click `index.html`

The code will open in your browser, and you are good to go!

### Step 3: Editing the Code

To start, try pasting this example in to your editor. If you are not using the web editor, edit the `sketch.js` file.

```javascript
var x = 20;

function setup() {
  createCanvas(400, 400);
}

function draw() {
  x = x + 1;
  ellipse(x, 20, 10);
}
```

The program runs in this order:

1. First, all the code inside the `setup()` function (between the `{` and `}` after `function setup()`) runs in order
2. Then, all the code inside the `draw()` function runs in order.
3. Then, the code inside the `draw()` function repeats
4. ... and repeats
5. ... and repeats
6. ... and repeats
7 ...

The `draw()` function repeats over and over again forever, until you close the browser window or click the `Stop` button in the top-left corner of the browser window (if you are using the web editor).

### Resources

Here are some resources to get you started using **P5js**:

* [Coding Train Tutorial Videos](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) *highly recommended*
* [Coding Train Text Tutorials](https://thecodingtrain.com/Tutorials/)
* [P5js Official Tutorials](https://p5js.org/learn/)
* [Happy Coding P5js Tutorials](https://happycoding.io/tutorials/p5js/)
* [Beginner P5js](https://blog.kadenze.com/creative-technology/p5-js-crash-course-recreate-art-you-love/)

### Demos

This site is the best place to find tons of examples of art made with P5js: [https://www.openprocessing.org/browse/#](https://www.openprocessing.org/browse/#)


----

# The House

The house is a very restrictive Javascript framework designed to help you make interactive fiction projects. Follow the steps below to download and test out the framework for yourself:

### Step 0: Tools

You will need a few pieces of software before you are ready to use P5js outside of the web editor. Here is a list of some options:

1. A text editor (like [Atom](https://atom.io/) or [VSCode](https://code.visualstudio.com/)
2. The [House source code]https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction)
3. [GitHub Desktop](https://desktop.github.com/) *optional*

You can also follow the steps below for more detailed information on downloading everything.

### Step 1: Text Editor

The text editor is the software you will use to write your code. Click one of the links below to download:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://atom.io/)

Both are free. Choose one, they are very similar so don't get too worried about it.

### Step 1.5: GitHub Desktop

GitHub Desktop is an excellent tool for sharing code and managing versions. We strongly recommend that you download it if you have not already. Use the link below:

* [GitHub Desktop](https://desktop.github.com/)

You don't need it, but it makes things very simple for you.

### Step 2: The House Source Code

You can download the source code for **The House** from GitHub. Here are some detailed steps for downloading the project:

#### Method 1: With GitHub Desktop

1. Open **GitHub Desktop**
2. Click `Clone a Repository` (if you don't see a button, go to `File > Clone a Repository`)
3. Click the `URL` tab
4. Paste this link into the text box: [https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction](https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction)
5. Click `Clone`

To **edit your code**, follow these steps:

1. Open **GitHub Desktop**
2. Go to `Repository > Open in Atom` or `Repository > Open in Visual Studio Code`
3. Make changes to the `main.js` file

To **run your code**, follow these steps:

1. Open **GitHub Desktop**
2. Go to `Repository > Show in Explorer` (Windows) or `Repository > Show in Finder` (Mac)
3. Double-click the `index.html` file

#### Method 2: Without GitHub Desktop

1. Go to the project GitHub page: [https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction](https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction)
2. Click the green `Clone or Download` button in the upper right-hand corner
3. Choose `Download ZIP`
4. Extract the zipped files that downloaded to your computer

To **edit your code**, follow these steps:

1. Find your extracted folder containing the project files
2. Open the folder in your text editor
3. Make changes to the `main.js` file

To **run your code**, follow these steps:

1. Find your extracted folder containing the project files using Finder or the File Explorer
2. Open the project folder
3. Double-click on `index.html`

### Resources

Check out the [House Documentation](https://github.com/HarrisonburgHighSchool/The-House-An-Interactive-Fiction/blob/master/README.md) for information on how to add rooms and other things to the game.

----

