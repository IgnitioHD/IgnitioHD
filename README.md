local A_1 = 
{
    [1] = getrenv()._G.Pass, 
    [2] = "Reset"
}
local Event = game:GetService("ReplicatedStorage").Remotes.Functions


-- Idk who just random custom by TryIgnitio 
-- MOVES LIST -- 
-- [Z] - Random Cool Combo 1 
-- [X] - Lighting Ground
-- [C] - Kick thing
-- [V] - Cool Combo
-- [T] - Bravery Slash
-- (Friendly reminder to do not spam moves as bc it can kick you)
-- Spawn in
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, true)
game.Players.LocalPlayer.PlayerGui.CharacterSelection.Character.Value = "Chara"
wait(2)
-- Spawned in
game.Players.LocalPlayer.Character.Head.Voice:Destroy()
game.Players.LocalPlayer:WaitForChild("StarterPlaylist")
game.Players.LocalPlayer.StarterPlaylist["1Megalo Strike Back"]:Destroy()
local Sound = Instance.new("Sound")
Sound.Parent = game.Players.LocalPlayer.StarterPlaylist
Sound.Volume = 1
Sound.Playing = true
Sound.Looped = true
Sound.SoundId = "rbxassetid://6665513699" 
Sound.Name = "no"
-- Some important shit
local Player = game.Players.LocalPlayer
local Backpack = Player.Backpack
Player.Character.HateArm:Remove()
Player.Character.HeartLocket:Remove()
game.Players.LocalPlayer.Character["Karma"]:Destroy()
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.StaminaBar:Destroy()
game.Players.LocalPlayer.Character["HateMode"]:Destroy()
game.Players.LocalPlayer.Character["FullHateMode"]:Destroy()
local Anim = Instance.new("Animation") Anim.AnimationId = "rbxassetid://7005139602" local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim) k:Play() k:AdjustSpeed(1)
game.Players.LocalPlayer.Backpack.Main.WalkSpeed.Value = "66"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light1.AnimationId = "rbxassetid://4456890962"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light2.AnimationId = "rbxassetid://4456894133"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light3.AnimationId = "rbxassetid://4348287123"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light4.AnimationId = "rbxassetid://4348301706"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light5.AnimationId = "rbxassetid://4456890962"
game.Players.LocalPlayer.Backpack.Main.CharaMoves.ModuleScript.Animations.BladesCombat.Light6.AnimationId = "rbxassetid://4456901030"
-- intro
-- (No intro rn)
-- [Cool Combo] [Z] Start
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "z" then
local Anim = Instance.new("Animation") Anim.AnimationId = "rbxassetid://7010191554" local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim) k:Play() k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.SpGrab,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.07, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Hurt,
				["Damage"] = 1
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(1.3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.MoveAnimations.OnTheGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.07, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.37)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.SpearHurt,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.07, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.85)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.2,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.GutHurt,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 40, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.AreaAttackBurst,
				["Damage"] = 40
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
end
end)
-- [Cool Combo] [Z] End
-- [Cool Combo 2] [X] Start
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "x" then
local Anim = Instance.new("Animation") Anim.AnimationId = "rbxassetid://7003950381" local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim) k:Play() k:AdjustSpeed(1)
wait(0.3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback3,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 70, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.ShockerBreakerHit,
				["Damage"] = 40
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(1.27)
local Anim = Instance.new("Animation") Anim.AnimationId = "rbxassetid://7007281153" local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim) k:Play() k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback3,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.3, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 40
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
end
end)
-- Cool combo 2 end
-- Cool combo 3 Start
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "c" then
local Anim = Instance.new("Animation") Anim.AnimationId = "rbxassetid://7007281153" local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim) k:Play() k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback3,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.3, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 40
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
end
end)
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "v" then
local bravery = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "KnifeProjectileOrange",
        [3] = "Spawn",
        [4] = Vector3.new(-7.6329288482666, 1.0000152587891, -263.52746582031)
    }
}

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://3816275001"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.SpGrab,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.HeartForm2,
				["Damage"] = 10
    }
}
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(1)
k:Stop()
wait(0.2)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5858687214"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.1,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback1,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 100, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit2,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(1)
k:Stop()
wait(1)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5871399342"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Stunned,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Stab,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.5)
k:Stop()

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5667194069"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Stunned,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Stab,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.3)
k:Stop()

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5667196296"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Stunned,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Stab,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.3)
k:Stop()

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5667206665"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Stunned,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Stab,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
k:Stop()
wait(0.5)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5667210178"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "YellowHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.InGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, PlayerposZ),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
k:Stop()
wait(0.2)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://6998858440"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "YellowHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.InGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(PlayerposX, 0.1, PlayerposZ),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit,
				["Damage"] = 10
    }
}
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.1)
k:Stop()
wait(0.1)
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://6998858440"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "YellowHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.InGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(PlayerposX, 0.1, PlayerposZ),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit,
				["Damage"] = 10
    }
} 
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.1)
k:Stop()
wait(0.2)
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://6998858440"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "YellowHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.InGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(PlayerposX, 0.1, PlayerposZ),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit,
				["Damage"] = 10
    }
}
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.1)
k:Stop()
wait(0.3)
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://6998858440"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(3)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 0.3,
				["Type"] = "Knockback",
				["HitEffect"] = "YellowHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.InGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(PlayerposX, 0.1, PlayerposZ),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit,
				["Damage"] = 10
    }
}
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.1)
k:Stop()

