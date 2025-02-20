# 🖐️ Contactless Keyboard and Mouse 🚀

This project allows users to **control the keyboard and mouse without physical contact** using hand detection with the YOLO model and the MediaPipe library. 🖱️⌨️  

## ✨ Features

✅ **Hand Detection**: Real-time hand tracking using the MediaPipe library.  
✅ **Gesture Recognition**: YOLO model detects and classifies hand movements.  
✅ **Contactless Control**: Move the mouse 🖱️, click 🖲️, and type using a virtual keyboard ⌨️ with just hand gestures.  

## 📦 Requirements

Before running the project, install the following dependencies:  

```bash
pip install opencv-python mediapipe torch numpy pynput
```

- 🐍 **Python 3.x**  
- 📷 **OpenCV** (For image processing)  
- 🖐️ **MediaPipe** (For hand tracking)  
- 🔥 **PyTorch** (For the YOLO model)  
- 🔢 **NumPy**  
- 🎮 **Pynput** (For simulating keyboard and mouse input)  

## 🚀 Installation and Setup

1️⃣ **Clone the repository:**  

```bash
git clone https://github.com/haydarkadioglu/Contactless-keyboard-and-mouse.git
cd Contactless-keyboard-and-mouse/KeyboardAndMouse
```

2️⃣ **Run the main script:**  

```bash
python main.py
```

📌 **Note:** This will activate the camera and track your hand movements to control the mouse and keyboard.  

## 🎮 Usage

- **🖱️ Mouse Control:** Move your hand to control the mouse pointer. Certain gestures allow for left and right clicks.  
- **⌨️ Virtual Keyboard:** Type by selecting keys on an on-screen keyboard using hand gestures.  

## 🛠️ Contributing

🚀 If you want to contribute to this project:  

1. **Fork the repository** 🍴  
2. **Create a new branch:**  
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make changes and commit:**  
   ```bash
   git commit -m '✨ Added new feature: YourFeatureName'
   ```
4. **Push the changes:**  
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Create a Pull Request!** 🔁  

## 📜 License

📝 This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

## 🔗 Links  

📌 [Original Repository](https://github.com/NecatiUlker/Contactless-keyboard-and-mouse.git)

🚀 **Happy coding!** 🎉
