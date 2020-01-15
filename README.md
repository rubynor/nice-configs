nice-configs
============

put most of these in HOME dir

Except
.hound.yml - Put this in REPO HOME



# Ubuntu

Disable/change keybindings is simple, under device -> Keyboard. 
Disable hidden keybindings (using zsh I need to escape chars like [])

    gsettings list-recursively
    gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-left \[\]
    gsettings get org.gnome.desktop.wm.keybindings switch-to-workspace-left     
    gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-right \[\]

