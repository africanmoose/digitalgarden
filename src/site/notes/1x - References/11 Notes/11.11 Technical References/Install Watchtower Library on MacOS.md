---
{"dg-publish":true,"dg-permalink":"WtlibOnMac","permalink":"/WtlibOnMac/","title":"Install Watchtower Library on MacOS","noteIcon":""}
---


### Summary
- Quick quide on how to install Watchtower Library on Mac OS 13.2. - ventura

### Details
- download wtlib from jw.org (ly_exe)
- install homebrew
	- run command below in terminal, enter password if prompted
	- /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
- install winetricks
	- run command in terminal
	- brew install winetricks
- install xquartz (not sure if this is required)
	- run command in terminal
	- brew install --cask xquartz
- install wine-crossover
	- run command in terminal
	- brew install --cask --no-quarantine gcenx/wine/wine-crossover
- run setup.exe
	- accept prompts to access files
	- accept default file locations
- create shortcut to wtlib.exe
	- turn on view in finder preferences to see your computer
	- in finder, turn on hidden files (command + shift + .)
	- users/(username)/.wine/drive_c/program files(x86)/watchtower/watchtower library/E/wtlibrary.exe
	- can make an alias to this for easy access
	- when you open it, allow to download updates



### References
- [general outline:](https://boleh.info/winemac/index.php?Watchtower+Library%2Fen)
	- except wine doesnt work, replace with wine-crossover
- https://github.com/Gcenx/winecx
- [home brew site](https://brew.sh)
- https://appleinsider.com/inside/macos/tips/how-to-get-started-with-wine-80-on-your-mac
- https://www.sysnettechsolutions.com/en/install-wine-macos/

