# Handwritten Digit Recognizer

A standalone Windows application that uses deep learning to recognize handwritten digits (0-9) in real-time.

![Version](https://img.shields.io/badge/version-1.0-blue)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey)

## 📖 Overview

- A machine learning application that recognizes handwritten digits (0-9)
- Uses a Convolutional Neural Network (CNN) trained on the MNIST dataset
- The model achieves ~98-99% accuracy
- Processes your drawings in real-time to predict which digit you wrote

## ✨ Features

- **Draw digits with adjustable brush size** - Use slider to change pen thickness
- **Real-time prediction with confidence scores** - Get instant predictions with confidence percentages
- **View preprocessed images** - See how the model processes your drawing
- **MNIST example digits for reference** - View sample digits from the training dataset
- **CNN-based deep learning model** - Powered by TensorFlow and Keras

## 🚀 Getting Started

### System Requirements

- **Windows 10/11** (64-bit)
- **4GB RAM** minimum (8GB recommended)
- **~1GB free disk space**

### Installation

**No installation required!** This is a standalone executable.

1. Download `DigitRecognizer.exe` from the `dist` folder
2. Double-click the file to run
3. Wait ~30 seconds for the model to train (first time only)

## 📝 How To Use

### Basic Usage

1. **Wait for model training** - On first run, the app will train the model (~30 seconds). A status bar shows progress.
2. **Draw a digit** - Use your mouse to draw a digit (0-9) on the white canvas
3. **Click "Predict Digit"** - See the prediction with confidence scores
4. **View results** - Check the predicted digit and top 3 predictions
5. **Try another digit** - Click "Clear Canvas" to start fresh

### Additional Features

- **Adjust Brush Size** - Use the slider to change pen thickness
- **Show Processed** - Click to see how the model preprocesses your drawing
- **Show Examples** - View MNIST-style example digits for reference

### Tips for Best Results

- Draw digits **LARGE and CENTERED** on the canvas
- Make your digits **CLEAR and DISTINCT**
- Avoid making loops too close to each other
- For digit 9, make both loops clear and distinct
- Click 'Show Examples' to see MNIST-style digits
- Try 'Show Processed' to see what the model sees

## 🔍 Understanding Results

- **Predicted Digit**: The most likely digit (0-9)
- **Confidence**: How certain the model is (0-100%)
- **Top 3 Predictions**: The three most likely digits
- **Higher confidence** = more certain prediction
- If confidence is low (<50%), try redrawing clearer

## 🛠️ Technology

Built with:

- **TensorFlow 2.20.0** - Deep Learning Framework
- **Python 3.13.1** - Programming Language
- **Tkinter** - Graphical User Interface
- **PIL (Pillow)** - Image Processing
- **NumPy** - Numerical Computing
- **Matplotlib** - Data Visualization

### Model Architecture

- **Type**: Convolutional Neural Network (CNN)
- **Training Data**: 60,000 handwritten digit images from MNIST dataset
- **Test Accuracy**: ~98-99%
- **Processing**: Real-time digit recognition
- **First Run**: ~30 seconds (one-time training)
- **Predictions**: Instant after training

## 📦 File Size

- The executable is approximately **500-700 MB** due to TensorFlow
- This is normal for machine learning applications
- All dependencies are bundled - no Python installation needed!

## 🤝 Sharing the App

### Option 1: Single File (Simple)

- Just share the `DigitRecognizer.exe` file
- Recipients can double-click to run (no installation needed!)

### Option 2: ZIP Archive

- Compress `DigitRecognizer.exe` into a ZIP file
- Share the ZIP file
- Recipients extract and run

## 🐛 Troubleshooting

### Common Issues

**Wrong prediction?**

- Try drawing larger and clearer
- Make your digit more distinctive
- Check if you're drawing in the center of the canvas

**Low confidence?**

- Make your digit more distinctive
- Avoid ambiguous shapes
- Try drawing larger

**Can't draw?**

- Check if mouse is working properly
- Try adjusting brush size
- Restart the application

**Model still training?**

- Wait for green status bar to complete
- This only happens on first run (~30 seconds)
- Subsequent runs are instant

**Need reference?**

- Click 'Show Examples' to see proper digit styles
- Try to match the MNIST example format

## 📧 Contact

**Creator**: Roslan M. Amin  
**Email**: [roslan.amin@gmail.com](mailto:roslan.amin@gmail.com)

## 📄 License

© 2025 Roslan M. Amin. All rights reserved.

## 🙏 Acknowledgments

- **MNIST Dataset** - For providing the training data
- **TensorFlow Team** - For the deep learning framework
- **Python Community** - For the amazing tools and libraries

---

**Version**: 1.0  
**Build Date**: October 7, 2025  
**Platform**: Windows 10/11 (64-bit)
