# EasyScript

EasyScript создан для того, чтобы упростить разработку приложений для разрабочиков MineOS.

# CreateWindow
-----------
Input: types, x, y, width, height, other.. <br>
Return: 1 - id window <br>
Types - title, tab, fill <br>
Description: Creates a program window
Example:
```lua
local id = CreateWindow("title", 1, 1, 60, 20, "Test")

```

# GetMenuWindow
-----------
Input: Id window <br>
Return: 1 - menu window <br>
Description: Allows you to get the program menu by its ID
Example:
```lua
local id = CreateWindow("title", 1, 1, 60, 20, "Test")
local menu = GetMenuWindow(id)

```

---------
# GetWorkspaceWindow
-----------
Input: Id window <br>
Return: 1 - Workspace window <br>
Description: Allows you to get the working surface of the program window by its identifier
Example:
```lua
local id = CreateWindow("title", 1, 1, 60, 20, "Test")
local Workspace = GetWorkspaceWindow(id)

```
