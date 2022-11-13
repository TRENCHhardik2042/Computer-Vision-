# `Rotation`

An image turns around a certain pivot point for a certain angle (cosθ / sinθ)
```
[ cosθ  -sinθ] 
[ sinθ   cosθ] = M Rotation Matrix
```

OpenCV allows us to scale and rotate the image at the same time 
```
cv2.getRotationMateix2D(rotation_centre_x, rotation_centre_y, angle of rotation, scale)
```
<img width="622" alt="Screenshot 2022-11-13 at 10 13 18 PM" src="https://user-images.githubusercontent.com/91974776/201533366-7fd1d0b6-7537-4eb3-8fec-401c4d99c91f.png">
