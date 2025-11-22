# Real-Time-Virtual-Highlighter-using-OpenCV
A fun computer-vision project that turns your finger or a colored object into a virtual highlighter pen. Using OpenCV, the system tracks your fingertip in real-time and draws smooth lines on a digital canvas. Perfect beginner-friendly project to learn color detection, contour tracking, masking, and drawing using OpenCV

Make sure your webcam is connected.

---

## 🖐 How It Works
1. Converts frame to **HSV color space**
2. Detects yellow color range
3. Finds the largest contour
4. Calculates fingertip center (cx, cy)
5. Draws line between previous and current points
6. Updates canvas in real time

---

## 🎥 Demo Output
- Left Side → Webcam feed with tracking dot  
- Right Side → Drawing canvas  

---

## 🛠 Customization

### Change drawing color:
Modify this line:
```python
DRAW_COLOR = (0, 0, 0)  # Black
