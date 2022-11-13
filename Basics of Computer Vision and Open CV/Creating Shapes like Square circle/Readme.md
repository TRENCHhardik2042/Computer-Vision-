# `Creating Shapes like Rectangle, Circle and Polygon algon with Lines and adding Text to any image`

In the above code we can see that images can be formed with the help of numpy.array()
We even formed two black images with the numpy arrays as shown below
<img width="1147" alt="Screenshot 2022-11-13 at 2 04 14 PM" src="https://user-images.githubusercontent.com/91974776/201526640-43b9f1af-a5b5-48ba-ae0b-5165553f5c3a.png">

We learnt about the functions like for creating any shape :
- ## Drawing Line over the Black Square Image
cv2.line(image, starting vertex, ending vertex, color, thickness) 
.lines
<img width="591" alt="Screenshot 2022-11-13 at 2 37 33 PM" src="https://user-images.githubusercontent.com/91974776/201526464-ea4585c7-9bd5-4373-9b13-adf386806fb9.png">


- ## Drawing a Rectangle in a Black Square
cv2.rectangle(image, starting vertex, ending vertex, color, thickness)
.rectangle
<img width="546" alt="Screenshot 2022-11-13 at 2 40 29 PM" src="https://user-images.githubusercontent.com/91974776/201526480-5387f3d6-4336-4817-82a5-41c049eedf7f.png">



- ## Drawing a Circle
cv2.circle(image, centre, radius, color, fill)
.circle

<img width="557" alt="Screenshot 2022-11-13 at 2 45 53 PM" src="https://user-images.githubusercontent.com/91974776/201526488-36bfb8fc-911c-4592-8d9f-1d0dc96b7f0d.png">



- ## Polygons
cv2.polylines( image, points, whether polygon is closed or not, color, thickness)
.polylines
 <img width="573" alt="Screenshot 2022-11-13 at 3 35 36 PM" src="https://user-images.githubusercontent.com/91974776/201526495-3fb6f14e-b368-48bb-a6c5-9ca01a995dbd.png">



> While adding thickness to any field we learnt that if positive value is passed, then a border line will be created ; whereas if negative value is passed, a fill will be given to the shape


- ## Adding text to image
cv2.putText(image, 'Text to Display', bottom left starting point, Font, Font size, Color, Thickness)
<img width="530" alt="Screenshot 2022-11-13 at 3 47 24 PM" src="https://user-images.githubusercontent.com/91974776/201526615-dc3a4ac9-30ce-449a-892d-ef5574115c97.png">