wait(0.7)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://3816275001"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(2)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.SpGrab,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 1, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Ping,
				["Damage"] = 10
    }
}
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.7)
k:Stop()

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.MoveAnimations.OnTheGround,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.07, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.50)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Normal",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.SpearHurt,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.07, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Knockback,
				["Damage"] = 10
    }
}

game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.6)
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://5667483477"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(2)
	local args = {
			[1] = getrenv()._G.Pass,
			[2] = game:service("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value,
			[3] = {
				["HitTime"] = 2.5,
				["Type"] = "Knockback",
				["HitEffect"] = "BoneHitEffect",
				["VictimCFrame"] = CFrame.new(Vector3.new(957.38525390625, -2.7168080806732, 271.31875610352), Vector3.new(0.90182185173035, 0.0016235302900895, 0.43210506439209)),
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback1,
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(100, 0, 0),
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.SummonScythe,
				["Damage"] = 40
    }
}
wait(0.2)
game:GetService("ReplicatedStorage").Remotes.Damage:InvokeServer(unpack(args))
wait(0.2)
k:Stop()

game:GetService("ReplicatedStorage").Remotes.CharaMoves:InvokeServer(unpack(bravery))
end
end)
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "t" then
local A_1 = 
{
	[1] = getrenv()._G.Pass, 
	[2] = "KnifeProjectileOrange", 
	[3] = "Spawn", 
	[4] = Vector3.new(-27.4101448, 0.400001317, -197.415451)
}
local Event = game:GetService("ReplicatedStorage").Remotes.CharaMoves
Event:InvokeServer(A_1)
local security = game.ReplicatedStorage.RemoteSecurity["Noob382"]

end
end)
-- Cool combo 3 end 
--Second phase

game.Players.LocalPlayer:WaitForChild("DeathPlaylist")
game.Lighting.Bloom.Intensity = 1
game.Lighting.Bloom.Size = 56
game.Lighting.Bloom.Threshold = 4
game.Lighting.Blur.Size = 6
game.Lighting.ColorCorrection.Brightness = 0
game.Lighting.ColorCorrection.Saturation = 0
game.Lighting.ColorCorrection.TintColor = Color3.fromRGB(255,255,255)
game.Lighting.Brightness = 6
game.Lighting.ClockTime = 12
wait(3)
Event:InvokeServer(A_1)
wait(1)
while wait(1) do
game.Players.LocalPlayer.Character.Humanoid.Health = "200"
end
game.Players.LocalPlayer.DeathPlaylist["1Megalo Strike Back"]:Destroy()
local Sound = Instance.new("Sound")
Sound.Parent = game.Players.LocalPlayer.DeathPlaylist
Sound.Volume = 1
Sound.Playing = true
Sound.Looped = true
Sound.SoundId = "rbxassetid://2471965157" 
Sound.Name = "yes"
wait(0.033)
local A_1 = 
	{
		[1] = getrenv()._G.Pass,
		[2] = "Blocking", 
		[3] = true
	}
local Event = game:GetService("ReplicatedStorage").Remotes.Functions
Event:InvokeServer(A_1)
local A_1 = 
	{
		[1] = getrenv()._G.Pass,
		[2] = "Chatted", 
		[3] = "Heh heh heh.", 
		[4] = Color3.new(0.5,0,0)
	}
local Event = game:GetService("ReplicatedStorage").Remotes.Events
Event:FireServer(A_1)
wait(1.5)
local A_1 = 
	{
		[1] = getrenv()._G.Pass,
		[2] = "Chatted", 
		[3] = "I guess i can stop holding back.", 
		[4] = Color3.new(0.7,0)
	}
local Event = game:GetService("ReplicatedStorage").Remotes.Events
Event:FireServer(A_1)
local A_1 = 
{
	[1] = getrenv()._G.Pass, 
	[2] = "SpecialHell2", 
	[3] = "Spawn", 
	[4] = Vector3.new(-27.4101448, 0.400001317, -197.415451)
}
local Event = game:GetService("ReplicatedStorage").Remotes.CharaMoves
Event:InvokeServer(A_1)
local security = game.ReplicatedStorage.RemoteSecurity["Noob382"]
game.Players.LocalPlayer.Backpack.Main.WalkSpeed.Value = "66"
-- Actual death scene
local plr = game:GetService('Players').LocalPlayer
repeat wait() until game.Players.LocalPlayer.Character.Humanoid.Health <= 0
if dead == true then return end
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://4460182501"
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(1)
  plr:WaitForChild("DeathPlaylist")
  plr.DeathPlaylist["1Megalo Strike Back"]:Destroy()
  local Sound = Instance.new("Sound")
  Sound.Parent = plr.DeathPlaylist
  Sound.Volume = 1
  Sound.Playing = true
  Sound.Looped = true
  Sound.SoundId = "rbxassetid://1368902987" 
  Sound.Name = "oh no i die"

-- End of script noob
