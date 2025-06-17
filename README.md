# Image-Processing-and-Data-Extraction
# Graph Line Extraction and Scaling (Folder - Extract Coordinates from Graph Image)

This Python script extracts a white line from a graph image, divides it into vertical strips, finds representative points on the line, and scales those points to match the graph's data axes.

## Features

- Load a graph image and detect white pixels along vertical strips.
- Aggregate multiple white pixels per strip using various methods (average, median, min, max, first, last).
- Scale pixel coordinates to a custom data range with inverted y-axis scaling.
- Visualize extracted points over the original image.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)

## Usage

1. Open Threshold Image Generation script and place your graph image file and update the `graph_image_path` variable in the script.
2. Run the script
3. Download the image under 'Thresholded Image (Plot lines/text in white):' from output of above script and crop it to remove axes (keeping only graph
feature lines)
4. Place this image file and update the `graph_image_path` in extract_and_scale_line.py script.
5. Run the script

