## Prerequisites
For auto focus, do 
```
sudo apt install wmctrl
```

## Installation
```
nvim open_project
```
change "/path_to_project" to the folder that project.godot is in. Save and exit.
```
cp gvim /usr/local/bin/gvim
cp open_project /usr/local/bin/godot_project
```
you can replace "godot_project" with whatever alias you prefer.

In godot3, go to Editor>Editor Settings>Text Editor>External.

![editor_setting](https://github.com/TremblingInferno/gvim-project-opener/assets/99841509/b7fe38c6-d567-41a7-894c-35498f6df959)

Check "Use External Editor" on,

In Exec path, place the path to "openGvimFile.sh"

Put {file} {project} in Exec Flags
