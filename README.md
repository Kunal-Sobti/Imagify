# Image Segmentation-What and How?
Image segmentation refers to the task of annotating a single class to different groups of pixels. While the input is an image, the output is a mask that draws the region of the shape in that image. Image segmentation has wide applications in domains such as medical image analysis, self-driving cars, satellite image analysis, etc. There are different types of image segmentation techniques like semantic segmentation, instance segmentation, etc. To summarize the key goal of image segmentation is to recognize and understand what's in an image at the pixel level.

For the image segmentation task, we will use "The Oxford-IIIT Pet Dataset" which is free to use dataset. They have 37 category pet dataset with roughly 200 images for each class. The images have large variations in scale, pose and lighting. All images have an associated ground truth annotation of breed, head ROI, and pixel-level trimap segmentation. Each pixel is classified into one of the three categories:
1.Pixel belonging to the pet

2.Pixel bordering the pet

3.Pixel belongs neither in class 1 nor in class 2
