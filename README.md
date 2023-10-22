# Basirah---Automated-Baggage-Scanning-System

# Project Pref:
Basirah is an automated baggage screening system that uses computer vision and deep learning to detect threats in luggage, improving security scans at airports and other facilities.

The goal of this project is to implement an object detection system using YOLOv8 to detect prohibited items in luggage. By identifying restricted items automatically, the system aims to streamline security checks while maintaining safety.

# Features
- YOLOv8 object detection model trained to recognize prohibited items
- Upload single or multiple images for scanning
- Draws bounding boxes on detected prohibited items
- Determines baggage status based on item labels
- Displays summary of detected prohibited items
  
---

# Install
Clone this repository: `git clone https://github.com/0raghad/basirah`
Go to the root of cloned repository
Install dependencies by running `pip3 install -r requirements.txt`

---

# Run
`python API.py`

This will start a web server on `http://localhost:8080`

The web interface allows users to upload an image. The image will be passed through the object detection model to identify any prohibited items. Bounding boxes will be drawn around each detected object along with the label.

Additionally, the status of the baggage ("Allowed" or "Not Allowed") will be displayed based on whether any prohibited items were found. A breakdown of detected prohibited items is also shown.

