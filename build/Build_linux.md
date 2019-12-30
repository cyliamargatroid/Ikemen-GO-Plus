# Building on Linux

With a debian based system, it can be compiled executing the following commands on a terminal:

Install golang:

`sudo apt install golang-go`

Install git:

`sudo apt install git`

Install [GLFW](https://github.com/go-gl/glfw) dependencies:

`sudo apt install libgl1-mesa-dev xorg-dev`

Install OpenAL dependencies:

`sudo apt install libopenal1 libopenal-dev`

With an Arch based system, it can be compiled executing the following commands on a terminal:

Install golang:

`sudo pacman -S go`

Install git:

`sudo pacman -S git`

Install mesa (If not avalable on other Arch-Based systems):

`sudo pacman -S mesa`

Install OpenAL dependencies:

`sudo pacman -S openal`

Note for Arch/Manjaro users; Xorg and Mesa already has the development tools

Update glibc:

`sudo pacman -S glibc lib32-glibc`

Download Ikemen GO Plus repository:

`git clone https://github.com/Windblade-GR01/Ikemen_GO.git`

Move to downloaded folder:

`cd Ikemen_GO`

Then, move to the build folder:

`cd build`

Execute get.sh to download Ikemen dependencies (it takes a while):

`./get.sh`

FINALLY compile:

`./build.sh`

The compiled Ikemen GO binary now should be inside the bin folder.

And now, Ikemen can be opened double clicking Ikemen_GO, or with the terminal:

`./Ikemen_GO`

PS: If you want to run the engine you can to donwload the mugen font and screenpack files at this [link](https://github.com/Windblade-GR01/Ikemen_GO-Elecbyte-Screenpack),
they need to be extracted at the `bin` directory.
