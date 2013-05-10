## Create Second Crack Draft from Pinboard Pins ##

To run, add `* * * * * sudo python /path/to/pin_draft.py` to crontab. The script will loop 18 times, which takes about a minute then die. Cron will trigger another instance, so it is essentially always running.