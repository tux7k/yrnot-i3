# yrnot

a simple weather program and logger to get data from the MET using yr.no. This is my personal script so there might be some things specific to my system in here. You can remove those/replace those. Please use cron jobs to log.

## specs
- notifications about rain/snow/sleet conditions in the next hour (cron)
- terminal forecast
- simple forecast for status bars
- force grab data (no cache)
- cache logger for speeding up times of command
- fun emojis mapped to each conditions
- all available data layed out and formatted beautifully

## how to use

use the plain command to get nice terminal weather data.
add -s flag to simplify for status lines.
add -f flag IN THE FIRST ARGUMENT to force no cache.
add -n flag in order to get a notification for weather conditions in the next hour.

use yrnot_log to log/cache data (create a cron job for this)

## configuration file

- create a configuration file at ~/.config/yrnot/cfg.
- create a variable called "loc" with your yr.no url location (explained in example cfg)
- create a variable called "prefbrow" with your preffered browser command in it
- create a "lat" and "lon" command with, you guessed it, your latidute and longidute.

## credits
- yr.no team
- nrk
- MET.no
- me (tux@nuk3.org)
