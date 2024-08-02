# Color Identification

## Description
This project is a color identification tool that uses computer vision techniques to identify colors from an image. It calculates the closest matching color name from a predefined list of colors based on the RGB values of the selected pixel.

## Base Paper
The project is based on the concept of color recognition using RGB values and finding the nearest matching color from a dataset of predefined colors.

## Algorithm Description
1. **Color Matching Algorithm**: 
   - Calculate the absolute difference between the given RGB values and each color's RGB values in the dataset.
   - Find the color with the minimum difference and return its name.

2. **GUI Implementation**:
   - Use PySimpleGUI to create a user-friendly interface.
   - Allow users to browse and select an image.
   - Display the image and allow users to click on any point to identify its color.

## How to Execute in VS Code?

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/color-identification.git
   cd color-identification
