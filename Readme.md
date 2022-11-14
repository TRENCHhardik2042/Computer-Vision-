# `Computer-Vision`

 Computer Vision is a cutting edge field of _**Computer Sciene**_ which aims to enable computers to understand what is being seen in an image.
 > It is always a big part of Artificial Intelligence.
 It helps the machine to see and understand the world around them just like in the movie ***Terminator*** with the help of sensors.
 
 ## `Computer Vision Challenges:`
 
 - Camera sensor & Lens limitation
 > Camera sensors preform bad in low light conditions and create noisy images. Pixelated image will be formed if zoomed. 
 
 - Viewpoint Variation
 
 - Changing Lighting conditions
 
 - Scaling issues
 
 - Non rigid deformations
 
 - Occlusion
 > Partially blocked or shut images 
 
 - Clutter
 > Finding a chameleon while its camouflaged.
 
 - Object Class Variation
 
 - Ambiguous images / Optical Illusion
 
 
 
 ## Applications of Computer Vision: 
 
 - Robotic Navigation
 - Face Detection 
 - Search Engine 
 - License Plate Reading 
 - Handwriting Recognition
 - Snapchat Fliters
 - Object Recognition
 - Ball & Player Tracking in Sports 
  And many more .......
  
  
  
  ## OpenCV & Python
  - Python is an easy platform for beginners. Python is extremely powerful for Data Science & Machine Learning application
  - Python stores images in the form of ***numpy arrays*** which allows us to do powerful operations quite easily
  
  
  
  ## Key areas in Computer Vision
  
  - Setup
  - Basics of Computer Vision & OpenCV
  - Image Manipulation
  - Image Segmentation
  - Object Detection
  - Face, People & Car Detection
  - Face Analysis and Filters 
  - Machine Learning in Computer Vision
  - Motion Analysis & Object Tracking 
  
  
  
  ## `Mini Projects covered `
  
  - Live Drawing Sketch of yourself
  - Shape Matching 
  - Counting Circles and Elipse
  - Finding Waldo 
  - Object Identification
  - Face, Pedestrian & Car Detection 
  - Live Face Swaps 
  - Face Reader 
  - Handwritten Digit Recognition 
  - Facial Recognition 
  - Ball Tracking 
  - Photo Restoration
  
  
  ## `Requirements` 
  
  - Webcam 
  - Python 
  - OpenCV
 
 
 ## OpenCV 2.14.3 & 3.1.0
 
 - 2.14.3 lacks few features of Object Tracking 
 - 3.1.0 lacks important functions like SIFT, SURF, etc.
 
 
 
 ## `What are Images`
 
Images are 2-Dimensional Representation of the visible Light spectrum
Represented in X-Y dimension like an 2D array
Each Pixel is a combination of 3 Colours RGB


## `How images are formd?`

- When light reflects off an object onto a film, sensor or retina 
- Using a small barrier (aperture) , we block off most of the rays of light reducing the blurring on the film or sensor
> This is the pinhole camera

## `Controlling the image formation`
-Both our camera adn eyes use an adaptive lens to control many aspects of image formation such as:
> ##Aperture Size
  - Controls the amount of light allowed through 
  - Depth of Field (bokeh) 
> Lens Width - Adjust focus distance ( near/far )


## `How does a computer Store an Image ?`

Using OpenCV , it uses RGB color space by default but it stores in BGR format
Each pixel coordinate (x,y) contains 3 values ranging for intesity of 0 to 255 (8-bit)
> Red 
> Green
> Blue

Mixing Different intensity of each colour will result in full colour spectrum
In each array which represents a pixel , the (RGB) data is stored 

