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
anim.AnimationId = "rbxassetid://0" 
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
## More Soon Lil Bro

So Yeah This is All This Will make You From noob To Pro At Scripting You Can Make Ur own Script By Using https://pastebin.com/ or https://github.com/ and put ur own script into loadstring I think It Was Good
