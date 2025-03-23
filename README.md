

# Comparison of SSD and SAD in Motion Estimation of Video Coding

This repository contains a course assignment for **Algorithm and Massive Datasets**, focusing on the comparison between **Sum of Absolute Differences (SAD)** and **Sum of Squared Differences (SSD)** — two widely used techniques in motion estimation for video coding.

## Overview

The goal of this project is to analyze and compare the performance of SAD and SSD in detecting motion vectors between video frames. The comparison is based on:

- Accuracy of motion estimation  
- Computational efficiency using Python and NumPy  
- Error sensitivity and behavior

## Key Results

- Both SAD and SSD detected the same motion vector: `(-4, -4)`
- Computation Time (on synthetic data):
  - SSD: 0.00164 seconds
  - SAD: 0.00247 seconds
- SAD uses uniform weighting for pixel differences  
- SSD emphasizes larger pixel differences, making it more sensitive to significant variations

## Conclusion

- SAD is generally preferred for speed-critical and hardware-optimized applications  
- SSD is more suitable for tasks requiring higher precision and sensitivity to pixel variations

## Technologies Used

- Python 3  
- NumPy  

## How to Run This Project

1. Clone the repository:

   ```
   git clone https://github.com/your-username/Comparison-of-SSD-SAD-in-Motion-Estimation-Of-Video-Coding.git
   cd Comparison-of-SSD-SAD-in-Motion-Estimation-Of-Video-Coding
   ```

2. Install the required libraries (if not already installed):

   ```
   pip install numpy
   ```

3. Run the script:

   ```
   python sad_ssd_comparison.py
   ```

4. Review the console output to see the motion vector detected and computation times for SAD and SSD.

## Repository Structure

```
├── sad_ssd_comparison.py         # Main script for motion estimation
├── test_frames/                  # Sample synthetic or test frames (if applicable)
├── README.md
```

## Course Information

This project was completed as part of the **Algorithm and Massive Datasets** course.

---
