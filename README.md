# SETUP

- Create a .bash_aliases file in your $HOME:
```bash
cd $HOME
nano .bash_aliases
```
- Create an ENV variable named GODOT_EXECUTABLE:
```bash
export GODOT_EXECUTABLE=$HOME/SUBDIRECTORY/Godot_v4.3-stable_mono_linux.x86_64
```
- Export your .bash_aliases in your $HOME/.profile:
```bash
cd $HOME
echo "\n" >> .profile
echo ". \"$HOME/.bash_aliases\"" >> .profile
```
- Restart your computer
---
- Create a .vscode folder inside your Godot C# project
- Copy these .json files in there
- Install C# plugins from Microsoft
- Press play
- Don't worry
- Be happy