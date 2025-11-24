# Image-Colourization

Convert black-and-white images into vibrant, realistic colour using deep-learning-powered image processing.

## 📸 Overview

**Automatic Image Colouring** is a deep-learning–based project that transforms grayscale images into natural-looking colour versions.
This notebook demonstrates:

- Converting B&W images to LAB colour space

- Passing the L-channel through a pretrained CNN model

- Predicting colour channels

- Recombining channels to form the final colourized output

- Everything runs inside a single Jupyter Notebook for clarity and simplicity.

## ✨ Features

🎨 Automatic B&W → Colour conversion

🤖 Powered by pretrained deep-learning models

🖼️ Works on any photo (portraits, landscapes, architecture)

📓 Clean and easy-to-run Jupyter Notebook

⚡ Realistic and high-quality output

## 🧠 How It Works

- Load grayscale image

- Extract L (lightness) channel

- Pass L through pretrained colourization model

- Predict AB colour channels

- Merge channels into LAB → Convert to RGB

- Display coloured results

## 🛠️ Technologies Used

- Python 3.x

- OpenCV (cv2)

- NumPy

- Matplotlib

- Deep Learning Pretrained Models

- Jupyter Notebook

## 📂 Project Structure

├── AutomaticImageColouring.ipynb   # Main notebook

├── input_images/                   # Add your black & white images

├── output/                         # Colourized outputs

└── README.md

## ▶️ How to Run

### 1. Clone the repository

git clone https://github.com/yourusername/AutomaticImageColouring.git
cd AutomaticImageColouring

### 2. Install dependencies

pip install opencv-python numpy matplotlib

### 3. Launch Jupyter Notebook

jupyter notebook AutomaticImageColouring.ipynb

### 4. Replace input image path

Inside the notebook, set the path to your grayscale image.

### 5. Run all cells

The notebook will colourize your image and display the result.
<img width="851" height="394" alt="download" src="https://github.com/user-attachments/assets/fd141552-35b0-4c00-b26d-dd85ed515603" />


## 🚀 Future Improvements

- Training a custom U-Net / GAN model

- Web app or desktop GUI

- Batch processing

- Real-time colourization

## 🤝 Contributing

Feel free to submit pull requests or suggest improvements!




