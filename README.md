# osuModeDeleter

!!!!!!!!!!!!!!
DISCLAIMER: BACK UP YOUR osu!/Songs FOLDER

I don't take any responsibility, if the script deletes something that isn't intended.


<p>The script deletes all beatmaps in osu! except specified gamemodes.<\p>
Script uses Python3 and it's built in libraries.
I only tried on Windows 10.

Usage:
Place "mode_deleter.py" in your osu/Songs directory or use path argument (see below)

python mode_deleter.py {gamemodes} {path}

gamemodes: gamemode's number which you want to KEEP separated by ; .Example normal osu! is: 0 (Check other beatmap modes by opening it with notepad)
path(OPTIONAL): Your osu!/Songs path with forward facing slashes. 

EXAMPLE:
You put the script in the Songs folder:
  python mode_deleter.py 0;1
You assing the path as an argument:
  python mode_deleter.py 0;1 C:/Users/user/AppData/Local/osu!/Songs

