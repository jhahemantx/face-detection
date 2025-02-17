# Flask Face Detection App

This is a Flask-based application that captures frames from a webcam, performs face detection using OpenCV, and streams the processed frames back to the client.

## Preview 
![Screenshot 2025-02-17 191942](https://github.com/user-attachments/assets/2f379966-d7dd-4455-a401-736ee4ae08ec)



## Features
- Captures video frames from a webcam.
- Detects faces in real-time using OpenCV.
- Streams the processed video with detected faces.

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Flask
- OpenCV
- NumPy

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/jhahemantx/face-detection.git
   cd face-detection
   ```

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Running the Application

1. **Start the Flask server:**
   ```sh
   python app.py
   ```

2. Open a browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Project Structure
```
flask-face-detection/
│-- app.py              # Flask backend
│-- requirements.txt    # Required Python packages
│-- templates/
│   ├── index.html      # Frontend UI
│-- Haarcascades/
│   ├── haarcascade_frontalface.xml    
```


## Future Enhancements
- Deploy on a cloud service.
- Improve detection with Deep Learning models.
- Implement a WebSocket-based streaming solution.

---
### **Author**: Hemant Jha


