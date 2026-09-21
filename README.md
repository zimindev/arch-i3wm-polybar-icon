🖼️ i3 / Polybar Workspace Icons

A curated collection of icons for i3, Polybar, Rofi, Dunst, and Nerd Fonts.

💡 These icons require a font that contains the corresponding glyphs. JetBrainsMono Nerd Font or another Nerd Font is recommended.

🤖 AI / Technology

󰚩  AI
󰘦  Brain
󰌆  Robot
󰭻  Bot
󰧑  Human / AI
󰅩  CPU
󰍛  CPU
  Processor
  Memory
󰘚  Activity
󰒋  System
󰢻  Server
  Server
󰣇  Linux
  Arch Linux
  Ubuntu
  Debian

💻 Programming / Development

  Code
󰨞  Code
  Terminal
󰆍  Terminal
  Terminal
  Terminal
󰅩  CPU
󰘚  Process
󰗀  API
󰅲  Script
󰈮  Programming
󰌛  Bug
  Bug
󰙨  Debug
󰐱  Git
  Git
󰊢  GitHub
  GitHub
󰏗  Package
  Package
󰏖  Package

🎨 Design / Graphics

  Palette
  Brush
󰏘  Paint
󰗇  Image
  Image
  Gallery
󰋩  Camera
  Camera
󰍉  Search / Design
󰃫  Layers
󰅣  Crop
󰙨  Design
󰉉  Vector
󰉏  Shapes
󰸘  Color

🌐 Internet / Browser

  Globe
󰖟  Browser
󰇧  Internet
󰈹  Web
  Firefox
  Chrome
  Edge
󰀂  Website
󰌘  Connection
  Link
󰛳  Network
󰈀  Network

🖥️ Desktop / Linux

  Desktop
  Computer
󰍹  Monitor
󰒋  System
󰣇  Linux
  Arch
  Ubuntu
  Debian
󰆍  Terminal
  Terminal
  Terminal
󰢻  Server
  Server
󰖩  Wi-Fi

📁 Files / Folders

  Folder
  Folder Open
  Folder
  Folder
󰉋  Folder
󰉖  Folder
  File
  File
  Document
󰈙  Document
󰂺  Notes
󰗀  File
󰈔  Archive
󰗄  Archive
󰏗  Package

🛠️ Administration / Sysadmin

  Gear
  Settings
  Wrench
  Tools
  Wrench
󰒓  Settings
󰑐  Tools
󰒋  System
󰢻  Server
  Server
󰅩  CPU
  RAM
󰍛  CPU
󰘚  Monitoring
󰀨  Power

🌐 Network / MikroTik

  Wi-Fi
󰖩  Wi-Fi
󰈀  Network
󰛳  Network
  Link
󰌘  Connection
󰅧  Router
󰒍  Router
󰣀  Ethernet
󰖩  Wireless
󰀂  Internet
  WAN
󰒗  LAN
󰒋  Server

🔐 Security

  Lock
  Key
  Unlock
󰌾  Secure
󰒃  Shield
  Shield
󰛨  Security
󰦝  Privacy
󰌆  Authentication
󰅖  Block
  Warning
  Warning
  Error
  Verified

📊 Monitoring / Statistics

  Statistics
  Graph
  Chart
󰄧  Monitor
󰍛  CPU
  CPU
  Memory
󰘚  Activity
󰓅  Monitor
󰆍  Terminal
󰅩  CPU
󰒋  System

🗄️ Server / Database

  Database
󰆼  Database
󰆼  SQL
󰒋  Server
󰢻  Server
  Server
󰅧  Cloud
󰅟  Storage
󰋊  Hard Drive
󰋊  Disk
󰍛  Database

☁️ Cloud / File Transfer

  Cloud
☁  Cloud
󰅧  Cloud
󰅟  Download
󰀃  Upload
  Download
  Upload
󰇚  Download
󰕒  Upload
󰒍  Sync
󰑐  Tools

💬 Communication

  Chat
  Chat
  Comments
󰍩  Message
󰭻  Messages
  Email
  Mail
  Send
󰇮  Inbox
󰍩  Chat
󰭻  Messages

🎮 Games

  Gamepad
󰊗  Gamepad
  Controller
󰖺  Game
󰓓  Game
  Steam

🎵 Media

  Music
  Volume
  Video
  Film
  Play
  Play
  Pause
󰝚  Music
󰎆  Music
󰕾  Volume
󰖀  Headphones

📚 Documents

  Book
  Book
  Document
  PDF
  File
󰈙  Document
󰂺  Notes
󰈙  Manual
󰈬  Clipboard
󰆏  Clipboard

⭐ Status / System

  Star
  Empty Star
  Heart
  Flag
  Info
  Warning
  Warning
  Check
  Error
  Done
󰄬  Task
  Tasks
󰅖  Close
󰅗  Add
󰐕  Plus
󰍉  Search
  Search

🖼️ Workspace Icon Sets

Minimal

󰚩  AI
  Design
  Code
  Web
  Files
  Chat
  Games
  Music

Recommended i3 Workspace Set

  Terminal
󰚩  AI
  Design
  Code
  Browser
  Files
  Chat
  Games
  Music
󰊢  GitHub

Sysadmin / Network

  Terminal
󰢻  Server
󰒋  System
󰅩  CPU
  RAM
  Database
󰖩  Wi-Fi
󰅧  Router
󰒃  Security
☁  Cloud

Development

󰚩  AI
  Code
  Terminal
󰌛  Debug
󰐱  Git
󰊢  GitHub
󰏗  Package
  Database
󰢻  Server

🧩 Example i3 Configuration

# Workspace icons
set $ws1  "1:"
set $ws2  "2:󰚩"
set $ws3  "3:"
set $ws4  "4:"
set $ws5  "5:"
set $ws6  "6:"
set $ws7  "7:"
set $ws8  "8:"
set $ws9  "9:"
set $ws10 "10:󰊢"

bindsym $mod+1 workspace number $ws1
bindsym $mod+2 workspace number $ws2
bindsym $mod+3 workspace number $ws3
bindsym $mod+4 workspace number $ws4
bindsym $mod+5 workspace number $ws5
bindsym $mod+6 workspace number $ws6
bindsym $mod+7 workspace number $ws7
bindsym $mod+8 workspace number $ws8
bindsym $mod+9 workspace number $ws9
bindsym $mod+0 workspace number $ws10

🔤 Nerd Font

Check whether JetBrainsMono Nerd Font is installed:

fc-list | grep -i "JetBrainsMono Nerd Font"

Recommended Polybar configuration:

font-0 = "JetBrainsMono Nerd Font:size=10;2"
font-1 = "Symbols Nerd Font:size=10;2"

Install on Arch Linux:

sudo pacman -S ttf-jetbrains-mono-nerd

Verify:

fc-list | grep -i "JetBrains"

🔎 Test Icons

You can test several glyphs directly from the terminal:

printf '%s\n' '󰚩 󰘦 󰌆     󰆍 󰨞 󰅩'

If an icon appears as □, ?, or an empty square, the current font does not contain that glyph.

💡 Recommended Workspace Layout

A practical 10-workspace layout for i3:

1      Terminal
2   󰚩   AI
3      Design
4      Code
5      Browser
6      Files
7      Chat
8      Games
9      Music
10  󰊢   GitHub

This layout is designed for i3 + Polybar and keeps workspace labels compact while making them easy to recognize visually.

🔗 Useful Resources

Nerd Fonts

Nerd Fonts Cheat Sheet

i3 Window Manager

Polybar

Rofi

Dunst
