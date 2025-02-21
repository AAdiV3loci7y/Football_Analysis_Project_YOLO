# ⚽ Football Analysis with YOLO
![pixelcut-export](https://github.com/user-attachments/assets/945b900a-fcc2-4d59-b915-4952a6b85313)


## 📌 End Result
[📌 Output Video](https://drive.google.com/file/d/1q33gTcND2ymhqlDxZO0rXwmJjbF2Hcnv/view?usp=drive_link) |

## 📌 Introduction
This project leverages **YOLO (You Only Look Once)**, a state-of-the-art object detection model, to **detect and track players, referees, and footballs** in match footage. By combining **machine learning techniques** with **computer vision**, we can analyze team performance, player movements, and game strategies effectively.

### 🔹 Key Features
- **Object Detection & Tracking**: Detects players, referees, and the ball using YOLO.
- **Team Classification**: Uses **KMeans clustering** to assign players to teams based on t-shirt colors.
- **Ball Possession Analysis**: Determines the percentage of time each team has the ball.
- **Camera Movement Estimation**: Uses **optical flow** to adjust for frame transitions and enhance movement tracking.
- **Player Speed & Distance Calculation**: Accurately measures player movements using perspective transformation.

This project is suitable for both **beginners** looking to explore AI-driven sports analytics and **experienced engineers** aiming to refine object detection models.

---

## 🚀 Trained Models
- [📌 Download Trained YOLO v5 Model](https://drive.google.com/file/d/17CuTgjFjfJ2wYrCIAvnDxRt2LsDIb1PD/view?usp=drive_link)

## 🎥 Sample Video
- [📌 Sample Input Video](https://drive.google.com/file/d/1hyw5HtirKnBurVeDY_0MhkPLQbjWLnHk/view?usp=drive_link)

---

## 🔧 Installation & Requirements
To set up and run this project, ensure you have the following dependencies installed:

### **1️⃣ Prerequisites**
- Python 3.x
- **Libraries:**
  ```bash
  pip install ultralytics supervision opencv-python numpy matplotlib pandas
  ```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/YourUsername/Football_Analysis_Project_YOLO.git
cd Football_Analysis_Project_YOLO
```

### **3️⃣ Run the Model**
```bash
python main.py
```

---

## 📊 Results & Applications
- **Performance Analysis:** Helps coaches and analysts track player movements and ball possession.
- **Scouting & Recruitment:** Identifies player strengths and weaknesses using movement and possession stats.
- **Broadcast Enhancement:** Provides live tracking data for sports commentators and analysts.

---

## 🤝 Support
If you found this project useful, **consider giving it a ⭐ on GitHub!**

---

### **📜 License**
This project is licensed under the **MIT License**. See `LICENSE` for details.
