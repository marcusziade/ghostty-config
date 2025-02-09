# Ghostty Configuration

My personal Ghostty terminal configuration.

## Current Configuration

```ini
# Ghostty Terminal Configuration

# General Configuration
confirm-close-surface = false

# Font Configuration
font-family = "JetBrains Mono"
font-feature = -calt  # Disable ligatures
font-size = 12
font-synthetic-style = true

# Window Appearance
window-padding-x = 2
window-padding-y = 2
window-inherit-working-directory = true
window-theme = system
window-save-state = default

# Terminal Colors & Theme
background = #1a1b26
foreground = #c0caf5
cursor-color = #c0caf5
cursor-style = block
cursor-style-blink = true

# Standard Terminal Colors (Tokyo Night theme)
palette = 0=#1a1b26
palette = 1=#f7768e
palette = 2=#9ece6a
palette = 3=#e0af68
palette = 4=#7aa2f7
palette = 5=#bb9af7
palette = 6=#7dcfff
palette = 7=#a9b1d6
palette = 8=#414868
palette = 9=#f7768e
palette = 10=#9ece6a
palette = 11=#e0af68
palette = 12=#7aa2f7
palette = 13=#bb9af7
palette = 14=#7dcfff
palette = 15=#c0caf5

# Mouse & Selection
mouse-hide-while-typing = true
mouse-shift-capture = false
copy-on-select = false
selection-invert-fg-bg = false

# Scrollback & Performance
scrollback-limit = 10000
window-vsync = true

# Shell Integration
shell-integration = detect
shell-integration-features = cursor,sudo,title

# Clipboard Settings
clipboard-read = ask
clipboard-write = allow
clipboard-trim-trailing-spaces = true
clipboard-paste-protection = true

# Default Keybindings - Using Ctrl instead of super for Linux
keybind = ctrl+shift+c=copy_to_clipboard
keybind = ctrl+shift+v=paste_from_clipboard
keybind = ctrl+shift+n=new_window
keybind = ctrl+shift+t=new_tab
keybind = ctrl+shift+w=close_surface
keybind = ctrl+shift+q=quit
keybind = ctrl+shift+f=toggle_fullscreen

# System Integration
term = xterm-256color
desktop-notifications = true
bold-is-bright = false

# Updates
auto-update = check
auto-update-channel = stable
```

## Last Updated
2025-02-02 10:02:47 UTC
