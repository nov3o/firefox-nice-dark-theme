# Nice customizable theme for Firefox, based on userChrome.css


## Browser screenshots:

### My theme is really compact. If compact density wasn't enough for you, you should install my theme
![If you see this sign, tell me](https://psv4.userapi.com/c848120/u128909579/docs/d14/f4b1646609f9/Minimized.png?extra=3LHUV_8GzlsjtAJ8fxUMPnZPhcPFzU0ZUPoe13jJ_37i_95UKLTxUM4EFzjlrTWijSbT0zzTr3LwjSyHHxxVq-LlrGPpDk_4K3jAY3dpiJwkFqXvOyEaAGMG53KCA17hrNszw1ZiuVATgve75X0oIXhQ "Difference between compact density out-of-the-box and my compact density")

### Nice custom home page
![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d9/464a075a0b3f/home_page.png?extra=lHMTQj3oKoPzKrmC1yFdKX5vTrGNfRP2p7XchIY0cFRKYnZR8MIxxBWmXlGCoggTXIjPjHl5APKGIABbdJAI5p8ykGyL0Vi6FqiWTL340-_Vbed48_XhGq6er0RuUUSmDJWL-V85b1lkSThCwYJ_4lPu "Home page")

### 3 default themes support
![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d15/c02feae488dd/Theme_support.png?extra=OXoT4INUKDhAXE3rfc6CJ5IlViqqG3dH4a2s-YLc_CUJkwuLjlnheYkHDqlrXsT7P6c7A5gty37wcMaB-xpa0fERDm9idmuUgPZs2OhdDOt-tMwfeANZcUnerp8hEWU5oZb-KgcV4uXl8yEs1V2m36mk "You can advance your favorite theme with my lines")

### Nice tab text color transition
![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d1/335d3b630ede/Tab_text_transition.png?extra=gAiT55EibfcCcY_Auo43nF3NMesU1MrZjex7V9eM8z-0LN9ZMtSFbRFXJL11vCnuEHtjUHrmWa62D0AsHFdHKZohxja9PhvQzhrPtH4YzOcPZGEH9xvTg-R9UuHyUHK8Enhhk8OtBuq4-UkIPeDXWm-b "Active, hover, inactive and pending tabs have different text colors")

### If you like Chrome's interface design or want smoothly move to Firefox, you can re-create Google's style just in couple of minutes
Google Chrome Classic theme in Firefox
![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d2/31777f303895/Chrome_theme.png?extra=4wu5VYZEBcp9wCyLK80Wqu4eAH6ma7yWpflNFxgcdd25eYna3OHEmZHwk6KqkWVK1ZImyU99ptjqMjbUy-h5zGbuvgSVdNFAqexH6R81TxNFMHvDutAHFZyk6FAQBSxFY2pq3q9BeMM2fKas3r9y6QvN "Chrome-styled interface, made in couple of minutes")


## Some important information:

#### Key features, for except of noticed above
- Many buttons are disabled, so you have much more space
- Now your address bar's width is almost 100% of window's width and you can type up to 180 symbols
- You can set any maximum tab width, so your couple or several tabs now can occupy all the tab bar width, not piece of it. For example, each of 2 opened tabs will have 50% of window
	![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d2/264f399a8fef/max_width.png?extra=29fCmKuFDE1J_Q_Ua_ZCuTt8Vx2aJe4bNAxDLADdLDtObJ9ECY1JmO2FtVEMVw4DQlod5_XnDPODNep7e_by8LY-oVo8zkszwNON_3ZpcLs0LnetAcAEk1DcKHjH_0na0GUlFmTkGUdqdHa6hLuQW2O9)
- Identity box now occupies least space until you hover it
	![If you see this sign, tell me](https://psv4.userapi.com/c848436/u128909579/docs/d7/0a36f3643cf3/identity_box.gif?extra=Y4JBnTGCAjHC4xz_N934Fbbup4jG50kVg-Vx8d46jnN1sQajMefwcfmbnzD3xa6T3GwXCXKoCGFVtcfOboQORksJxbBT1WEeJ-8B3GpwT-ZTD8VEzz5beIA6sA7xtUYU20ISDwevfGwB4jkH9limdS0h)
- You can place hamburger button to top left corner
- You can make bookmark toolbar be visible only on home page
- You can easily customize anything, since all rules placed in related files
- Navigation and tab bars minimized more than 33%


Notice, I made this up in a way to make it be more compact, I changed many size properties, so any non-compact density will be rolled back to compact size or may be broke

#### Why many buttons are disabled?
On linux there are many shortcuts that speeds up your actions, so you can open any box I disabled with keyboard much faster, than point and click the box with your mouse. If you don't want, not used you this style, you can enable it in any time.

#### Theme goal
I wanted to make it more nice and more compact. Many buttons doesn't needed, since you have keyboard. The second goal was to make it more nice, disable ugly borders between bars, round icons and make it look in one(or two) solid colors. Since I installed Firefox, I had dark theme, but now I like default theme more due to few rounded elements and nice combination of colors.


## Compatibility:
Everything I made works good on Linux Ubuntu 18.04, Firefox stable 65.0. Haven't tested yet on other OSs and Fx versions. Try it and tell me, if something go wrong.


## Issues:
I still don't know how to solve next problems:
- How to switch themes without manual comment and outcomment :root blocks
- How to prevent home page image's "jump" caused by dis- and appearing of bookmark bar
- How to totally disable bookmark bar on non-home pages. When page is loading, bar appears for a second, but it shouldn't
- How to totally disable scroll bar or make it show if you point on window edge

If you know answers for questions above, tell me


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
