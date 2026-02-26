# ✋ Hand Hover Drawing App (OpenCV + MediaPipe)

Draw on your screen using your hands — no mouse or touchscreen required!  
This interactive project uses **OpenCV** and **MediaPipe** to detect hand landmarks and allows you to draw in real-time by hovering your fingers in front of the webcam.

---

## 🚀 Features
- 🖐️ **Hand Tracking:** Real-time detection using MediaPipe.
- ✏️ **Air Drawing:** Move your index finger to draw freely on the screen.
- 🎨 **Color Selection:** Change brush colors using gesture-based selection.
- 🧽 **Eraser Mode:** Use a gesture to erase drawings.
- 🧼 **Clear Screen:** Instantly clear everything with a command gesture.
- ⚡ **Real-time Processing:** Smooth and fast performance with OpenCV.

---

## 🧠 Tech Stack
- **Language:** Python  
- **Libraries:**  
  - [OpenCV](https://opencv.org/)  
  - [MediaPipe](https://developers.google.com/mediapipe)  
  - NumPy

---

## 🖥️ How It Works

::contentReference[oaicite:0]{index=0}

1. The webcam captures your hand in real time.  
2. MediaPipe detects the **21 hand landmarks** and tracks the movement of your index finger.  
3. Based on finger position and gesture, drawing actions are performed (draw, erase, or clear).  
4. The drawn output is displayed dynamically using OpenCV.

---

## 🧩 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/HandHoverDrawing.git
   cd HandHoverDrawing
   ```

2. **Install dependencies**
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Run the project**
   ```bash
   python hand_hover_drawing.py
   ```

---

## 📸 Demo Preview

::contentReference[oaicite:1]{index=1}

*(Add a GIF or image of your app here – for example a short screen recording of air drawing.)*

---

## 🧑‍💻 Author
**Ayush Pradhan**  
💼 Full Stack + AI Enthusiast | 🎯 Focused on practical AI & Computer Vision Projects  
🔗 [LinkedIn](https://linkedin.com/in/your-link) | [GitHub](https://github.com/your-username)

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub — it helps others find it too!

---

### 🧩 Future Ideas
- Add **shape recognition** (circle, rectangle)  
- Integrate with **AI sketch completion**  
- Add **gesture-based UI buttons**  
