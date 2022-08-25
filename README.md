# google-images-ss

Taking screenshots of images in google images for creating datasets faster with Selenium in Python. 

Lines you need to change are indicated in comment lines.

- First choose driver for the web browser you are using.
- Change the string inside box.send_keys() function to the image you are searching for.
- Change the range of for loop to select how many images you need. (Program stops when it reaches the end of first page of google images, so there is a limit.)
- Select saving location for the images.
