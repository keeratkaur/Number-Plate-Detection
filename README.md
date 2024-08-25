# Number-Plate-Detection
The Number Plate Detection System is a Python-based application designed to detect and extract vehicle number plates from images automatically. This system employs advanced image processing techniques to accurately identify number plates.

## Custom Dataset:

Self-Created Dataset: The system uses a dataset that was created specifically for this project. The dataset includes images of vehicles captured under different conditions, such as varying angles and lighting, to ensure that the detection algorithm is robust and adaptable to diverse scenarios.

## Image Preprocessing:

Grayscale Conversion: The input images are converted to grayscale to simplify the processing and enhance the focus on the number plates.
Noise Reduction: Techniques such as median filtering are applied to the grayscale images to remove noise, making the number plates clearer and easier to detect.

![Screenshot 2024-07-30 164253](https://github.com/user-attachments/assets/85c9858a-3bc3-40a7-8ca7-70c6db8f94e9)


### Edge Detection:

Canny Edge Detection: The system employs the Canny edge detection algorithm to find the edges within the image, which is a critical step in identifying the boundaries of the number plates.

![Screenshot 2024-07-30 164302](https://github.com/user-attachments/assets/56faf9b6-9672-444c-90c3-b4b5acea91f5)



### Contour Detection:

Contour Analysis: After edge detection, the system analyzes the contours in the image. Contours resembling the shape and size of typical number plates are selected for further processing.

## Plate Extraction:

Region of Interest (ROI) Selection: The system identifies and extracts the region of interest (ROI) containing the number plate from the image.
Perspective Transformation: If necessary, the system corrects any skew or distortion in the extracted number plate to ensure accurate character recognition.

![Screenshot 2024-07-30 164316](https://github.com/user-attachments/assets/def80719-13cd-4584-a9d6-88a376548bb4)




### Character Segmentation and Recognition:

Character Segmentation: The system isolates individual characters from the extracted number plate, preparing them for recognition.
Optical Character Recognition (OCR): The isolated characters are then processed using OCR to convert them into text. This step is essential for reading the alphanumeric characters on the number plate.

![Screenshot 2024-07-30 164326](https://github.com/user-attachments/assets/6ad46a1b-8eeb-49d7-bfa3-c666a1015d32)

### Results Display:

Output Generation: The system provides the detected number plate in image and text format, facilitating easy verification and further application use.

![Screenshot 2024-07-30 164804](https://github.com/user-attachments/assets/d2058c66-d43b-487f-88fd-c2a7b71dd81d)

