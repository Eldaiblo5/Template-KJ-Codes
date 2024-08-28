# 🔴 KJ TEMPLATES CODES

## Play Animation And Sound
```lua
local player = game.Players.LocalPlayer
repeat wait() until player.Character.Humanoid 
local humanoid = player.Character.Humanoid 
local character = game.Players.LocalPlayer.Character or game.Players.LocalPlayer.CharacterAdded:Wait() 
local UserInputService = game:GetService("UserInputService") 
debounce = false -- Activate debounce 
local anim = Instance.new("Animation") 
anim.AnimationId = "rbxassetid://PUT_UR_ANIMATION_ID" 
local playAnim = humanoid:LoadAnimation(anim) 
anim.AnimationId = "rbxassetid://0" 
local Sound = Instance.new("Sound") 
Sound.Parent = character 
Sound.SoundId = "rbxassetid:/PUT_UR_SOUND_ID" 
Sound.Playing = true 
spawn(function() 
wait(1) 
debounce = true 
end) 
playAnim:Play() 
playAnim:AdjustSpeed(0.3) 
 wait(0.3) 
playAnim:AdjustSpeed(1) 
local Players = game:GetService("Players") 
local Character = Players.LocalPlayer.Character or Players.LocalPlayer.CharacterAdded:Wait() 
local animationPlayed = false -- Flag to track if the animation has already been played
```
Only Animation:
```lua
    		local player = game.Players.LocalPlayer
        repeat wait() until player.Character.Humanoid 
        local humanoid = player.Character.Humanoid 
        local character = game.Players.LocalPlayer.Character or game.Players.LocalPlayer.CharacterAdded:Wait() 
        local UserInputService = game:GetService("UserInputService") 
       debounce = false -- Activate debounce 
        local anim = Instance.new("Animation") 
        anim.AnimationId = "rbxassetid://PUT_UR_ANIMATION_ID" 
        local playAnim = humanoid:LoadAnimation(anim) 
        anim.AnimationId = "rbxasset://0"
        wait(1) 
        debounce = true 
        end) 
        playAnim:Play() 
        playAnim:AdjustSpeed(0.3) 
        wait(0.3) 
        playAnim:AdjustSpeed(1) 
        local Players = game:GetService("Players") 
        local Character = Players.LocalPlayer.Character or Players.LocalPlayer.CharacterAdded:Wait() 
        local animationPlayed = false -- Flag to track if the animation has already been played
```

## vfx Code
```lua
Bruh
```

## Stop vfx and script after 3 sec
```lua
wait(0.3)
Script.Disable
```

# • character Stuff
Like When You Click "Character" DropDown
You will See Some characters on character list and Custom One You Made
## Create Character On Character List
```lua
Ok
```

## Remove All Moveset
```lua
Ok
```
## Put New Moveset [Should Use "remove all moveset" First]
```lua
Bro
```

So Yeah This is All This Will make You From noob To Pro At Scripting You Can Make Ur own Script By Using https://pastebin.com/ or https://github.com/ and put ur own script into loadstring I think It Was Good
