# `Thresholding, Binarization`

Thresholding is the act of converting an image into binary fromat

> cv2.threshold( image, THreshold value, Max Value, Threshold type)

`NOTE`: Before thresholding any image the image needs to be greyscaled

Threshold Types:
- THRESH_BINARY     -> Most Common.  Inshort it creates a threshold value, the value above threshold value will be white and below will be black

- THRESH_BINARY_INV -> Most Common  Black will be white and white will be black 

- THRESH_TRUNC      -> After the Threshold value the Shade remains the same till max value 

- THRESH_TOZERO     -> Before the Thresold value all the colour is set to black

- THRESH_TOZERO_INV -> After the Threshold value all the white colour 


<img width="1398" alt="Screenshot 2022-12-12 at 8 19 12 PM" src="https://user-images.githubusercontent.com/91974776/207075700-bb43888f-d507-4d37-b631-bc1979bb72e9.png">





# `Adaptive Thresholding`

Simple Thresholding requiers us to provied a thresold vlaue 
Adaptive Thresholding takes away that uncertainty away

> cv2.aptiveThreshold( Max Value, Adaptive Type, Threshold Type, Block Size, Constant that is subtracted from mean)

`NOTE:` Block size needs to be ODD NUMBER


`Types of Adaptive Thresholding`:
- ADAPTIVE_THRESH_MEAN_C      -> based on KNN of pixels
 
- <img width="1675" alt="Screenshot 2022-12-13 at 10 08 43 PM" src="https://user-images.githubusercontent.com/91974776/207585365-d8f278f1-0832-42ce-adf2-501ae6539eaa.png">


- ADAPTIVE_THRESH_GAUSSIAN_C  -> weighted sum of neighbourhood pixels under the Gaussian window

<img width="1673" alt="Screenshot 2022-12-13 at 10 08 18 PM" src="https://user-images.githubusercontent.com/91974776/207585433-1b56ae6a-a6b8-4429-b9c2-0256a0dfee3a.png">


- THRESH_OTSU                 -> (uses cv2.threshold function) a clever algorithm assumes there are two peaks in the grey scale histogram  of the image and then tries to find an optimal value to seperate these two peaks to find T

<img width="1672" alt="Screenshot 2022-12-13 at 10 08 27 PM" src="https://user-images.githubusercontent.com/91974776/207585403-83ba5d36-ffd9-4f0e-98f8-6e55afa174ff.png">
