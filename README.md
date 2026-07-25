# Sealz.UI
Interface Suit for Roblox. Ultrasmooth, Mobile Friendly.


<img width="434" height="328" alt="image" src="https://github.com/user-attachments/assets/22061604-01b9-4e31-991c-ae83d3c773d4" />

# 📩 Installation
```lua
local Sealz = loadstring(game:HttpGet("https://raw.githubusercontent.com/4lpaca-pin/Sealz/refs/heads/main/source/source.luau"))();
```

## ⚙️ Configuration
```lua
local Sealz = loadstring(game:HttpGet("https://raw.githubusercontent.com/4lpaca-pin/Sealz/refs/heads/main/source/source.luau"))({
  -- Path to Icon file
  Icons = {
    Type = "Asset",
    Data = "rbxasset://LuaPackages/Packages/_Index/BuilderIcons/BuilderIcons/BuilderIcons.json"
  },

  -- Custom Signal Library
  SignalLibrary = {
    Type = "Url",
    Data = "https://raw.githubusercontent.com/4lpaca-pin/Sealz/refs/heads/main/source/signal.luau",
    Name = "Signal.luau",
  },

  -- Fonts
  Fonts = {
    Primary = Enum.Font.RobotoMono,
    Second = Enum.Font.RobotoMono
  },

  -- Accent Color of UI
  AccentColor = Color3.fromRGB(255, 94, 97)
});
```
