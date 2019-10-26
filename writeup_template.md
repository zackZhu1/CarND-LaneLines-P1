# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. 
1. grayscale the image
2. apply a gaussian smoothing module
3. apply a canny edge detection module
4. select region of interest
5. apply hough transform line detection

### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the vehicle is driving in curvy lanes



### 3. Suggest possible improvements to your pipeline

A possible improvement would be to apply advanced techniques to detect curvy lanes
