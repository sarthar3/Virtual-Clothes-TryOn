# Virtual Try-On 3D

## Overview
Virtual Try-On 3D is an augmented reality (AR) application that allows users to visualize outfits in real time using their webcam. The system uses pose detection and overlays selected clothing images onto the user's body.

## Features
- Password-protected authentication system
- Real-time 3D outfit visualization using AR
- Augmented Reality integration for a lifelike experience
- Simple and intuitive user interface
- Upload front and back views of t-shirts and pants
- Toggle between front and back views manually
- Mouse-based zoom functionality
- Take photos of the try-on session
- Animated floating effects for an enhanced UI experience

## Technologies Used
- HTML, CSS, JavaScript
- Three.js for 3D rendering
- MediaPipe Pose for body tracking
- TensorFlow.js for ML-based pose detection

## File Structure
```
├── index.html   # Authentication page (password-protected access)
├── index2.html  # Main landing page
├── index3.html  # Virtual Try-On application
├── assets/      # (If applicable) Store images, styles, or scripts
```

## Installation & Setup
1. Clone or download the project files.
2. Open `index.html` in a browser.
3. Enter the correct password to proceed to `index2.html`.
4. Click the "Start Virtual Try-On" button to navigate to `index3.html`.
5. Allow camera access when prompted.
6. Upload clothing images and click "Try Dress" to begin the AR experience.

## How to Use
1. Enter the password to access the main page.
2. Upload the front and back images of a t-shirt and pants.
3. Click the "Try Dress" button to start the virtual try-on.
4. Use the "Switch View" button to toggle between front and back clothing views.
5. Use the mouse wheel to zoom in or out.
6. Click "Take Photo" to save a snapshot of your try-on experience.

## Future Enhancements
- Add support for real-time physics-based cloth simulation
- Improve UI with more customization options
- Extend compatibility to mobile devices
- Implement additional clothing categories (e.g., jackets, dresses)
- Enhance authentication system for better security

## License
This project is open-source and free to use. Contributions are welcome!

