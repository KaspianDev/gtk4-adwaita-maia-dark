![image](https://user-images.githubusercontent.com/34658474/173929672-06b7920b-d533-4480-947f-bfebc50c931e.png)
# gtk4-adwaita-maia-dark

## What does it do?
This repo is a workaround for GTK4 maia adwaita theme. GTK4 does not play well with out current maia theme so I created a little bit modificated version of the gnomes theme with green tint and symlink to the original maia for GTK3 apps.

## Usage
Simple. Add this to your ~/.themes directory and set `GTK_THEME` variable to `gtk4-adwaita-maia-dark`.
This was mainly created for flatpak but will work for everything else.

You need to run this command for flatpak to work.
```
sudo flatpak override --env=GTK_THEME=gtk4-adwaita-maia-dark
```
And of course let flatpak access your .theme folder.
```
sudo flatpak override --filesystem=$HOME/.themes
```
You also need the compact version of dark adwaita maia instaled (it is installed by default on manjaro).

## Credit

All the credit goes to GNOME for adw-dark theme and [Manjaro team](https://gitlab.manjaro.org/packages/community/themes/adwaita-maia).
This theme originally comes from [libadwaita](https://gnome.pages.gitlab.gnome.org/libadwaita/).
