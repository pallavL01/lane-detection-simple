# **Finding Lane Lines on the Road** 

### Reflection

### 1. Describing my pipeline

My pipeline consisted of 5 steps. 

 1. converted the images to grayscale
 2. included Gaussian smoothing
 3. applied the Canny transform to detect the edges
 4. an image mask to select the region of interest.
 5. drew the hough lines.

### 2. Identifying potential shortcomings with my current pipeline


One potential shortcoming would be what would happen when lines are hit by shadows, hidden by other cars or close to other similar features on the road. 

Another shortcoming could be identifying the lines if they get out of the region of interest like when a car changes lanes.


### 3. Suggesting possible improvements to my pipeline

A possible improvement would be to use the HSV color space to deal with shadows.

Another potential improvement could be to use machine learning to identify lane lines.
