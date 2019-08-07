# Nice customizable theme for Firefox, based on userChrome.css


## Browser screenshots:

### My theme is really compact. If compact density wasn't enough for you, you should install my theme
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62637735-9f5e4b00-b92b-11e9-9b96-4dcf83322434.png "Difference between compact density out-of-the-box and my compact density")

### Nice custom home page
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62637777-b43ade80-b92b-11e9-8b0f-ce8e7519a3ba.png "Home page")

### 3 default themes support
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62637816-c61c8180-b92b-11e9-94c1-d8e01fdea4e1.png "You can advance your favorite theme with my lines")

### Nice tab text color transition
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62637844-d2a0da00-b92b-11e9-8de0-0abdb73efda2.png "Active, hover, inactive and pending tabs have different text colors")

### If you like Chrome's interface design or want smoothly move to Firefox, you can re-create Google's style just in couple of minutes
Google Chrome Classic theme in Firefox
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62637902-f2d09900-b92b-11e9-86a3-8ca731488f3e.png "Chrome-styled interface, made in couple of minutes")
A implemented a rounded bottoms like in Google Chrome, but I made it kinda rough, so I can't change color or this rounding. I made it with png image, instead of svg, because I don't know how to code this figure.
![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62638472-11835f80-b92d-11e9-9789-bd60f126a8dc.png "So niice")


## Some important information:

#### Key features, for except of noticed above
- Many buttons are disabled, so you have much more space
- Now your address bar's width is almost 100% of window's width and nav bar have just url bar + 36px(without extensions, with menu button at left top corner and with only account button and identity box at the end of url bar)
- You can set any maximum tab width, so your couple or several tabs now can occupy all the tab bar width, not piece of it. For example, each of 2 opened tabs will have 50% of window
	![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62638277-9f127f80-b92c-11e9-8d6b-afd1bd3de737.png)

- Identity box now occupies least space until you hover it:\
	![If you see this sign, tell me](https://user-images.githubusercontent.com/31302079/62638321-b8b3c700-b92c-11e9-9ad1-3ff0335971fe.gif)
- You can place hamburger button to top left corner
- You can make bookmark toolbar be visible only on home page
- You can easily customize anything, since all rules placed in related files
- Navigation and tab bars are minimized a lot. All bars(menu bar, tabs, url, bookmarks and find ones) are minimized to 97/147 pixels


Notice, I made this up in a way to make it be more compact, I changed many size properties, so any non-compact density will be rolled back to compact size or may be broke

#### Why many buttons are disabled?
On linux there are many shortcuts that speeds up your actions, so you can open any box I disabled with keyboard much faster, than point and click the box with your mouse. If you don't want to go this way, you can enable it buttons any time.

#### Theme goal
I wanted to make it more nice and more compact. Many buttons doesn't needed, since you have keyboard. The second goal was to make it more nice, disable ugly borders between bars, round icons and make it look in one(or two) solid colors. Since I installed Firefox, I had dark theme, but now I like default theme more due to few rounded elements and nice combination of colors.


## Compatibility:
Everything I made works good on Linux with Gnome DE, Firefox stable 68.0. Haven't tested yet on other OSs and Linux distros


## Issues:
I still don't know how to solve next problems:
- How to switch themes without manual comment and outcomment :root blocks
- How to prevent home page image's "jump" caused by appearence toggling of bookmark bar
- How to totally disable bookmark bar on non-home pages. When page is loading, bar appears for a moment, I don't want it to act like this
- How to totally disable scroll bar or make it show if you point on window edge. Idea to make every page scrollable and then cut that space doesn't work, cause every html page out of main window(i.e. extensions' htmls) have scrollbars on edges
- Make sense to rewrite fx interface file
- I don't know what svg to use in rounded bottoms of tabs and how to switch colors in that case
- Extensions that doesn't fit in ther blocks, moves to overflow menu
- Some features I implemented kinda rough and inefficient. I am not experienced front-end developer, so I can have no knowledge how some algorithms work and do some things more difficult way


## Customizing:

#### First way:
Change :root variables.
This is more "general" and easy way to customize your theme. I advice you to create new :root block and comment others to roll back to default settings if some errors occur

#### Second way:
Change css rules manually.
This is less reliable and more complicated, but it offers more tweaks and it's more grained way to customize your browser


## How to install the theme:
How to find profile folder and install the theme you can find [here](http://kb.mozillazine.org/index.php?title=UserChrome.css).
To switch the theme you have to:
- Change theme on customization page
- Change theme in css/variables.css. Comment your current and outcomment preferred
- Change or don't font color in css/variables.css. Bright colors for default and dark theme. Dark colors for light theme
- Restart browser

You can set variables in file with this name to change browser without changing switching theme in browser, but label colors or menu backgrounds may be broke, so I advice you not to skip first bullet.


## Afterword
Some code snippets took from [UserChrome-Tweaks](https://github.com/Timvde/UserChrome-Tweaks). I made this for myself and glad about all this work. It became much small. Some features have worse performance than others, so you should enable only those you really need. This project closes to it's end, I implemented all I wanted and probably won't spend more time on it. I want you to fork it and make it more prettier and convenient for users like me, how not satisfied with this interface fatness
