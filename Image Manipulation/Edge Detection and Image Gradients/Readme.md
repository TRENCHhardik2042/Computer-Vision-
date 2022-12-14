# `Edge Detection and Image Gradient`
Edge detection is a very important part of computer vision , especially when dealing with contours

Edges can be defined as a sudden changes (discontinuity) in an image and they can encode just as much information as pixels.
> crests and truf ...... the max and min point are the edges


## `Edge detection Algorithms`

- `Sobel`     : To emphasize on vertical and horizontal edges .

<img width="755" alt="Screenshot 2022-12-14 at 6 42 39 PM" src="https://user-images.githubusercontent.com/91974776/207605226-96af024c-7047-462e-87f5-4261c39223fc.png">


- `Laplacian` : Gets all the orientation.

<img width="749" alt="Screenshot 2022-12-14 at 6 42 54 PM" src="https://user-images.githubusercontent.com/91974776/207605132-04e0d519-9b4f-44e0-b6c4-2afe57f5c008.png">

- `Canny`     : Optimal due to lwo error rate, well defined edges and accurate edge detection.

## `Canny Edge Detection Algorithm`

Applies Gaussian Blurring 
Finds intensity gradient of the image
Applies non-maximum suppression (removes pixels that are not edges)
Hysteresis - Applies threshold  (if pixel is within the upper and lower threshold it is considered as an edge)


<img width="756" alt="Screenshot 2022-12-14 at 6 45 19 PM" src="https://user-images.githubusercontent.com/91974776/207605116-a26b04ec-6016-4e5a-88b6-c135db7c5602.png">
