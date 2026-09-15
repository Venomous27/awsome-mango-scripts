# A Simple bash script for enabling/disabling monitor for multi-monitor setups

In the `monitor.sh` change the monitor names according to your monitor's name.<br>
Use `wlr-randr` to get your monitor's name, make, model, and serial.<br>
You can also add more options according to your need.<br>

Then make it executable using:<br>
`chmod +x "script's/path"`

To use it with MangoWM<br>
Add keybind and windowrule in your `mango's config`. Don't forget to change path of script in keybind :p<br>

Keybind:<br>
`bind=SUPER,p,spawn_shell,kitty --title="Floating-Monitor" -e ~/superior-dotfiles-mango/scripts/monitor.sh`

Windowrule:<br>
`windowrule=title:Floating-Monitor,width:300,height:200,isfloating:1`
