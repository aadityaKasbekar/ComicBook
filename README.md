# PyCartoon: Python Image Cartoonization & Comic Strip Generator

PyCartoon is a comprehensive Python toolset designed for image cartoonization and comic strip generation. This project provides a robust set of functions and scripts to transform images into cartoon-like illustrations, overlay text onto images, and create professional-quality comic strips. With support for multiple languages, dynamic layouts, and PDF generation, PyCartoon offers a versatile solution for generating engaging visual content.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Instructions](#instructions)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Acknowledgments](#acknowledgments)
- [Output](#output)

## Introduction
PyCartoon simplifies the process of creating comic strips by providing a collection of functions and scripts tailored for image processing and comic generation tasks. Whether you're a professional artist, educator, or hobbyist, PyCartoon offers a user-friendly interface to unleash your creativity and storytelling abilities.

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/PyCartoon.git](https://github.com/aadityaKasbekar/PyCartoon-Python_ImageCartoonization_and_ComicPDFGenerator)
   ```
2. Install the required dependencies using pip:
   ```bash
   pip install <dependency name>
   ```

## Instructions
1. Make sure all the required images are stored in the `Eng/` and `Hin/` directories for English and Hindi versions respectively.
2. Ensure that the font file `LilitaOne-Regular.ttf` is available in the `font/` directory.
3. Run the `ComicBook.py` script to generate the PDF files for both English and Hindi versions.
4. The generated PDF files will be named `TheHackathon_English.pdf` and `TheHackathon_Hindi.pdf`.

## Usage
1. Customize the parameters and options in the provided scripts to suit your requirements.
2. Run the scripts to generate comic strips in PDF format.
3. Explore the generated PDFs and share your comic strips with others.

## Features
- **Image Cartoonization**: Convert images into cartoon-like illustrations with customizable settings.
- **Text Overlay**: Overlay text onto images with support for multiple languages and font choices.
- **Comic Strip Generation**: Create comic strips by combining images and dialogues in a sequential layout.
- **PDF Generation**: Generate PDF documents containing comic strips with Unicode character support.

## Dependencies
PyCartoon relies on the following dependencies:
- OpenCV (cv2)
- Pillow (PIL)
- pandas
- numpy
- textwrap
- FPDF

## Acknowledgments
- Special thanks to the developers of OpenCV, Pillow, pandas, numpy, textwrap, and FPDF for their contributions to the Python ecosystem.
- Inspired by the creativity and storytelling capabilities of comic strips.

## Output

[View Notebook](ComicBook.ipynb)
[View English PDF](TheHackathon_English.pdf)
[View Hindi PDF](TheHackathon_Hindi.pdf)
