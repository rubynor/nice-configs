nice-configs
============

put most of these in HOME dir

    cd
    mv .gitconfig .gitconfig-old
    wget https://raw.githubusercontent.com/rubynor/nice-configs/master/.gitconfig
    wget https://raw.githubusercontent.com/rubynor/nice-configs/master/.gitignore_global
    
    #Change your NAME and other
    nano .gitconfig 

# Ubuntu

Disable/change keybindings is simple, under device -> Keyboard. 
Disable hidden keybindings (using zsh I need to escape chars like [])

    gsettings list-recursively
    gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-left \[\]
    gsettings get org.gnome.desktop.wm.keybindings switch-to-workspace-left     
    gsettings set org.gnome.desktop.wm.keybindings switch-to-workspace-right \[\]

