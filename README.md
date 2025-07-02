# Automatic Number Plate Recognition (ANPR) System

This project is an end-to-end system for automatically detecting and recognizing license plates from images. It's a classic computer vision project that showcases a pipeline of image processing techniques to extract alphanumeric characters from a non-standardized environment.

## Technical Overview

-   **End-to-End System:** Built a complete ANPR system using Python, leveraging the OpenCV library for image manipulation and Tesseract for optical character recognition.
-   **Image Preprocessing Pipeline:** Implemented a comprehensive preprocessing pipeline to enhance image quality for better OCR accuracy. This included grayscale conversion, noise reduction (`fastNlMeansDenoising`), image deskewing, and cropping.
-   **Character Segmentation:** Performed character segmentation from the license plate using Otsu's Binarization method and contour analysis to isolate each individual character.
-   **OCR Integration:** Integrated the Tesseract OCR engine (via Pytesseract wrapper) to extract the final alphanumeric text from the processed and segmented plate image.

## Technologies & Libraries Used

-   Python
-   OpenCV
-   Pytesseract (Tesseract OCR)
-   NumPy
-   Matplotlib

## Project Workflow

Image Input → Image Preprocessing (Grayscale, Denoising, Deskewing) → Character Segmentation (Binarization, Contour Analysis) → OCR with Tesseract → Text Output

---

***Disclaimer:** Please note that the code currently in this repository is the raw version from an earlier stage of my learning journey. A more well-documented, refactored, and structured version is currently in development.*
