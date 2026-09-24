# Job Gesture Hunting

**Job Gesture Hunting** is an interactive career exploration webpage designed for college students who may not yet know what they want to do after graduation.

Instead of using a traditional career website with search bars, filters, or questionnaires, users explore different career possibilities through hand gestures detected by their webcam.

Move your right hand horizontally to switch between career cards. When a career result appears, hold a thumbs-up gesture for approximately 350 ms to open more details about that career.

All camera processing and gesture recognition happen locally in the browser. Camera footage is not uploaded or stored.

---

## Live Demo

Open the project here:

https://lunake000.github.io/Job-Gesture-Hunting/

For the best experience, please use **Google Chrome** and allow camera access when prompted.

---

## Original Idea

My original idea was to create a career exploration tool for college students who may feel uncertain about what they want to do after graduation.

Most career exploration websites rely heavily on text, search bars, filters, personality tests, or questionnaires. I wanted to experiment with a more playful and embodied interaction model by connecting physical gestures with digital information.

Instead of clicking buttons, users can move their hand to discover different career possibilities and use a thumbs-up gesture when they want to learn more about one of them.

The project explores the question:

**How can physical gestures make digital exploration feel more playful, intuitive, and engaging?**

This project is not only about career information. It is also an experiment in alternative human-computer interaction and how body movement can become part of the interface.

---

## How to Run the Project

### Option 1: Open the Live Website

The easiest way to run the project is to open:

https://lunake000.github.io/Job-Gesture-Hunting/

Then:

1. Open the website in Google Chrome.
2. Click **Start Camera / Start Prediction**.
3. Allow the browser to access your webcam.
4. Place your right hand in front of the camera.
5. Move your right hand horizontally to switch between career options.
6. Hold a thumbs-up gesture for approximately 350 ms to open the career details.
7. Release the gesture and continue moving your hand to explore other careers.

### Option 2: Run Locally

Download or clone this repository.

Navigate to the project folder in Terminal and run:

```bash
python3 -m http.server 8000
