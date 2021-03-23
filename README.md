# Restore i3 workspaces with load screen

Here I present the method I use to beautify the process of restoring the i3 workspaces that are saved when I closed my session. I use <a href=https://github.com/JonnyHaystack/i3-resurrect> i3-resurrect </a> to save and restore the windows in workspaces, but I didn't like the continuous spawning of black windows, so I created a script to "cover" this process. I archieved that thanks to <a href=https://github.com/elkowar/eww>eww</a>. 

## Dependencies
<ul>
<li> i3-resurrect
<li>eww
<li>picom-jonaburg-git (see picom config to get the blur effect)
</ul>

## Usage

Simply add the script `rest-ws-i3` to your i3 config to autostart it on login if you want to restore your saved workspaces. I usually save them on logout, reboot and poweroff. 

## Demo


https://user-images.githubusercontent.com/54718071/112203081-6a8f2c80-8c12-11eb-8a83-926c3d78af4e.mp4


