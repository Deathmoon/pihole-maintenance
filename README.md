# pihole-maintenance
Script that runs via a cron job post install as as maintenance routine

Make File Executable
sudo chmod +x pihole_maintain.sh

Execute Weekly
crontab-e 0 0 * * 1 sudo bash /home/pi/pihole_maintain.sh
