
When you are working with Optical character recognition(OCR) or any data or 
object recognition problem, the first thing to do is preprocessing. Here preprocessing means
to extract the location where our information is located. After extracting the location,
any machine algorithm will be performed on that image. 

The problem arises when you have to detect objects which are located in any tables/boxes or
in row-column format. If the image is like this then you have to detect boxes and extract them one by one. 
Now it should be done accurately for all images.

This algorithm helps to detect every boxes accurately and save it in a "Cropped" folder.The code is shown in box_detection.py 
and the test image is "41.jpg".

you can see the medium blog for this code: https://medium.com/@kananvyas/a-box-detection-algorithm-for-any-image-containing-boxes-756c15d7ed26
