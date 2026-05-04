# Computer Vision and Signal Processing for ROI Extraction and Pulse Estimation

This project combines computer vision and biomedical signal processing techniques for facial region-of-interest extraction and non-contact pulse estimation from video data.

The project consists of two main parts:

- **Task 1 – Computer Vision:** Extraction of facial regions of interest, including forehead and eye regions.
- **Task 2 – Signal Processing:** Pulse estimation from forehead and sclera video signals using signal processing techniques.

## Project Overview

The objective of this project is to process facial video data and estimate pulse-related information from selected facial regions. In the first stage, relevant facial regions were extracted and prepared in a structured format. In the second stage, the extracted forehead and sclera signals were processed to estimate pulse rate values.

The project follows the general principles of remote photoplethysmography (rPPG), where subtle color and intensity variations in facial regions are analyzed to infer cardiac activity.

## Repository Structure

```text
Task1-ComputerVision/
    Jupyter notebook for facial ROI extraction

Task2-SignalProcessing/
    Jupyter notebooks for binary video reading, signal processing, and BPM estimation

Computer Vision and Signal Processing for ROI...
    Project report

README.md
REFERENCES.md
.gitignore
