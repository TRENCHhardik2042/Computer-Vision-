# `Convolution`

Basically convolution can be defined as a mathematical operation performed on two functions producing a third function, which is modified version of one of the orignal functions.

``
Output Image = Image x Function(kernal size)
``

In Computer Vision, Kernal size is used to specify the size over which we run our manipulating function over our image.


# `Blurring`

Blurring is an operation where we average the pixels within a particular region (kernal)

``
Kernal = 1/25 [[11111],[11111],[11111],[11111],[11111]]
``
The above is a 5x5 kernal 
> Increasing the matrix size increases the amount of Blurring 

We multiply it by 1/25 to normalize i.e. sum to 1, otherwise we'd be increasing the intensity 

```
cv2.filter2D(image,-1,kernal)
```

- `Averaging`
> Done by Convulating the image with a normalized box filter.     
This takes the pixel under a box and replaces the central element.    
`Box size needs to be odd and positive`

<img width="442" alt="Screenshot 2022-12-11 at 10 08 10 PM" src="https://user-images.githubusercontent.com/91974776/206916593-afbede46-b966-4ee3-b065-f29aa9b74db0.png">



- `Gaussian blur`
> Instead of box filter Gaussian Blur
<img width="420" alt="Screenshot 2022-12-11 at 10 08 19 PM" src="https://user-images.githubusercontent.com/91974776/206916605-c86615b3-828a-4868-b543-ddacfb64f2d7.png">


- `Median Blur`
> Takes the median of all the pixel in a kernal and central element is replaced with the median vlaue
<img width="423" alt="Screenshot 2022-12-11 at 10 08 15 PM" src="https://user-images.githubusercontent.com/91974776/206916612-1b3427ad-8d4f-4132-85e6-c1bbcd0305c6.png">


- `Bilateral Blur`
> Effective in noise removal while keeping the edges sharp

<img width="415" alt="Screenshot 2022-12-11 at 10 08 24 PM" src="https://user-images.githubusercontent.com/91974776/206916624-9e6b0357-e1f1-4e8c-a59e-48b6e6a0a769.png">


- `Image Denoising`

Parameters, after none are - the filter strength 'h' (5-10 is a good range )
Next is hForColourComponents, set as same value as h again

It takes a while to get the output
<img width="757" alt="Screenshot 2022-12-11 at 10 19 36 PM" src="https://user-images.githubusercontent.com/91974776/206917028-8905b74a-ff0f-48bd-9e3e-09f21ef0bebb.png">


  - Types of Denoising 
   1) cv2.fastNlMeansDenoisingColored()      -> works with a coloured image
   2) cv2.fastNlMeansDenoising()             -> works with a greyscaled image
   3) cv2.fastNlMeansDenoisingMulti()        -> works with image sequence captured in short period of time (greyscale images)
   4) cv2.fastNlMeansDenoisingColoredMulti() -> works with image sequence captured in short period of time (colored images)
