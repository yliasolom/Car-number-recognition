# Russian Car License Plate Detection and Recognition with OpenCV and TesseractOCR

### Introduction
- Use of OpenCV to detect Russian car plates in images, and TesseractOCR (optical character recognition engine) to extract number and text from the detected lisense plate. 

### About Haar Cascade XML File:
Paul Viola and Michael Jones came up with the object detection technique using Haar feature-based cascade classifiers. It is an approach (involving AdaBoost) where a cascade function is trained from many positive and negative images. It extracts numerical values for features  efficiently with the concept of integral image, which trumps the default computationally-heavy way of subtracting sums of pixels across multiple regions of an entire image.

OpenCV actually comes with pre-trained XML files of various Haar Cascades, where each XML file contains the feature set. So I used Haar Cascade XML file containing the features for Russian car plates. 

### About TesseractOCR:
TesseractOCR is an open-source optical character recognition (OCR) engine. Learn more: 
(https://github.com/tesseract-ocr/tesseract)
