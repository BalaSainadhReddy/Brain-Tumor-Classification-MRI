# 🧠 Brain Tumor Classification & Grad-CAM Visualization

This project implements a deep learning model using ResNet18 to classify brain tumors from MRI scans and provides Grad-CAM visualizations to highlight important regions in the images.

## 📂 Project Structure

brain-tumors/
├── app/ # Flask application
├── model/ # Model training & Grad-CAM notebooks
├── brain_tumor_resnet18.pth # Trained PyTorch model weights
├── requirements.txt # Python dependencies
├── README.md # This file
└── .gitignore # Files & folders to exclude from version control

markdown
Copy
Edit

## 🚀 Features

- Predicts brain tumor classes from MRI images using ResNet18.
- Generates Grad-CAM heatmaps to visualize model attention.
- Flask web app for user-friendly interface.

## ⚙️ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/brain-tumors.git
   cd brain-tumors
(Optional) Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
🏃‍♂️ Usage
Run the Flask app

bash
Copy
Edit
cd app
python app.py
Open your browser at http://127.0.0.1:5000.

View Grad-CAM visualizations
Check the Grad_cam/ notebook for generating heatmaps.

📷 Example

Grad-CAM highlighting tumor regions.

📝 Credits
This project is based on and adapted from an existing open-source project:
🔗 Original Repository:(https://github.com/Vnadh/brain-tumors)

Model: ResNet18

Visualization: Grad-CAM

Improvements and frontend built using Flask.

Additional enhancements, structuring, and explanations added by Your Name

🛡️ License
MIT License

vbnet
Copy
Edit
MIT License

Copyright (c) 2025 <your-name>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
👨‍💻 Author
Your Name — M.Bala Sainadh Reddy

yaml
Copy
Edit

---
