# We need to build a system that is capable of:

- Taking in the image/video (series of images) from surrounding along with a camera and at the software end, we need a library to capture and process the data (image). I’ve used `OpenCV (4.1.0)`.
- Looking for a license plate in the image. I used `pretrained Haar cascade` (identify objects in an image or video and based on the concept of features proposed by Paul Viola and Michael Jones in their paper “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001)
- Analyzing and performing some image processing on the License plate. 
- Segmenting the alphanumeric characters from the license plate.
- Considering the characters one by one, recognizing the characters, concatenating the results and giving out the plate number as a string

# Steps:
1. Number plate detection
2. Image processing
3. Segmenting the alphanumeric characters from the license plate.
4. Building and creating the model (I used a Convolutional Neural Network with 3 layers)



![image](https://user-images.githubusercontent.com/108471933/223166834-8f24c17e-fe2b-4947-940f-ef21640abd15.png)
