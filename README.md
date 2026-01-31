# Project Title
# How to set up the virtual environment
# How to run Python scripts
Edited on GitHub web interface
# Run Instructions

## Reflection: Computational Thinking Less

- Abstraction: I chose to inspect the CSV containing point coordinates (longitude and latitude) to verify the integrity of spatial data before further processing like for mapping or analysis. 
- Representation: I assume that the CSV columns 'lon' and 'lat' represent decimal degrees in the WGS84 coordinate system and that all rows correspond to valid points and that 'id' is a unique identifier for each point.
- Respondibility: The script should automatically check for missing values, invalid coordinate ranges, and generate summary statistics or a quick scatter plot while human should check for issues that the script cannot catch/check, such as duplicate points, mislabeled coordinates, or inconsistencies in metadata.
- Scale: If the dataset becomes very large, problems may include slower script execution, higher memory usage, and difficulty visualizing all points in a scatter plot. 
