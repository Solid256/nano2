Directions for compiling nano2.

First, follow the directions in the link below, but skip the last step. Ignore the 'it will take 40 minutes to finish' crap. It won't, trust me.

http://mybookworld.wikidot.com/compile-nano-from-source

for compiling nano after compiling ncurses, run these commands instead:

cd ../nano-3.2<or nano2>

mkdir stage
./configure --prefix /<full url to nano3.2 or nano2>/stage
make
sudo make install

This will build the program inside of the stage folder in your nano source code folder.

Go to the folder nano-3.2<or nano2>/stage/bin and type ./nano to run the program. Do NOT type 'nano' by itself, as this will run the original nano.

Link to the original nano website:
    https://nano-editor.org/
