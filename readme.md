# AI Project

My goal was to create a program that will be able to find and separate a specific person or a group of people images from a local folder that contains thousands of images.
To do so, I used python and a library called '[face_recongnition](https://pypi.org/project/face-recognition/)'.

**To run this program you need:**   
  - Python 3  and  
  - [face_recongnition](https://pypi.org/project/face-recognition/) installed  


**Features:** 
  - It's consoled based program
  - Consists of three options:
    1. **Separate images of a person:** This function takes the image name of the target person (located in `./images/training/` directory) and searches all the images available in the `./images/inputs/` directory. As output, it copies all of those images which consists target person and save in a folder at `./images/outputs/` directory.  
    1. **Separate images of a group of people:** This function takes all the images located in the `./images/training/` directory as target person image and searches all the images available in the `./images/inputs/` directory. As output, it copies all of those images which consists target person, and saves them in a folder at the `./images/outputs/` directory.  
    1. **Identify known persons in an image:** This function takes all the images available in the `./images/training/` directory as known persons and search all the images available in the `./images/inputs/` directory. As output, it shows each image with an identified person, if the person is known then it will show the person (image) name otherwise it will show unknown. It also saves an identified copy of those images in a folder at the `./images/outputs/` directory.  
 - Make sure your target person's image is located in the `./images/training/` directory and the images you wanna filter are located in the `./images/inputs/` directory.
