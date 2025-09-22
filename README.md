# image-HUE-analysis
A Jupyter project that analyzes crop images by detecting green hues and separating them into levels. This helps visualize crop status and detect potential stress areas. The current version is tuned for green hues under direct sunlight, but future improvements could normalize shadows and lighting variations.


# Crop Hue Analyzer

This project provides a Jupyter Notebook to analyze crop images by focusing on the **green hue spectrum**.  
It separates green tones into different levels, allowing better visualization of crop status and helping to identify potential stress or growth variations.

## Features
- Detects **green hues** in crop images using HUE values.
- Separates green into levels for easier visualization.
- Highlights potential areas of stress or abnormal growth.
- Works best with images taken under direct sunlight (to avoid shadow interference).

## Limitations / Next Steps
- Shadows may appear as darker greens, creating noise in detection.
- Current version is calibrated for sunlight at zenith.
- Future work: shadow normalization, multi-spectral adaptation, automatic warnings.

## Quickstart
1. Clone the repository:

git clone https://github.com/Chirip4/crop-hue-analyzer.git

cd crop-hue-analyzer

2. Install dependencies:

   pathlib, os, numpy,cv2, PIL, matplotlib
   
3. Run the Jupyter Notebook:

   jupyter notebook image_color_analyzer.ipynb
   
4. Uplad a crop image and visualize green hue levels.

### Image Directory Setup

This project uses a flexible way to load images that works on any OS or cloud environment:

- By default, it expects an `Images/` folder in the project root.
- You can override this by setting an environment variable:

export IMAGES_DIR="/path/to/your/images"

# Sample result:

<img width="801" height="316" alt="imagen" src="https://github.com/user-attachments/assets/e9618622-ec4e-4401-8d8b-d12d7e4ac79c" />



