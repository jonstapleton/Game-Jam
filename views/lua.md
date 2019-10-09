**Lua** is a popular scripting language based on C++. Many popular games are created using Lua with a C# or C++ engine. Below are some game engines that you can use Lua with. Follow the instructions to get them set up.

# Table of Contents

* [Pico-8](#pico-8)
* [Love2D](#love2d)

----

# Pico-8

Pico-8 is a virtual console that features a code editor, sprite creator, and several useful functions to streamline the game creation process. Pico-8 is very limited: the whole screen is only 128 x 128 pixels, meaning that it has a pixelated, retro look. 

### Demos:

Here are some games made with Pico-8:

* [Celeste]()
* 

### Getting Set Up

Follow the instructions below to get Pico-8 set up:

### Step 1: Purchase & Download Pico-8

Pico-8 is an all-in-one program that you can download from the internet. It costs $15.00. Follow the link to purchase Pico-8: [https://www.lexaloffle.com/games.php?page=updates](https://www.lexaloffle.com/games.php?page=updates)

If you cannot purchase Pico-8 but would like to use it for the Game Jam, please contact the Game Jam coordinators to request a copy: 

* Jon Stapleton: [jstapleton@harrisonburg.k12.va.us]()
* Perry Shank : [pshank@harrisonburg.k12.va.us]()

### Step 2: Write and Test Your Code

You write and test your code all in the Pico-8 program.

1. Open **Pico-8**
2. To write code, press `Esc`

The editor will open up. Paste the following code into the editor to get started:

```lua
function _init()

end

function _update()

end

function _draw()
  rectfill(10, 10, 40, 40)
  print('hello, world', 0, 0)
end
```

Once you have pasted your code, you need to run it to see what it does.

1. Hit `Esc`
2. Save your file by typing `save nameofgame` in the black screen and pressing `Enter` (you can put whatever you want to name your game, it doesn't have to be 'nameofgame')
3. Run your game by typing `run` and pressing `Enter`

### Resources

Now that you are set up, go check out some games made with Pico-8. 

Go to the black console screen in Pico-8. Type `splore` and hit `Enter`. You will be able to load and run other games made with Pico-8 on this screen. You can even look at the code! Check out the following resources for information on how to use Pico-8 to make games:

* [Build a Retro Game with Pico-8](https://thenewstack.io/retro-game-pico-8-basics/)
* 

----

# Love2D

**Love2D** is a Lua framework for creating games. It is used by many amateur and indie developers as a tool for making 2D games. Here are some games made with Love2D:

### Demos

### Getting Started

You will need to download a few things to begin making games with Love2D. Here's a list:

* A text editor (like [Atom]() or [VSCode]())
* The [Love2D game engine]()
* An extension for your text editor
* [GitHub Desktop]() *optional*

Follow the steps below for details on setting up Love2D:

