




https://github.com/user-attachments/assets/b8114a33-7064-4689-b47c-f8bd302e4aa5











# BB8xfcesetup
Wallpaper Thanks to:https://www.reddit.com/r/midjourney/comments/1fw53jb/disc_jockey/

Not responsible if it breaks your system. 
BACKUP everything before making any changes. 

REQUIREMENTS & INSTALLATION
(Use the animations and the menu styles in the video with other dark themes) Skip 1 to 4 if already have these things installed...
step 1.xfce goodies packages for the default xfce plugins and widgets. 
           Plugins used are : Power Manager plugin,  Free Space Checker, Pluse Audio, Sensor plugin, System tray plugin, Actions buttons, Notificaiton plugin,  Date Time, Cpu graph, System load monitor, 
           
           Four panels are being used here.
           So use the Panel profiles app to good measure
step 2. May or may not need htop, cava and cmus(Terminal based programs.. The panel has them )

step 3. Panel profiles app to load the panelprofile without much fuss. 

step 4. Themes(ICON and gtk)
 ICONS: Fluent-dark(https://github.com/vinceliuice/Fluent-icon-theme)
 GTK: Modified Simpy Circles(shared here above in method 1)
 Custom: Whisker menu icon (also shared in the folder above(WhiskemnuCIon.... add manually from the properties menu of Whisker menu via rightclick))
 For Window Decorations use the Borderlesstheme using your Window Manager app on xfce.
 
 fonts used: 1. Exo 2. Terminus for date and time. 
 
 step 5. Copy the gtk3.css to ~/.config/gtk-3.0 folder.
 
 xfce4-panel -r or reboot for it too take effect and don't blame me if your system breaks. Please adjust the dimensions and other aspects to your taste. These configs won't may not work properly on you system. Use it at your own discretion. 
 

IMPORTANT: YOu can also disable tooltips systemwide by uncommenting the tooltips section in your ~/.config/gtk-3.0/gtk.css file manually.
To Disable the themes menu for thunar uncomment the Menu section in the gtk.css
