# Face_detection_using_HaarCascades_and_OpenCV

Small but interresting project where I use Haar Cascasdes classifiers to detect face and eyes through my webcam. 

Kind of introduction to Computer vision

In this project we will elaborate a machine learning algorithm that use the webcam of the laptop to detect eyes and faces. This is one of the possibilities that offers Computer Vision.

1.	What is Computer Vision:

Computer vision is artificial intelligence (AI) that enables computers and systems to obtain meaningful information from digital images, videos, and other visual inputs, and take action and make recommendations based on that information. Where AI enables computers to think, computer vision enables them to see, observe, and understand.

Computer vision is very similar to human vision, except that human vision has benefits: Human vision has the advantage of context lifetime, learning how to distinguish objects, how far they move, when to move, and when there is a problem with the image.
Computer vision trains machines to perform these functions, but it needs to be done in a much shorter amount of time, using cameras, data, and algorithms rather than the retina, optic nerve, and visual cortex. Systems trained to inspect products and observe production assets analyze thousands of products and processes per minute and can quickly discover unnoticed defects and problems, thus it will quickly surpass humans.
Computer vision is used in industries ranging from energy and utilities to manufacturing and automotive, and the market continues to grow. It is expected to reach $ 48.6 billion in 2022.

2.	What is Haar cascades:
3.	
Introduced in 2001 by Viola and Jones in their publication “Rapid Object Detection using a Boosted Cascade of Simple Features”, and are OpenCV´s most popular object detection algorithm. 

There are many other algorithms more accurate than Haar cascades like HOG (Histogram of Oriented Gradient) + Linear SVM, SSDs, Faster R-CNN, YOLO (You Only Look Once - Deep Learning) … etc, but Haar cascades still useful and relevant till today. 
Haar Cascades are very fast but on the other hand they present some false-positive detections what requires parameter tuning.

That said, Haar cascades are:
•	An important part of the computer vision and image processing literature
•	Still used with OpenCV
•	Still useful, particularly when working in resource-constrained devices when we cannot afford to use more computationally expensive object detectors

Viola and Jones focus on detecting faces in images, but also real-time videos. Still, the framework can be used to train detectors for arbitrary “objects,” such as cars, buildings, kitchen utensils…etc.

OpenCV can perform face detection out-of-the-box using a pre-trained Haar cascade. This ensures that we do not need to provide our own positive and negative samples, train our own classifier, or worry about getting the parameters tuned exactly right. Instead, we simply load the pre-trained classifier and detect faces in images. (No Train test split needed here)
