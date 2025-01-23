# Marker PDF Tool

## Description
This project utilizes the `marker-pdf` library to process PDF files. The example provided processes the HKBU Sustainability Report for 2023-2024 and saves the output to a specified directory.

## Requirements
Make sure you have Python installed on your system. This project requires the following libraries:

- `torch`
- `torchvision`
- `torchaudio`
- `marker-pdf`

## Installation

To install the required libraries, run the following commands:

```bash
pip3 install torch torchvision torchaudio
pip install marker-pdf
```
## To run the code, use the following command:
```bash
marker_single HKBU-Sustainability-Report-2023-2024.pdf --output_dir "PATH_to_save"
```
