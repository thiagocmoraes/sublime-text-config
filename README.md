sublime-text-config
===================

Instructions to config Sublime Text 2 according to my preferences

1. Install Package Control
	- Install Sidebar Enhancements
	- Install Bracket Highlighter (to emphasize tags)
	- Sublime Linter
		SublimeLinter-pep8

2. Copy the theme files to the Packages/User/Themes folder. Custom themes will appear separatedly from the default ones
	- Currently there's a Cobalt and a Monokai variant which highlight XML tags

Copy files from instructions below to "Packages/User/" folder 

3. Use keymap to change ctrl+tab behavior: remove "_in_stack" from commands
4. bh_core.sublime-settings makes Bracket Highlighter work (only works on themes which have a color set for tags)
	- Currently only configured for XML tags

5. Copy the file "Default.sublime-theme" to "Packages/User" folder