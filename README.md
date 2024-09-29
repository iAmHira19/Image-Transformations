# Image Transformations in OpenCV

## Description
This project demonstrates various image transformation techniques using OpenCV, including translation, scaling, and rotation. Each transformation alters the appearance of the image, allowing for basic manipulations in image processing.

## Features
- Load and display an image.
- Apply translation (shifting), scaling (resizing), and rotation to the image.
- Display the original and transformed images side by side.
- Save the transformed images as new files.

## Requirements
- Python 3.x
- OpenCV (opencv-python-headless)
- NumPy
- Matplotlib (for displaying images)

## Installation
1. Install required packages:
    ```bash
    !pip install opencv-python-headless matplotlib numpy
    ```

2. Upload an image to Colab for transformation.

## Usage
- Upload the image you want to transform.
- The script applies translation, scaling, and rotation to the image.
- The transformed images are displayed and can be saved.

## Code Explanation
- **Translation**: The image is shifted horizontally and vertically based on user-defined parameters.
- **Scaling**: The image is resized by a scaling factor, either enlarging or shrinking it.
- **Rotation**: The image is rotated around its center by a user-defined angle.

## Example Output
- **Original Image**: The original input image.
- **Translated Image**: The image shifted by a specified number of pixels.
- **Scaled Image**: The image resized by a scaling factor.
- **Rotated Image**: The image rotated by a specified angle.

## Contributing
Feel free to fork the repository, create issues, or submit pull requests with improvements or new features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
