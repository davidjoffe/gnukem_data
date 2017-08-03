# data subfolder
This is the 'data' subfolder for this game: https://github.com/davidjoffe/dave_gnukem

*NB This folder is essential for the game to run*

To use this using git, clone the main game, e.g.:

`git clone https://github.com/davidjoffe/gnukem_datasrc.git`

then change directory into the main game folder, and do:

`git clone https://github.com/davidjoffe/gnukem_data.git data`

Thereafter, if fetching updates, you must separately update the main folder and the data subfolder.

You can do this in one go with a command like: git pull && cd data && git pull && cd ..
