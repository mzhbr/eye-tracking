👁️ Eye Tracking with Python
A real-time eye tracking system built with Python, OpenCV, and dlib — detecting and following eye movements through a webcam feed.

Why This Matters

Eye movement patterns are clinically significant biomarkers. Abnormal saccades and fixation patterns have been linked to:
ASD (Autism Spectrum Disorder) — atypical gaze patterns during social interaction
Schizophrenia — smooth pursuit eye movement deficits

ADHD — irregular fixation stability
This project was my first step into computational neuroscience — bridging computer vision with brain-behavior research.

Demo

Run the script, look at your webcam — the system detects and tracks your eye region in real time.


How to Run
# Clone the repo
git clone https://github.com/mzhbr/eye-tracking
cd eye-tracking

# Install dependencies
pip install opencv-python dlib

# Run
python eye_tracking.py

How It Works:

Webcam captures live video frames
dlib detects 68 facial landmarks per frame
Eye region landmarks (points 36–47) are isolated
OpenCV draws bounding boxes and tracks movement in real time

What I Learned:

Real-time video processing with OpenCV
Facial landmark detection using pre-trained dlib models
The neuroscientific relevance of eye tracking as a non-invasive biomarker
Part of my journey from Computer Engineering → Computational Neuroscience (MSc, Bahçeşehir University)
