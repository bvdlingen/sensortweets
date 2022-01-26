# sensortweets

Yet another twitterbot ... This simple bot is doing a few things:

1. Fetching a daily png image from graphana (a public graphana instance without image rendering functionality)

2. posting it to twitter

3. The final script is meant to be scheduled using cron or a systemd timer.

requirements:
- nodejs
- npm
- capture-website-cli
- python
- systemd or cron
- system sandboxing should be enabled

Only docker is needed for the alternative script 

Local initiative @ partij voor de dieren Utrecht, The Netherlands. 
Feel free to copy and re-use. Everything is at least GPL licensed. Our scripts are MIT licensed.
https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licences
