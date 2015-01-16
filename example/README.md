#Example

This version of the alien client includes w3m's w3mimgdisplay program. 

The program draws images into a framebuffer so this can render images in your terminal without opening firefox (yay!)

This client uses seikichi's pyw3mimg (https://github.com/seikichi/pyw3mimg) in order to handle the w3mimg protocol


How to run
===
alien pics -o 1 //show image in framebuffer
alien pics -f -o 1 //show image in framebuffer full size
alien gifs -o 1 //show animated gif in framebuffer full size

Dependencies
===
w3m //for /usr/lib/w3m/w3mimgdisplay
gifsicle //for exploding gif images
Enjoy!
