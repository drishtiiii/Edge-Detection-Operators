# Edge-Detection-Operators
Python program for Sobel and Prewitt Operator
</br>
</br>
Edges are calculated by using difference between corresponding pixel intensities of an image. All the masks that are used for edge detection are also known as derivative masks. Because as we have stated many times before in this series of tutorials that image is also a signal so changes in a signal can only be calculated using differentiation. So that’s why these operators are also called as derivative operators or derivative masks.
</br>
All the derivative masks should have the following properties:
</br>
*Opposite sign should be present in the mask.</br>
*Sum of mask should be equal to zero.</br>
*More weight means more edge detection.</br>
### Prewitt Operator</br>
Prewitt operator is used for edge detection in an image. It detects two types of edges:
</br>
*Horizontal edges</br>
*Vertical Edges</br>
Prewitt operator provides us two masks one for detecting edges in horizontal direction and another for detecting edges in an vertical direction.
</br>
When we apply this mask on the image it prominent vertical edges. It simply works like as first order derivate and calculates the difference of pixel intensities in a edge region. As the center column is of zero so it does not include the original values of an image but rather it calculates the difference of right and left pixel values around that edge. This increase the edge intensity and it become enhanced comparatively to the original image.
</br>
### Sobel Operator</br>
The sobel operator is very similar to Prewitt operator. It is also a derivate mask and is used for edge detection. Like Prewitt operator sobel operator is also used to detect two kinds of edges in an image:
</br>
*Vertical direction</br>
*Horizontal direction</br>
</br>
When we apply this mask on the image it prominent vertical edges. It simply works like as first order derivate and calculates the difference of pixel intensities in a edge region.
</br>
As the center column is of zero so it does not include the original values of an image but rather it calculates the difference of right and left pixel values around that edge. Also the center values of both the first and third column is 2 and -2 respectively.
</br>
This give more weight age to the pixel values around the edge region. This increase the edge intensity and it become enhanced comparatively to the original image.
</br>
