# Color Identification

## Description
This project is a color identification tool that uses computer vision techniques to identify colors from an image. It calculates the closest matching color name from a predefined list of colors based on the RGB values of the selected pixel.

## Algorithm Description
1. **Color Matching Algorithm**: 
   - Calculate the absolute difference between the given RGB values and each color's RGB values in the dataset.
   - Find the color with the minimum difference and return its name.

2. **GUI Implementation**:
   - Use PySimpleGUI to create a user-friendly interface.
   - Allow users to browse and select an image.
   - Display the image and allow users to click on any point to identify its color.

## How to Execute?

   -install the visual studio code according to your system through https://code.visualstudio.com/download
   .install the python latest version from https://www.python.org/downloads/
   .Install the prerequisites/software’s required to execute the code
   .edit the path at the 23rd line in main.py 

## Issues Faced
Coordinate Out of Bounds: Handling cases where the selected coordinates are outside the image boundaries.
GUI Responsiveness: Ensuring the GUI remains responsive and updates correctly when the user interacts with it.

## Note
Make sure to update the path to colors.csv in the script if necessary.
Ensure that all required packages are installed and the virtual environment is activated before running the script.

## connect me:

For any queries feel free to connect me at www.linkedin.com/in/katkuri-balram-143284248 or katkuribalram@gmail.com

