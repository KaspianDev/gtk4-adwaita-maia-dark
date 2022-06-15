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
