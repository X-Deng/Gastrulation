# Gastrulation
## Project Objective
This project focuses on visualizing the movement of cell populations on the embryo surface to better understand the mechanisms of gastrulation. By computing optical flow, we can track cell movement over time, providing valuable insights into how cells migrate during this critical developmental process. 

## Pipeline
- Loading and processing of 3D imaging data
- Calculation of 3D optical flow using `optical_flow_tvl1`
- Warping images to align frames
- Visualization of results using `napari`, which provides interactive exploration of the computed optical flow and aligned images.
- Saving and exporting results


## Files Overview
- **`demo.ipynb`**: Demonstrates the workflow for a single pair of timeframes.
- **`whole.ipynb`**: Processes the entire dataset, computing 3D optical flow across multiple channels and visualizing the results.

