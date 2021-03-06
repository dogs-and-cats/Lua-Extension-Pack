# Lua-Extension-Pack
An extension pack to impress your friends. Comes with more functions to the built in libraries. 

Each module assumes that the respective library is set to read only so new methods are created by wrapping the original library within a new table. 


Using it is easy. Just download the modules and [require](https://www.lua.org/pil/8.1.html) them. 

```lua
local math = require("/some/path/math.lua")
local string = require("/some/path/string.lua")
local table = require("/some/path/table.lua")
```
