# Barb's Hitbox Module+

A lightweight, fast, and clean hitbox system for Roblox.  
Designed for fighting games, abilities, VFX triggers, and anything that needs reliable detection.

## Features
- Sphere hitboxes
- Follow-mode hitboxes
- Duration-based activation
- Max hit limit
- Hit cooldown per target
- Optional visualization
- Server-authoritative
- Easy API

## Basic Usage

```lua
local Hitbox = require(ReplicatedStorage["Barb's Hitbox"])

Hitbox.Sphere(position, radius, {
    Owner = character,
    Visualize = true,
    Duration = 0.2,
    OnHit = function(result)
        print("Hit:", result)
    end
})
```

# FREE TO USE AND EDIT.
# CREDIT IS OPTIONAL.
