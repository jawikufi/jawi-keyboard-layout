# jawi-keyboard-layout for Linux

1. Updates /usr/share/X11/xkb/rules/evdev.xml
$ sudo nano /usr/share/X11/xkb/rules/evdev.xml
add the data in usr_share_X11_xkb_rules_evdev.xml after <layoutList>:

2. Add /usr/share/X11/xkb/symbols/jawimy
$ mv usr_share_X11_xkb_symbols_jawimy jawimy
$ sudo cp jawimy /usr/share/X11/xkb/symbols

3. Go to Settings > Keyboard > + Add Input Source... > {tap on 3-dots} > Language or country: Jawi > Other > Jawi (MY) > Add

4. Reboot your machine.

5. Select Jawi(MY) as your current keyboard layout.

6. Ready to be used the Jawi keyboard layout in the app such as text editor, doc, etc.
