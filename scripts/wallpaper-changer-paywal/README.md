# A Simple bash script for changing wallpaper with pywall for generating color pallate

Needed dependencies: awww, fzf, pywal

Make sure wallpapers are in "~/Pictures/Wallpapers/"

Then make it executable using:<br>
`chmod +x "script's/path"`

To use it with MangoWM<br>
Add keybind and windowrule in your `mango's config`. Don't forget to change path of script in keybind :p<br>

Keybind:<br>
`bind=SUPER,w,spawn_shell,kitty --title="Floating-Wallpaper" -e ~/superior-dotfiles-mango/scripts/wallpaper.sh`

Windowrule:<br>
`windowrule=title:Floating-Wallpaper,width:700,height:500,isfloating:1`
