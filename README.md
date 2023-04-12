Water Level Ruler
This project utilizes the Pyzbar and zxing-cpp libraries to read QR codes and calculate the water level of a ruler.

Libraries Used
Pyzbar
zxing-cpp
For a list of other QR code reading libraries that you can use, check out this blog post.

File Description
TestImg: image data used for testing
Contour: file for contour getting from testing cv2
MainImageFile: main image file, add photos of the water level ruler here and run main.ipynb to get the water level
Main.ipynb: main file with code and description
TestCode1.ipynb, TestCode2.ipynb, TestCode3.ipynb, TestMain.ipynb: files used to test QR code reading libraries and contours
TestScew.ipynb: file used to test function for skew correction
Future Work
To improve the accuracy of the QR code reader and measurement calculation, consider using other QR code reading libraries or optimizing the current code. Image processing techniques can also be used to enhance the quality of input images. Additionally, the project can be integrated with other sensors or technologies for more accurate measurements.