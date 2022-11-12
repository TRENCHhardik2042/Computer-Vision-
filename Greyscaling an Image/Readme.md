# Greyscaling of any Image 

In the above code we have used the cv2 library for grayscaling any image.
We know that anay image can be represented in the form of a 3-Dimensional Array, where 
- The first element represents the Height of the image 
- The second element represents the Width of the image 
- Lastly the third element represents whether the image is made up of RGB / HSV / CMYK

For greyscaling any image we have used 2 different approach :
1. Without using any grayscaling function of cv2 
2. Using cv2 library

In the Prior approach, what we did was while loading the image using '.imread()' function, we added a parameter 0 so that only greyscaled image can be obtained
While in the Former approach , we used the functions '.cvtColor()' where the image was converted into desired color schemes. Here we passed a parameter cv2.COLOR_BGR2GRAY so that the image will be converted into grayscaled version
