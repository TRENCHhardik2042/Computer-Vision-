# Colour Spaces 

In the above Code we explored a new colour space 'HSV' which shows us the Hue , Saturation and the Value of any Image.
We also learnt that how to split any image BGR using 'cv2.split' function 

While splitting for RGB color space, we observed that the output images were not in the form of colors that we depicted to be instead they were in the greyscaled versio. This happened because there was only a single value present in the image and we know that when there is only a single value, a greyscale image will be formed. 

So to convert the image into RGB format, we used the Numpy library to create arrays using the 'np.zeros' function. and then merged the RGV values respectively in the format of BGR as stored in cv2 format.
