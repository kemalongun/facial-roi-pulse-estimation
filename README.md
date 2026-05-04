# Computer Vision and Signal Processing for ROI Extraction and Pulse Estimation

This project combines computer vision and biomedical signal processing techniques for facial region-of-interest extraction and non-contact pulse estimation from video data.

## Overview

The project consists of two main parts:

- **Task 1 – Computer Vision:** Facial ROI extraction from patient video data.
- **Task 2 – Signal Processing:** Pulse estimation from forehead and sclera video signals.

The project follows the general principles of remote photoplethysmography (rPPG), where subtle color and intensity variations in facial regions are analyzed to estimate cardiac activity.

## Repository Structure

Task1-ComputerVision/
    Jupyter notebook for facial ROI extraction

Task2-SignalProcessing/ 
    Jupyter notebooks for signal processing and BPM estimation

Computer Vision and Signal Processing for ROI...    
    Project reportREADME.mdREFERENCES.md.gitignore
    
## Tools and Libraries

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- SciPy
- Matplotlib

## Results
| Patient ID | Forehead BPM | Sclera BPM |
|---:|---:|---:|
| 1 | 59.2 | 63.4 |
| 10 | 62.9 | 57.5 |
| 29 | 44.5 | 53.1 |
| 5 | 51.9 | 64.9 |
| 6 | 53.6 | 52.8 |

## Related Literature

This project was developed with reference to studies on remote photoplethysmography, chrominance-based pulse extraction, ROI-based facial video analysis, and video-based physiological monitoring.

The main papers reviewed during the project are listed in [REFERENCES.md](REFERENCES.md).

## Notes

The original raw video data and patient-related binary files are not included in this repository. The repository contains only the implementation files, report, and non-sensitive project documentation.

The obtained BPM values should be considered experimental estimates rather than clinically validated measurements, since no ground-truth heart rate values were available for quantitative validation.
