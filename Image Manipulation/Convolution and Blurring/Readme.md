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




- `Gaussian blur`
> Instead of box filter Gaussian Blur


- `Median Blur`
> Takes the median of all the pixel in a kernal and central element is replaced with the median vlaue


- `Bilateral Blur`
> Effective in noise removal while keeping the edges sharp
