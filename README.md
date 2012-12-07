=======================================================================
LINUX MINT 14
=======================================================================

NEMO
----
- Move breadcrumb/location_entry to a new toolbar within the right view pane (similar to Caja)
- Check MD5
- Create an actions API, which reads desktop files in /usr/share/nemo/launchers. A action is basically a text file which defines a name, an icon, an executable and which file extensions nemo shows the action for when the file is right-clicked. A typical example of this would be a "Edit tags" action which would apply to *.mp3 files. 

MDM
---

Cinnamon 1.6
------------

Mint Tools
----------
- Improve the software manager (layout, look and feel)

=======================================================================
LINUX MINT 15
=======================================================================

Cinnamon 1.8
------------
- [dalcde] Desklets
- Ability for cinnamon-settings to browse/install/remove/update themes/applets/extensions/desklets remotely
- Magic bumpmaps
- Configurable color schemes for themes

=======================================================================
R&D
=======================================================================
- [mtwebster] Give Cinnamon its own screensaver
- Replace or patch gedit
- Code a new driver manager for both Ubuntu and Debian (in replacement for Jockey)
- [fred] (LMDE-specific) Create a mint-lmde-mirrors package which contains the list of LMDE mirrors. Make mintupdate-debian depend on it. Give it a postinst which finds the fastest mirror and asks the user whether or not to switch his/her sources to it.