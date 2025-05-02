# Invisible Cloak using OpenCV

## 🎭 Overview
This project creates an **invisibility cloak** effect using OpenCV. By capturing the background and applying color detection and masking techniques, a specific-colored object (like a red cloak) can be made to appear invisible in real-time video.

## ✨ Features
- Real-time invisibility effect
- Uses color detection and segmentation
- Background capture for seamless blending
- Works with OpenCV and NumPy

## 📌 Requirements
- Python 3.x
- OpenCV (`cv2`)
- NumPy

Install dependencies using:
```bash
pip install opencv-python numpy
```

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Akshatbhatnagar908/invisible-cloak.git
   ```
2. Navigate to the project directory:
   ```bash
   cd invisible-cloak
   ```
3. Run the script:
   ```bash
   python invisible_cloak.py
   ```
4. Wear a cloak of the defined color and watch the magic happen! 🎩

## ⚙️ How It Works
1. Capture the background before introducing the cloak.
2. Detect the specified color using HSV color space.
3. Create masks to remove the detected color and replace it with the background.
4. Blend the frames to produce an invisibility effect.


## 📜 License
This project is open-source under the **MIT License**.

---
Feel free to contribute and enhance the project! 🚀

https://www.linkedin.com/in/akshatbhatnagar908/



