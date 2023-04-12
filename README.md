# Water Level Ruler

### Description
This is a Python project for measuring the water level in a container using a ruler with QR codes. The project uses image processing techniques to detect and read QR codes on the ruler, and calculate the distance from the water level to the QR code at the bottom of the ruler.

## Dependencies
### This project uses the following libraries:

- OpenCV (cv2)
- Numpy
- Pyzbar
- zxing-cpp

### Usage
Clone or download the repository to your local machine.
Add the images of the water level ruler to the mainImageFile folder.
Run the main.ipynb notebook to process the images and calculate the water level.

## File Description
- `main.ipynb`: main file with code and description.
- `testCode1.ipynb`, `testCode2.ipynb`, `testCode3.ipynb`, `testMain.ipynb`: files used to test QR code reading libraries and contour.
- `testScew.ipynb`: file used to test function used for skew correction.
- `TestImg`: image data used for testing.
- `contour`: file for contour getting from testing cv2.
- `mainImageFile`: folder for the main image files used in the project.
  
## Future Work
To improve the accuracy of the QR code reader and measurement calculation, you can try using other QR code reading libraries or optimizing the current code. Additionally, you can consider using image processing techniques to enhance the quality of the input images. For future work, you can also explore the possibility of integrating the project with other sensors or technologies for more accurate measurements.

To try more QR code reading libraries: https://blog.jonasneubert.com/2022/09/30/the-best-python-packages-for-reading-barcodes/

### References
- OpenCV documentation
- Pyzbar documentation
- zxing-cpp documentation
