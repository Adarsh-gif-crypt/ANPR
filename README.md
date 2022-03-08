## Automatic_Number_Plate_Detection
An Automatic Number Plate Detection algorithm which detects the number plates using canny edge detection

Libraries Used - 
[OpenCV](https://opencv.org/)
[PyTesseract](https://pypi.org/project/pytesseract/)
[Numpy](https://numpy.org/)

- The Program starts with reading the image and converting it into Grayscale
- Proceeding, it applies filters and finds rectangular edges for localisation
- Finds co-ordinates(Contours) of the plate and applies mask
- Reads the text in the image using OCR
- Renders text with Image

### Example: <br>
![image]()

Currently a work in progress
