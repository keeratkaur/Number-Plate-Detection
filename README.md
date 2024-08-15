# Number-Plate-Detection
The Number Plate Detection System is a Python-based application designed to automatically detect and extract vehicle number plates from images. This system employs advanced image processing techniques to accurately identify number plates.

## Custom Dataset:

Self-Created Dataset: The system uses a dataset that was created specifically for this project. The dataset includes images of vehicles captured under different conditions, such as varying angles and lighting, to ensure that the detection algorithm is robust and adaptable to diverse scenarios.

## Image Preprocessing:

Grayscale Conversion: The input images are converted to grayscale to simplify the processing and enhance the focus on the number plates.
Noise Reduction: Techniques such as median filtering are applied to the grayscale images to remove noise, making the number plates clearer and easier to detect.

### Edge Detection:

Canny Edge Detection: The system employs the Canny edge detection algorithm to find the edges within the image, which is a critical step in identifying the boundaries of the number plates.

### Contour Detection:

Contour Analysis: After edge detection, the system analyzes the contours in the image. Contours resembling the shape and size of typical number plates are selected for further processing.

## Plate Extraction:

Region of Interest (ROI) Selection: The system identifies and extracts the region of interest (ROI) containing the number plate from the image.
Perspective Transformation: If necessary, the system corrects any skew or distortion in the extracted number plate to ensure accurate character recognition.

### Character Segmentation and Recognition:

Character Segmentation: The system isolates individual characters from the extracted number plate, preparing them for recognition.
Optical Character Recognition (OCR): The isolated characters are then processed using OCR to convert them into text. This step is essential for reading the alphanumeric characters on the number plate.
Results Display:

Output Generation: The system provides the detected number plate in both image and text format, facilitating easy verification and further use in applications.
