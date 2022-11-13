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
