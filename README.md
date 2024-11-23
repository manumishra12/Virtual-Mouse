# Virtual Mouse Using Hand Tracking 🖱️

This project implements a **Virtual Mouse** that allows users to control their computer cursor using hand gestures. It leverages **Mediapipe** for real-time hand tracking and **OpenCV** for computer vision processing, providing an innovative and touch-free interface.

![Results](https://github.com/manumishra12/Virtual-Mouse/blob/main/Images/1.png)


![Results](https://github.com/manumishra12/Virtual-Mouse/blob/main/Images/2.png)

---

## 📖 Introduction

The **Virtual Mouse** enables cursor control through hand gestures, bypassing the need for traditional input devices. By detecting hand landmarks and interpreting gestures, it maps hand movements to cursor movements, making it a versatile tool for accessibility and innovation.

---

## ✨ Features

- **Real-time hand tracking** using Mediapipe.
- **Click, drag, and scroll** gestures.
- Easy-to-use and lightweight solution.
- Compatible with any webcam-enabled device.

---

## ⚙️ Requirements

- Python 3.7+
- OpenCV
- Mediapipe
- PyAutoGUI (for controlling mouse functions)
- HandTrackingModule

---

## 💻 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/username/virtual-mouse.git
   cd virtual-mouse
   ```

2. Install the required dependencies:
  ```bash
  pip install -r requirements.txt
   ```

🚀 Usage
- Connect a webcam to your computer.
- Run the script

  ```bash
  python virtual_mouse.py
  ```

## 🛠️ Technical Details

### **Hand Detection**
- **Mediapipe** detects 21 key landmarks on each hand.
- These landmarks are analyzed to determine gestures and control logic.
  

### **Gesture Recognition**
- Specific hand gestures are mapped to mouse functions:
  - **Single Finger Up**: Cursor control.
  - **Two Fingers Up**: Click.
  - **Pinch Gesture**: Drag.
  - **Closed Fist**: Scroll.
    

### **Cursor Movement**
- The screen resolution and hand detection region are mapped using **OpenCV** to accurately translate hand movements into cursor movements.
  

### **Mouse Interaction**
- **PyAutoGUI** handles the actual mouse events, such as:
  - Moving the cursor.
  - Simulating left and right clicks.
  - Performing drag and drop.
  - Implementing scrolling functionality.
    

---

## 🚀 Future Enhancements

- Add support for **multi-hand gesture control**.
- Implement additional gestures for **keyboard emulation**.
- Optimize performance for **low-spec devices**.
- Explore **3D gesture-based interactions** to enhance functionality.

---




## 🛠️ Steps to Run the Virtual Mouse in a Virtual Environment

### 1. **Create a Virtual Environment**
   - Open a terminal and navigate to the project directory.
   - Create a virtual environment using `venv`:
     ```bash
     python -m venv venv
     ```

### 2. **Activate the Virtual Environment**
   - **Windows**:
     ```bash
     .\venv\Scripts\activate
     ```
   - **Linux/macOS**:
     ```bash
     source venv/bin/activate
     ```

### 3. **Install Required Dependencies**
   - Install all the necessary packages from the `requirements.txt` file:
     ```bash
     pip install -r requirements.txt
     ```

### 4. **Run the Virtual Mouse Script**
   - Execute the Python script to start the Virtual Mouse:
     ```bash
     python virtual_mouse.py
     ```

### 5. **Control the Mouse with Gestures**
   - Ensure your webcam is connected and follow these gestures:
     - **Index Finger Up**: Move the cursor.
     - **Index and Middle Finger Up**: Left-click.
     - **Pinch Gesture**: Drag.
     - **Closed Fist**: Scroll.

---

## 🔄 Deactivating the Virtual Environment
   - To deactivate the virtual environment after you're done:
     ```bash
     deactivate
     ```

---

## 📋 Notes
- Make sure your Python version is 3.7 or above.
- Ensure the webcam is enabled and accessible by the script.
- For better performance, use a well-lit environment for hand tracking.

Enjoy controlling your mouse with gestures! 🖐️
Feel free to contribute, suggest improvements, or report issues to make this project even better! 🚀

