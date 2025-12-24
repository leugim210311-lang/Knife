-- Main Settings
CONFIG = {
    -- Kill Aura Settings
    KillAura = {
        Enabled = true,
        Range = 100,           -- Detection range in studs
        Smoothness = 0.5,      -- Animation smoothness (0-1)
        AutoAttack = true,
        TargetPlayers = true,
        TargetNPCs = false
    },
    
    -- God Mode Settings
    GodMode = {
        Enabled = true,
        InvincibilityMode = "Full",  -- "Full", "Partial", "Damage_Reduction"
        HealthRegenSpeed = 50,       -- HP per second
        DamageBlockPercentage = 95   -- 0-100
    },
    
    -- Performance Settings
    Performance = {
        MaxFPS = 60,
        RenderDistance = 500,
        LagCompensation = true,
        OptimizeGraphics = true
    },
    
    -- Auto-Farm Settings
    AutoFarm = {
        Enabled = false,
        TargetResource = "Knives",
        AutoCollect = true,
        OptimalPathing = true
    },
    
    -- UI Settings
    UI = {
        ShowStats = true,
        ShowAimBox = true,
        TransparencyLevel = 0.8,
        UIScale = 1.0
    }
}
