# `Image Pyramid`

Pyramiding image refers to either upscaling or downscaling an image.

Its simply a different way of re-sizing that allows us to easily and quickly scale image. Scaling down reduces the height and widht of the image by half.

This comes in handy when making object detectors that scales images each time it looks for an object.

```
cv2.pyrDown(image)
cv2pyrUp(image)
```

> When upscaling an image from lower quality , the image quality degrades to a certain extent.

<img width="1532" alt="Screenshot 2022-11-14 at 3 01 33 PM" src="https://user-images.githubusercontent.com/91974776/201624892-8203c682-5d1f-435c-923a-1f35f1365b41.png">
