shell-scripts
=============

Linux shell scripts

memstat.sh: From nixsavy. Script calculates memory usage for all processes on linux machine. Will use "PSS" and "Private" data from /proc/<PID>/smaps. See http://stackoverflow.com/a/13754307/1619146 for more info.
This version does not use paste or bc to do mathematical operations but awk instead. I do not have a lot of awk experience so the use is rather simply implemented.
Big thanks to nixsavy for creating the original script.
