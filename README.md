# makemkv-autorip-script
A script for auto ripping movies using makemkv

This script can be auto executed when the BluRay drive is accessed by using incrontab.
See here: http://linux.die.net/man/5/incrontab

For example, if your drive is '/dev/sr0', you can execute the script with adding the following line.

/dev/sr0 IN_ACCESS,IN_NO_LOOP ripmovie
