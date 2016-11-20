# Circles_in_images

This project concerns the usage of parametric transforms to find circles in images.

In this project, we take a detailed look at how we can find shapes (namely, circles) inside images using the generalized 
form of the Hough Transform. 
There are two possible methods to follow to achieve this:
    1)	Using gradient vector traversal to update a 2D accumulator array and then find the regions of maximal concentration 
      in the accumulator.
    2)	Using a 3D accumulator to draw circles from each edge point and then do clustering to find the optimal point of 
      intersection, which will be the center of the original circle.
      
The first approach is adopted in this project.
