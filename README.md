# My Sublime Text 3 Preferences

They're really not that interesting - I promise...

## How does this thing work?

	# Back up existing settings
	cd ~/Library/Application Support/Sublime Text 3/Packages
	cp User User.bak

	# Replace settings folder with folder from repo
	rm -rf User && ln -s /path/to/repo/User/

	# Re-import non-settings files
	ls | grep -v .sublime-settings | xargs -I {} cp {} .