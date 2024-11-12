# License Plate Detection System

## Overview
This is a Python-based license plate detection system that uses **OpenCV** and **EasyOCR** to identify license plates in images. The system performs image preprocessing such as contrast enhancement, sharpening, and thresholding, followed by optical character recognition (OCR) to extract license plate text.

## Features
- Preprocessing of images to enhance contrast and sharpness.
- Noise reduction and binarization using Otsu's thresholding and morphological transformations.
- Use of EasyOCR for detecting and recognizing text from license plates.
- Draws bounding boxes around detected text and displays the recognized characters.

## Installation

### Prerequisites
- Python 3.x
- `opencv-python`
- `easyocr`
- `numpy`
- `matplotlib`

You can install the required dependencies using `pip`:

```bash
pip install opencv-python easyocr numpy matplotlib
```

## Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/ahmdmohamedd/License-Plate-Detection.git
    cd License-Plate-Detection
    ```

2. Open the Jupyter Notebook:
    ```bash
    jupyter notebook license_plate_detection_system.ipynb
    ```

3. Run the notebook and provide an image with a license plate for detection.

## Example
An example image is processed to detect and extract the text from the license plate. The system will display the image with bounding boxes around the recognized license plate text.

## Contributing
Feel free to fork the repository, create a branch, and submit pull requests for any improvements or bug fixes.
