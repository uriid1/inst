# inst
Script that adds photos to a white square of 1080x1080 with the same aspect ratio.\ You can set the size of the square (frame).\
You will need imagemagick to work\
Termux support is available!

![Screenshot](https://github.com/uriid1/scrfmp/blob/main/inst/inst.png)

# Install
1) git clone https://github.com/uriid1/inst/<br />
2) cd inst
3) chmod +x install
4) sudo ./install
5) Done! Delele inst folder.

# Using
Keys:\
-a or --all  To process all files in the directory\
-o or --one  To process one specific file\
-w or --width  Sets the width\
-h or --height  Sets the height

This example will create an inst_file_name.png image
by writing the input image in a white square of 1080x1080px\
$ inst -o file_name.png 40

Fitting all images from the directory to a square of 1080x1080\
$ inst -all 40

Fit one or more images into a given square.\
$ inst -all 50 -w 512 -h 512

# Uninstall
sudo rm /usr/bin/inst
