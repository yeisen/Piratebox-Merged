## Piratebox for laptop (eeePc) script collection   WITH LIGHTTPD
##   created by Matthias Strubel (matthias.strubel@aod-rpg.de)  2014-01-17
##   licenced by GPL-3 ;; please feel for improvements or feedback :)
## 
## Yeisens edits:
## original source: 
## https://github.com/PirateBox-Dev/PirateBoxScripts_Webserver
## merged with:
## https://github.com/Nargren/PirateBox
## Nagaren's placed in /piratebox/share as CONTENT_DESIGN1.0 and CONTENT_DESIGN2.0 
## Most of CONTENT_DESIGN1.0 copied into /piratebox/share/content My currently used.
## edited /piratebox/install.sh dependancies to include "droopy iw net-tools wireless-tools php-cli php-readline"
## original piratebox/share/index.html edited down to just the chat box and renamed chat.html, Nagaren's deleted
## /piratebox/share/index.html from Nagaren edited: 
## Forum link to /cgi-bin/forest.py instead of /board/
## Home image edited, box stats replaced with mine.
## ln -s /media/sda3/Shared /opt/piratebox/share/Shared
## my shared folder points to my sda3 partition Shared folder
## rm /piratebox/forumspace
## mkdir /piratebox/shared/forumspace
## edit /piratebox/conf/irc/motd.txt
## added /piratebox/init.d/miniircd.sh custom start up command. 
