# IMAGE ANALYSIS AND COMPUTER VISION

## Project Overview

This repository contains the implementation of various methods for synchronization of projective transformations in image analysis and computer vision. The project focuses on techniques such as:

- Direct Synchronization
- Iterative Synchronization
- Spectral Method
- Tree-Based Method
- Sphere-Based Method

These methods are essential for solving problems in image alignment, camera calibration, and 3D reconstruction.

## Table of Contents

- [Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/MiladRamezani0/IMAGE-ANALYSIS-COMPUTER-VISION.git
   cd IMAGE-ANALYSIS-COMPUTER-VISION
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your input data (homography matrices or transformation data) and place it in the appropriate format.
2. Run the main script to compute the synchronized transformations:
   ```bash
   python main.py
   ```
3. View the output transformations and analysis results in the console or exported files.

## Methods

The following methods are implemented in this repository:

- **Direct Synchronization**: Calculates transformations directly using linear algebra.
- **Iterative Synchronization**: Refines transformations iteratively for improved accuracy.
- **Spectral Method**: Uses spectral decomposition to find optimal transformations.
- **Tree-Based Method**: Synchronizes transformations based on hierarchical tree structures.
- **Sphere-Based Method**: Employs a spherical optimization approach for synchronization.

## Results

Sample outputs include synchronized projective transformations, error analysis, and visualization of the results. These outputs demonstrate the effectiveness of each method under different noise levels.

## Contributors

- **Milad Ramezani Ziarani**  
  [GitHub Profile](https://github.com/MiladRamezani0)  
  M.Sc. in Geoinformatics Engineering, Politecnico di Milano

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
