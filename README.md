
# Virtual Try-On System Using Generative Models

## Project Overview

This project presents a Virtual Try-On System that leverages advanced generative models, specifically VITON and VITON-HD, to facilitate virtual clothing trials on 2D images. Our system allows users to upload an image of a person and an image of a clothing item, and then generates a new image of the person wearing the selected clothing. Through meticulous adjustments in the preprocessing stage, especially in handling agnostic models, we have achieved significantly improved results.

## Features

- **Generative Model Integration**: Utilizes state-of-the-art generative models like VITON and VITON-HD to produce realistic virtual try-on results.
- **Enhanced Preprocessing**: Incorporates advanced preprocessing techniques, particularly adjustments to agnostic models, to enhance the quality of the generated images.
- **User-Friendly Interface**: Simple and intuitive interface for users to upload images and visualize the try-on results.
- **High-Quality Output**: Generates high-resolution images with realistic clothing overlays on 2D person images.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- CUDA-enabled GPU for optimal performance
- Required Python libraries:
  - TensorFlow or PyTorch
  - OpenCV
  - NumPy
  - Scikit-image


### Usage

1. Upload a 2D image of a person.
2. Upload an image of the clothing item.
3. Click on "Try On" to generate the new image.
4. View and download the result.

## Adjustments and Improvements

### Preprocessing Enhancements

One of the key contributions of our project is the refined preprocessing stage, particularly with agnostic models. These adjustments include:

- **Improved Segmentation**: Enhanced segmentation algorithms to better isolate the person from the background.
- **Body Part Recognition**: More accurate recognition and mapping of body parts to ensure the clothing fits naturally on the person.
- **Texture Mapping**: Advanced techniques to map the clothing texture realistically onto the person's body.

### Results

Through these improvements, our system delivers more accurate and visually appealing virtual try-on results compared to baseline models. The enhanced preprocessing pipeline ensures that the generated images maintain high fidelity and realism.

## Conclusion

Our Virtual Try-On System is a robust solution for trying on clothes virtually using 2D images. By leveraging generative models and refining the preprocessing stage, we have achieved significant advancements in the quality and realism of the generated images. This project showcases the potential of AI-driven virtual try-on applications and sets the stage for future developments in this field.

