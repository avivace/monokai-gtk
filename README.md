# monokai-gtk
A GTK2 theme, forked from [arc-theme](https://github.com/horst3180/arc-theme), which gives a uniform look to applications using the Monokai color scheme.

## Installation
Install the theme cloning this repo (`git clone https://github.com/avivace/monokai-gtk`) and moving it into `/usr/share/themes`. You can now enable it system-wide.

You can enable GTK themes only for some applications: launch them in this way: `GTK2_RC_FILES=/usr/share/themes/monokai-gtk/gtk-2.0/gtkrc your-application` (GTK2) or `GTK_THEME=your-theme your-application` (GTK3). Change the `exec` parameter in your desktop launcher to save this preference in your DE.

![](http://i.imgur.com/UwEmPnP.png)
![](http://i.imgur.com/TGX3LCv.png)

In these screenshots I'm on debian testing, KDE Plasma 5.8.2, KDE Frameworks 5.27.0 using Arc Dark as desktop theme. The UI font is Helvetica Neue. The Sublime Text 3 theme is Boxy.