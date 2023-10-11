# -Image-Morphing-Image-Pyramid-and-Image-Stylization

# Image Processing and Pyramid Morphing

This project contains two Python scripts for image processing and pyramid morphing. The image processing script includes functions for applying a Difference of Gaussians filter and XDoG (eXtended Difference of Gaussians) filter to an input image. The pyramid morphing script demonstrates smooth image morphing using Gaussian and Laplacian pyramids.

## Table of Contents

- [Image Processing](#image-processing)
  - [Difference of Gaussians (DoG)](#difference-of-gaussians-dog)
  - [XDoG (eXtended Difference of Gaussians)](#xdog-extended-difference-of-gaussians)
  - [Hatch Effect](#hatch-effect)

- [Pyramid Morphing](#pyramid-morphing)
  - [How to Run](#how-to-run)
  - [Parameters](#parameters)

- [Getting Started](#getting-started)
- [Author](#author)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Image Processing

### Difference of Gaussians (DoG)

The "difference_of_gaussians" function applies a DoG filter to an input image. You can adjust parameters like the size of the Gaussian kernel, scale factor (k), and gamma for fine-tuning.

### XDoG (eXtended Difference of Gaussians)

The "xdog_" function extends the DoG filter with additional parameters, including epsilon and phi. This filter can create artistic, edge-enhanced versions of images.

### Hatch Effect

The script also includes a "hatchBlend" function that combines an XDoG-filtered image with a hatch texture, resulting in an artistic hatching effect.

## Pyramid Morphing

### Pyramid Morphing

The "pyramid_morphing" script reads two grayscale images and a mask image and uses Gaussian and Laplacian pyramids to create a smooth morphing effect between the two images. It allows you to control various parameters like Gaussian kernel size, morphing strength, and more.

### How to Run

To use the image processing and pyramid morphing scripts:

1. Ensure you have Python installed on your system.

2. Install the necessary libraries (NumPy, SciPy, OpenCV) using pip:



3. Place your input images in the same directory as the scripts.

4. Run the individual scripts using a Python interpreter:
- For image processing: `python image_processing.py`
- For pyramid morphing: `python pyramid_morphing.py`

5. The scripts will generate processed images or morphed images based on the provided parameters.

### Parameters

- For the image processing script, you can adjust parameters in the "difference_of_gaussians" and "xdog_" functions to control the filtering and artistic effects.

- For the pyramid morphing script, you can specify parameters like the input images, mask, and morphing parameters within the script.

## Getting Started

To get started with this project, follow the instructions under "How to Run" for each script.

## Author

- tajamul Ashraf
- Krishnapriya 

## License

This project is licensed under the XYZ License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

Mention any acknowledgments or external libraries used in the project.
