## Preview
### Normal
![normal](https://raw.githubusercontent.com/addy-dclxvi/diminished-tray-icons/master/preview-normal.png)
<br />
I usually only put clipit, pnmixer, nm-applet, and xfce4-power-manager in my system tray.
Like default Crunchbang/Bunsenlabs setup.

### With More Tray Icons
![full](https://raw.githubusercontent.com/addy-dclxvi/diminished-tray-icons/master/preview-full.png)
<br />
**From left to right** pnmixer, xfce4-power-manager, nm-applet, clipit, transmission-gtk, thunar (dialog).
Not a complete set, but enough for my necessity. For other available icons, just check inside the folder.
By the way, the panel I user for that preview is Fluxbox panel with 24x24 tray box size.

## How to use
- Clone this repo to *~/.icons* folder
```
git clone --depth=1 https://github.com/addy-dclxvi/diminished-tray-icons ~/.icons/Diminished
```
- (Optional) Edit the *index.theme* file

![inherits](https://raw.githubusercontent.com/addy-dclxvi/diminished-tray-icons/master/inherits.png)
<br />

Add your current GTK Icons to the *inherits* section in the first order (highest priority) if it has not been available.
It will be used as fallback. Any icons that is not covered by Diminished icons, will be taken from the icons in *inherits* section.
- Apply Diminished icons using LXAppearnce or any theme chooser do you have
