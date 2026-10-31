# Image Processing Practical Files

Two Jupyter notebooks (Practical File 1: 10 problems, Practical File 2: 6 problems), written with Python, OpenCV, NumPy and Matplotlib.

| File | Topics |
|------|--------|
| `Practical_File_1.ipynb` | Problems 1-10 (with explanation): read/display, shape and dtype, grayscale, Pillow, resize, crop, rotate, flip, HSV channels, MSE |
| `Practical_File_2.ipynb` | Problems 1-6 (code only, with short analysis): edge detection, noise sensitivity, RLE vs Huffman, JPEG block artifacts, GLCM texture segmentation, multi-feature segmentation |

## How to run
```bash
pip install opencv-python numpy matplotlib pillow scikit-image jupyter
jupyter notebook
```
If an image file is missing, the notebook creates or uses a built-in sample so it still runs. Put your own images (for example `flower.jpg`, `scene.jpg`, `outdoor.jpg`) in the same folder to use them.
