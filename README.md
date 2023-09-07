# My Czech programmer keyboard

just simply put `ce` into `/usr/share/X11/xkb/symbols/` and then
```setxkbmap -layout ce```
and if you don't like it make your own.

Oh and you'll need a keypad.
Keypad supremacy.

## Instalation
```bash
# cd /usr/share/X11/xkb/symbols/
# wget wget https://raw.githubusercontent.com/3top1a/Czechish-programing-keyboard/main/ce
$ setxkbmap -layout ce

```

i3 config
```i3
# ce
bindsym $mod+equal    workspace  $ws1
bindsym $mod+ecaron   workspace $ws2
bindsym $mod+scaron   workspace $ws3
bindsym $mod+ccaron   workspace $ws4
bindsym $mod+rcaron   workspace $ws5
bindsym $mod+zcaron   workspace $ws6
bindsym $mod+yacute   workspace $ws7
bindsym $mod+aacute   workspace $ws8
bindsym $mod+iacute   workspace $ws9
bindsym $mod+eacute   workspace $ws10

bindsym $mod+Shift+equal    move container to workspace  $ws1
bindsym $mod+Shift+ecaron   move container to workspace $ws2
bindsym $mod+Shift+scaron   move container to workspace $ws3
bindsym $mod+Shift+ccaron   move container to workspace $ws4
bindsym $mod+Shift+rcaron   move container to workspace $ws5
bindsym $mod+Shift+zcaron   move container to workspace $ws6
bindsym $mod+Shift+yacute   move container to workspace $ws7
bindsym $mod+Shift+aacute   move container to workspace $ws8
bindsym $mod+Shift+iacute   move container to workspace $ws9
bindsym $mod+Shift+eacute   move container to workspace $ws10
```
