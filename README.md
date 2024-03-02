# Color Shell Text
Takes a string and adds color to it to be displayed in the console. Intended to make coloring the shell more developer friendly.

# About
I made this to make my personal shell look nicer when developing.

# Usage
There are two functions. ```coloredConsoleLog``` for logging in the shell, and ```convertColors``` for returning the string value. 
When passing strings as parameters, include the following arguments inside of the string. (Examples are shown later down).

```colorRed```,```colorGreen```,```colorYellow```,```colorBlue```,```colorPurple```,```colorCyan```,```colorReset```

```
const { coloredConsoleLog } = require("utilities/color-shell-text");
```
This will act as a replacement for ```console.log()```. Taking any input and logging it.
```coloredConsoleLog("colorGreenHi Mom!");```
> \u001b[1;32mHi Mom!


```
const { convertColors } = require("color-shell-text");
```
