Terminal emulator


#Open Vim Terminator By Default

#Open vim.desktop file located in /usr/share/applications/

#Open terminal and paste the command

sudo nano /usr/share/applications/vim.desktop

#Change terminal=false And Change Exec=terminator -e "vim %F"

Exec=terminator -e "vim %F"

Terminal=false
