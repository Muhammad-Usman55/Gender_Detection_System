# Gender Detection System

This project is a deep learning-based gender detection system using PyTorch. It includes model training, inference pipeline, and testing on images. The project utilizes facial features to predict the gender of individuals in images.

## 📁 Project Structure
```
Gender_Detection_System/
├── main.ipynb              # Main logic and pipeline for gender detection
├── Pipeline.ipynb          # Additional pipeline steps
├── best_Gender.pt          # Trained gender classification model
├── best_Classifier.pt      # Another model (e.g., classifier for feature extraction)
├── Testing_Images/         # Sample images for testing the model
```

## 🚀 Getting Started

### Clone the Repository
```bash
git clone https://github.com/Muhamad-Usman55/Gender_Detection_System.git
cd Gender_Detection_System
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Code
Open `main.ipynb` in Jupyter Notebook and follow the steps to test gender prediction.

## 📦 Dependencies
- torch
- torchvision
- matplotlib
- numpy
- opencv-python
- PIL

## 🧠 Models
- `best_Gender.pt`: Pre-trained gender detection model.
- `best_Classifier.pt`: Auxiliary model (could be feature extractor or classifier).

## 🖼️ Sample Testing Images
Located in `Testing_Images/` folder.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
