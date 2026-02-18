# 🥦 SmartSort - AI Powered Produce Classifier 🍎

**SmartSort** is an AI-powered web application that detects whether fruits and vegetables are *fresh* or *rotten* using deep learning (VGG16). Built with a modern UI and deployed on Render, this tool provides instant quality analysis with a single image upload.

---

## 🚀 Live Demo

🔗 **[SmartSort Live App](https://smartsort-backend.onrender.com)**
click the link and wait a minute to load the application and then refresh or open in a new tab

---

## 📸 Demo Visuals

### 🏠 Home Page  
<img width="1920" height="1080" alt="Screenshot (583)" src="https://github.com/user-attachments/assets/e0077ba9-62bf-4c46-a363-21e29d5d758c" />
<img width="1920" height="1080" alt="Screenshot (584)" src="https://github.com/user-attachments/assets/14759493-afa4-42a9-ab67-33e471d46b75" />


### 🔍 Predict Page  
![Predict](https://raw.githubusercontent.com/vamsi746/smartsort/main/Executablefiles/static/img/predict.JPG)

### 📈 Result Output  
![Result](https://raw.githubusercontent.com/vamsi746/smartsort/main/Executablefiles/static/img/result1.JPG)

### About
![About](https://raw.githubusercontent.com/vamsi746/smartsort/main/Executablefiles/static/img/about.JPG)

### Contact
<img width="1920" height="1080" alt="Screenshot (590)" src="https://github.com/user-attachments/assets/d27a0342-1ae6-400e-aaab-c3a6faafb5d3" />

<img width="1920" height="1080" alt="Screenshot (591)" src="https://github.com/user-attachments/assets/ea302184-6a30-404f-a82e-e238ae36fe65" />


## 🎥Demo Video:
https://drive.google.com/file/d/1W26DcKPSnwxO8gVYwLsN2Tkug1zpECqo/view?usp=sharing

# 📄Project Documents
https://drive.google.com/drive/folders/1lO8CeXBpDSK54ffyY4JHPWkCMBCORJ2F?usp=sharing
## access all the project related templates and reports here 


## 💡 Features

- ✅ Upload an image of a fruit or vegetable  
- ✅ Predict whether it’s **Healthy** or **Rotten**  
- ✅ Stunning modern UI with dark theme and glassmorphism  
- ✅ Fully responsive for all devices  
- ✅ Backend powered by Flask + TensorFlow (VGG16)  
- ✅ Hosted & Live on Render

---

## ⚙️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python Flask  
- **Deep Learning:** TensorFlow, Keras, VGG16  
- **Deployment:** Render (Backend), GitHub Hosting  

---
## 🗂️ Project Structure
```
smart-sorting/
│
├── app.py # Flask backend
├── healthy_vs_rotten.h5 # Trained model
├── requirements.txt
│
├── templates/ # HTML files
│ ├── index.html
│ ├── about.html
│ ├── contact.html
│ ├── predict.html
│ └── output.html
│
├── static/
│ ├── css/
│ │ └── style.css
│ └── img/
│ ├── banner.jpg
│ ├── email.png
│ ├── github.png
│ └── linkedin.png
│
└── screenshots/
├── home.png
├── predict.png
└── contact.png


```
## 📦 How to Run Locally
```
# Clone the repository
git clone https://github.com/vamsi746/smartsort.git
cd smartsort

# Optional: create virtual environment
python -m venv venv
venv\Scripts\activate     # For Windows
# source venv/bin/activate  # For macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Run the Flask application
python app.py


Then open http://127.0.0.1:5000 in your browser.


```
## 👥 Team Members

| Name             | Role               | 
|------------------|--------------------|
| Durga Mallula  | Team Lead | 
|   Koppineedi Lakshmi prasanna     | Team Member    | 
|    Pramila Kumpatla | Team member  |
|   Vijay Thota | Team member | 

## 🎯 Use Cases-
🏭 Factories: Automated sorting of fresh vs rotten produce

🛒 Supermarkets: Quality check at delivery docks

🏠 Smart Homes: Alert users to use produce before it spoils

🙌 Acknowledgements-
Kaggle Dataset – for the fruit and vegetable dataset

TensorFlow – deep learning framework

VGG16 – pre-trained model for transfer learning

Flask – lightweight Python web framework


## 🧑🏻‍💻 Prasanna Koppineedi
## 🔗 GitHub: https://github.com/prasannaKoppineedi01
## 🔗 LinkedIn: https://www.linkedin.com/in/prasanna-koppineedi-249825316

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.



