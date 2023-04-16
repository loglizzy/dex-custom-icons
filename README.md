# Script
```lua
-- Change to an valid theme (example: "Green", "Blue)
getfenv(1).currentTheme = "Mono"

-- Change its RGB value to apply an custom color (example: equivalent to red in RGB: 255, 0, 0)
getfenv(1).customColor = Color3.fromRGB(255, 255, 255)

-- Some few modifiers to improve the explorer like you want
getfenv(1).modfiers = {
    SearchOnType = true -- auto updates the explorer list when you type on the search box
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/loglizzy/dex-custom-icons/main/main.lua"))()
```

# Themes
* Mono (white icons)
* Colourful
* Green
* Purple
* Yellow
* Blue
* Red

# Update 04/16
I updated the icon map, it supports all the current classes right now
