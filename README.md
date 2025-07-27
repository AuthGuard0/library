# library

```lua
local AuthGuard = loadstring(game:HttpGet("https://raw.githubusercontent.com/AuthGuard0/library/refs/heads/main/v1.lua"))

local link = AuthGuard:getLink(): string
local success = AuthGuard:validateKey(key: string): boolean
```