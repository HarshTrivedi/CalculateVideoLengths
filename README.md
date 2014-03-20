Bash Video Duration Culumulator (BVDC)


PRE-REQUISITES:

Install ffmpeg and then make sure avconv command works:
sudo apt-get install ffmpeg

USAGE:

1. Put file "bvdc" in ~/.local/bin or ~/.bin. In which ever directory you put, make sure that the directory is in your PATH variable.
2. Direct your console to whichever directory you have lots of videos, you want to total the durations of, and run bvdc
3. It finds all possible videos from that and all the sub-directories and cumulates duration to give result.


WARNING:

Before calculating durations of videos, the script first of all removes the blank spaces from the names of all sub-directories and sub-file. In case, it is a harm to you make sure u make necessary changes in the code before running script in any directory.
