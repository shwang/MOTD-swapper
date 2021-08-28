MOTD switcher.

## Installation
Clone this repo to `~/.motd`, and replace "/home/shwangster/.motd" everywhere
with "/home/$YOU/.motd"/". (You can't just use `~/.motd` here because the
crontab needs to run from root to write to /etc/motd.)

### Now let's install a root crontab. 

Copy the contents of `./crontab` to `sudo crontab -e`.
