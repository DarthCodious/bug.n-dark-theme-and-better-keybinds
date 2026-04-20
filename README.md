# bug.n-dark-theme-and-better-keybinds
Like the title says, I've been using Bug.N on Windows 10 and wanted to upload my Config file. Main changes are a black toolbar, red line indicators for virtual workspaces that are in use, and better keybinds. 

#### You still need to download and install bug.n separately from fuhsjr00 on github: https://github.com/fuhsjr00/bug.n 

Then just backup your config file and drop the one I've provided in. The config file for me was stored in: 

c: / users / your windows username / bug.n / src / config.ahk 

but YMMV. 

Example keybinds: Alt+1 now switches you to the virtual workspace #1. This is a better one handed approach than the defaults. This works for all workspaces 1-9 so Alt+7 would take you to workspace #7. 

To send a specific program (like photoshop) to a workspace, you press Alt + the letter directly under the number row. Workspaces 1-9 are the Q through O letters respectively. So Alt+Q sends notepad to workspace 1. And Alt+1 takes you there. 

#### HERE ARE ALL OF THE OTHER USEFUL KEYBINDS FOR BUG.N I'VE NOTED. SOME ARE DEFAULTS, SOME ARE CUSTOM FROM MY CONFIG FILE: 

VIEW ORGANIZATION ideas:
Chrome / primary 
Any
Notes
Work tab: VSCode / neovim (macOS Xcode) / PS / LR / Davinci. Essentially the work tab. 
YouTube
Movie
Videogame
Discord (or push to second monitor)
Keybinds list for bug.N or similar


bug.n Useful keybinds: 

Swap stack from left / right: change the position of the stack (the secondary window area) from one side to the other is Win + Ctrl + Enter

reload bug.n (Ctrl + Win + R)

Win+ Shift + down arrow: rotates tile to other positions 

Entire layout: 
Win + F = set entire view to float. win +  T(tile) or M(monocle layout) same
Windows + period. : swap monitor focus 

Layouts:
WIN + CTRL + T = swap from horizontal to vertical stacking etc. should change everything in the view you’re in. 
WIN + T = set tile layout 
Win + M = set monocle layout
Win + F = set float layout


Individual Programs (e.g. discord or notepad)
Windows + shift + period. : swap current app over to other monitor
Win + Space = show/hide windows bottom toolbar 
WIN + Shift + X = maximize window 
Win + C = close window/tile. you can use this to close phantom tiles after using win + down to cycle through the open tiles. 
Win  + shift + enter = resize current active window to 1st pos in window list of the view. 
Win + Shift + down / up arrow = move active window to previous or next position
Win + Shift + → --< right or left arrow will tweak the border size / border spacing of all the open apps / tiles. 
Win + Tab = toggle previously set layout. 
Win + right or left arrow: change size of master area in active view. 
Win + Down = jump to / activate next window in active view. Win + up activates previous window in the active view. 
WIN + Y = bug.n GUI pullup. hit esc (capslock on nuphy) to exit menu. 
WIN + space hides and shows windows bar and does other stuff too

Workspaces:
ALT + 1-9 = pull up the virtual view of choice. 
ALT + Q-O = send current program to that virtual workspace. 

Win+Ctrl+Down (or up) arrow = shrink/grow the workspace “blocks quantity” down to 1x1. sometimes this fixes windows stuck in horizontal position. 

---
General syntax used by documentation (and code?):
! Alt
^ Ctrl
Hashtag: left windows key
Shift

