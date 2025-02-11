# Enhancing OCR Accuracy on Bank Forms Using GEN AI

This project focuses on improving the Optical Character Recognition (OCR) accuracy of bank form images using advanced preprocessing techniques and Generative AI models. The primary goal is to preprocess images by removing interfering graphical elements such as lines, grids, and checkboxes while standardizing text color and background. This enhances the text clarity for OCR systems, leading to more accurate text extraction.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Challenges and Learnings](#challenges-and-learnings)
- [License](#license)

## Project Overview
Bank forms often contain visual aids such as lines, grids, and checkboxes, which can hinder OCR systems from correctly extracting text. This project addresses these challenges by employing preprocessing methods using OpenCV and generative AI models like CycleGAN and Pix2Pix. By removing these graphical elements and standardizing the background, we enhance the OCR accuracy and reliability in text extraction.

### Key Tasks
- **Remove Graphical Elements:** Eliminate lines, grids, and checkboxes from the bank form images.
- **Standardize Text and Background:** Convert all text to black and background to white for better contrast.
- **Enhance OCR Accuracy:** Improve the clarity of text to achieve better recognition and extraction.

## Technologies Used
- **OpenCV:** For image preprocessing tasks, including the removal of graphical elements.
- **OCR Models:** TesseractOCR, EasyOCR, and PaddleOCR for text extraction.
- **Generative AI Models:** CycleGAN and Pix2Pix for enhancing image quality and removing graphical elements.
- **Python Libraries:** OpenCV, NumPy, Matplotlib, and others for image manipulation and processing.
