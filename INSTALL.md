### [Mousepad](https://salsa.debian.org/xfce-team/apps/mousepad)

#### Install manually
1. Git clone this repository
```text
git clone https://github.com/dracula/mousepad.git && cd mousepad
```
3. Create a folder inside your $HOME folder
```text
mkdir -p $HOME/.local/share/gtksourceview-3.0/styles
```
<br>If you're installing Mousepad using Flatpak the directory is in `~/.var/app/org.xfce.mousepad/data/gtksourceview-4/styles`

4. Copy the dracula.xml
```text
cp dracula.xml ~/.local/share/gtksourceview-3.0/styles
```
5. Go to Edit > Preferences > View > Color scheme > Dracula <br>

Note!
- If Mousepad doesn't recognize change `gtksourceview-3.0` to `gtksourceview-4`
