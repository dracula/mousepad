### [Mousepad](https://salsa.debian.org/xfce-team/apps/mousepad)

#### Install manually
1. Git clone this repository:
 `git clone https://github.com/dracula/mousepad.git && cd mousepad`
2. Create folder inside your $HOME folder
 `mkdir -p "$HOME/.local/share/gtksourceview-3.0/styles" `
3. Copy the dracula.xml
 `cp dracula.xml $HOME/.local/share/gtksourceview-3.0/styles`
 
Note! if mousepad doesn't recognize change `gtksourceview-3.0` to `gtksourceview-4`
