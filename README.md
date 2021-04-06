# Workmark-Plus
a Small addon for Discord Web Users to get and Enjoy a Titlebar Looks Better in Fullscreen. :D

# Quick Ports
- To Use these versions just create a new usercss file or css file in stylus and paste one of your choice! 
> Custom Wordmark Version
```css
:root{
--discordtext: "DISCORD - THEMED BY STYLUS - UWU - uwuwuwuwuwuuwuwuwuwuwuwuwuwuwuwwuwuuwuwuwuwuwuwuuwuuwuwuwu";
--textcolor: linear-gradient(
        #7289DA 0%,
        #959da0 70%
    );
}

@font-face {
    font-family: 'Discord';
    src: url("https://HypeSquad-inc.github.io/fonts/Discord-Sans/Discord Sans.otf ") format("opentype");
}
#app-mount::before {
    padding-left: 4px;
    content:var(--discordtext);
    font-family: Discord;
    line-height: 25px;
    background: var(--textcolor);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
```
> Discord Logo Version
```css
@import url(https://therealgwjosh.github.io/Workmark-Plus/src/IconImport.css);
```
> Discord Wordmark Version
```css
@import url(https://therealgwjosh.github.io/Workmark-Plus/src/WordmarkImport.css);
```
