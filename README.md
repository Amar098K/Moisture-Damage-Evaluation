
# Moisture Damage Evaluation in Asphalt Mixtures using Image Analysis

## Introduction

This repository contains an algorithm developed in Python for evaluating moisture damage in asphalt mixtures using image analysis techniques. The algorithm takes images of asphalt samples after exposure to moisture and calculates the stripping and coating percentage on the aggregate.

## Features

- Image preprocessing to enhance the asphalt sample and moisture damage features.
- Segmentation of the asphalt and moisture-damaged areas using computer vision techniques.
- Calculation of a moisture damage percentage based on the pixel intensity differences between the two regions.
- Visualization of the moisture damage and segmented regions on the original images.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib (for visualization)

## Installation

1. Clone this repository to your local machine using the google colaboratory file which is provided in the file as "Moisture Damage Evaluation.ipynb"

## Datasets
The algorithm has been tested on the following datasets:

- FRL5
- FRL10
- IL5
- IL10
- IL15
- VG40new
These datasets consist of sample images of asphalt mixtures before and after moisture exposure, representing different moisture damage levels.


