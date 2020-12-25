# AI Project

My goal was to create a program which will be able to find and separate a specific person or a group of persons images from a local folder which contains thousands of images.
To do so, I used python and a library called '[face_recongnition](https://pypi.org/project/face-recognition/)'.

**To run this program you need:**   
  - Python 3  and  
  - [face_recongnition](https://pypi.org/project/face-recognition/) installed  


**Features:** 
  - It's consoled based program
  - Consists three options:
    1. **Separate images of a person:** This function takes the image name of target person (located in `./images/training/` directory) and search all the images available in `./images/inputs/` directory. As output, it copy all  of those images which consists target person and save in a folder at `./images/outputs/` directory.  
    1. **Separate images of a group of people:** This function takes all the images located in `./images/training/` directory as target persons image and search all the images available in `./images/inputs/` directory. As output, it copy all  of those images which consists target person and save in a folder at `./images/outputs/` directory.  
    1. **Identify known persons in a image:** This function takes all the images available in `./images/training/` directory as known persons and search all the images available in `./images/inputs/` directory. As output, it show each image with identified person, if the person is known then it will show the person (image) name otherwise it will show unknown. It also save a identified copy of those images in a folder at `./images/outputs/` directory.  
 - Make sure your target persons image are located in `./images/training/` directory and the images you wannna filter are located in `./images/inputs/` directory.
