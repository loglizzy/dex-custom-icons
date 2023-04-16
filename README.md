# Script
```lua
-- Change to an valid theme (example: "Green", "Blue)
getfenv(1).currentTheme = "Mono"

-- Some few modifiers to shape the explorer like you want to
getfenv(1).modfiers = {
    SearchOnType = true, -- Auto updates the explorer list when you type on the search box
    CustomColor = Color3.fromRGB(255, 255, 255), -- Change its RGB value to apply an custom color
    LocalPlayerColor = Color3.new(0.8, 1, 0.8) -- Will change the color of the local player node/button
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
