# inst
Script that adds photos to a white square of 1080x1080 with the same aspect ratio. You can set the size of the square (frame).

![Screenshot](https://cs03.spac.me/f/087069048125087123181077169255042197255015203119156239075033085175/1605032965/83313815/0/1c23f2872be04f20f97a158685030346/inst-spaces.im.png)

# Install
1) git clone https://github.com/uriid1/inst/
2) cd inst
3) chmod +x install
4) sudo ./install
5) Готово!

# Using
Keys:
-a or --all  To process all files in the directory
-o or --one  To process one specific file
-w or --width  Sets the width
-h or --height  Sets the height

This example will create an inst_file_name.png image
by writing the input image in a white square of 1080x1080px.
$ inst -o file_name.png 40

Fitting all images from the directory to a square of 1080x1080
$ inst -all 40

Fit one or more images into a given square.
$ inst -all 50 -w 512 -h 512

# Uninstall
sudo rm /usr/bin/inst
