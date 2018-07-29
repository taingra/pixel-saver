Pixel Saver Simplifed
===========

Pixel Saver Simplifed is an extension for Gnome Shell hides the title bar of
maximized window. It is especially interesting for small screens, but MOAR
pixels for your apps is always good !

For applications using the modern GTK header bar there are no space savings to
achieve a uniform appearance.

It is currently almost 100% the same code as Pixel Saver, minus a few files. Pixel
Saver is largely inspired by [bios and mathematicalcoffee's Window Buttons Extension](https://github.com/mathematicalcoffee/Gnome-Shell-Window-Buttons-Extension) and [mathematicalcoffee's maximus extension](https://bitbucket.org/mathematicalcoffee/maximus-gnome-shell-extension) and
some code come from there. You may want to check theses out, especially if you
want something more configurable.

Installation
------------

Maybe I will put it into the extension store someday for conviencce.

You can also follow these simply instruction for manual installation :

    git clone https://github.com/taingram/pixel-saver.git
    cd pixel-saver
    # Get the last released version
	git checkout 1.10
    # copy to extensions directory
    cp -r pixel-saver@taingram.org -t ~/.local/share/gnome-shell/extensions
    # activate
    gnome-shell-extension-tool -e pixel-saver@taingram.org

For code changes to become effective, you might need to reload GNOME Shell
by pressing <kbd>Alt</kbd> + <kbd>F2</kbd> and entering <kbd>r</kbd> .

### Dependencies

Pixel Saver depends on Xorg's xprop and xwininfo utilities. If not already
present on your system, these can be installed using:

* Debian/Ubuntu: `apt install x11-utils`
* Fedora/RHEL: `dnf install xorg-x11-utils`
* Arch: `pacman -S xorg-xprop`

Configuration
-------------

Fork this repo and hack away.

Screenshots
-----------

When you maximize the window, the title bar is no longer there. That's it, no
buttons added to title added to the to panel.
