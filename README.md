# 🛡️ Smart Security System – IOCL Guwahati Refinery

## 📌 Overview
This project is a *Smart Security Infrastructure* developed during my internship at *Indian Oil Corporation Limited (IOCL), Guwahati Refinery, under the mentorship of **Mr. Prakash Kumar Sinha* (Senior Manager – IS Department).

The system enhances workplace safety and security by integrating *QR-based access control, **real-time face recognition, and **safety gear detection* to ensure compliance and streamline entry/exit monitoring.

---

## 🚀 Features
- 📇 *QR Entry Pass Generation* – Generates unique QR codes for secure access.
- 🧑‍💻 *Real-Time Face Recognition* – Verifies identity instantly using InsightFace buffalo1 with Euclidean distance matching.
- 📊 *Automated Entry/Exit Tracking* – Logs check-ins/outs and generates overtime alerts.
- 🦺 *Safety Gear Detection* – Detects helmets, safety shoes, full suits, and IFR suits using *YOLOv11*.
- ⚡ *Optimized Performance* – Runs efficiently on real-world industrial setups with edge device integration.

---

## 🛠️ Tech Stack

### *Backend*
- Django – Scalable backend for managing authentication, data storage, and processing.
- Django REST Framework – For API communication with frontend.

### *Computer Vision & ML*
- YOLOv11 – For safety gear detection.
- OpenCV & dlib – For QR code reading and face recognition preprocessing.
- InsightFace – For accurate facial matching.

### *Frontend*
- React.js – Integration with backend APIs for a smooth UI/UX.

---

## 📂 Project Structure


📁 SmartSecuritySystem
├── backend/           # Django backend
├── frontend/          # React.js frontend
├── models/            # YOLOv11 and face recognition models
├── scripts/           # Utility scripts
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation

`

---

## ⚙️ Installation & Setup

### **1️⃣ Clone the repository**
bash
git clone https://github.com/<your-username>/SmartSecuritySystem.git
cd SmartSecuritySystem
`

### **2️⃣ Backend setup (Django)**

bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


### **3️⃣ Frontend setup (React.js)**

bash
cd frontend
npm install
npm start

## 🎯 Achievements

* Successfully deployed and tested the system in industrial conditions.
* Optimized detection models for real-time inference on edge devices.
* Strengthened teamwork and adaptability while meeting strict deadlines.

## 🤝 Acknowledgements

Special thanks to *IOCL Guwahati Refinery* for the opportunity and mentorship. 


