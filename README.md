# Rover Path Planning Project

This project contains code for rover path planning using Bidirectional A* algorithm and terrain analysis. Due to GitHub's file size restrictions, some large input/output files have been excluded from the repository.

## Excluded Files
The following files are not included in the repository due to their large size:
- `rover_astar_result3_hillshade.png` (132MB)
- `converted_hillshade.png` (42MB)
- `masked_dem_output.tif` (523MB)
- `rover_astar_result3_hillshade_GOOD.png` (132MB)
- `South_Clear_Creek/`
- `Upper_Willow_Creek/`

## Setup and Usage
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. To run the code:
   ```bash
   python rover_path_planning.py
   ```

   Before running, modify the following variables in the script:
   - Input file paths (road_mask_path, dem_path, hillshade_path)
   - Start and goal coordinates
   - Cost function parameters (road_weight, offroad_weight, elevation_weight, etc.)

## Input Files
You will need to provide your own input files:
- Digital Elevation Model (DEM) files
- Hillshade images
- Road mask files
- Any other terrain data required for your specific use case

## Output
The code will generate:
- Path planning results
- Visualizations of the planned paths
- Terrain analysis outputs

Note: Make sure your input files are in the correct format and location as specified in the script variables. 
