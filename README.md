# Deepfake Detection

This repository contains code for a deepfake detection model, built using Python and TensorFlow. The model is designed to classify media (images and videos) as either genuine or fake based on deep learning techniques.

## Installation

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Python 3.12+ (The project has been tested on Python 3.12.10)
- Pip (Package Installer for Python)

### Setting Up the Environment

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Jojohere/deepfake-detection.git
   cd deepfake-detection
2. **Install dependecies**

   ```bash
   pip install -r requirements.txt

### Usage
Open the application in your browser.

Upload an image or video you want to check.

The model will analyze the media and return a prediction: Genuine or Fake.

### Project Structure
```bash
     deepfake-detection/
  ├── app.py                # Streamlit application entry point
  ├── model/                # Directory containing the trained model
  ├── data/                 # Sample data for testing
  ├── requirements.txt      # Project dependencies
  └── README.md             # Project documentation
