# Lane-Detection-Curved-Roads

This project demonstrates how to detect lane lines on curved roads using OpenCV and Python. Each step is explained with visual outputs and documentation.

## 🚀 How It Works

1. Load and resize the input image
2. Apply color filter (yellow & white lanes)
3. Use edge detection (Canny)
4. Define a region of interest (ROI)
5. Apply Hough Transform to detect lines
6. Overlay lines on the original image

## 📁 File Structure

- `lane_detection_curved.ipynb` - Jupyter Notebook 
- `test_curved_road.jpg` - Sample road image
- `output_images/` - Output folder with plots
- `requirements.txt` - List of Python libraries to install

- ## 📦 Installation

```bash
pip install -r requirements.txt
