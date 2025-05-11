# CV-CT3
## Noise Reduction Techniques Comparison Tool
This project implements a GUI-based tool to compare image denoising techniques for Gaussian noise
### Features
1. Denoising Methods: Gaussian blur, median blur, wavelet transform, convolutional autoencoder.
2. GUI: PyQt5 interface for uploading and visualizing images.
3. Evaluation Metrics: Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), Structural Similarity Index (SSIM).
4. Input: Supports RGB images (PNG, JPG, JPEG), resized to 128x128 pixels.
### Installation
1.	Clone the repository (optional, if hosted on GitHub): git clone https://github.com/NishaMehtaN/CV-CT3.git
2.	Install dependencies: pip install opencv-python tensorflow scikit-image pywavelets PyQt5
### Usage
1.	Run the ipynb script
2.	In the GUI, click "Upload Image" to select an RGB image.
3.	View the original, noisy, and denoised images, along with MSE, PSNR, and SSIM metrics.
### Sample Input/Output
1. Input: RGB image (e.g., sample.jpg, 128x128 pixels).
2. Output: GUI displaying Original image, Noisy image (Gaussian noise, $\sigma=0.1$), Denoised images from four methods, Metrics table (e.g., Autoencoder: MSE=0.008, PSNR=31.5, SSIM=0.92).
### Project Structure
1. CT3Final.ipynb: Main application script.
2. CT3Dataset/: Directory for dataset images (update path in script for new data).
3. README.md: Project documentation.
### Requirements
1. Python 3.8+
2. Libraries: opencv-python, tensorflow, scikit-image, pywavelets, PyQt5
3. Hardware: CPU (GPU recommended for faster autoencoder training)
### Notes
1. Update dataset_path in the script to point to your dataset directory.
2. Autoencoder training may take time; adjust epochs or dataset size for faster testing.
3. Ensure images are in PNG, JPG, or JPEG format.
