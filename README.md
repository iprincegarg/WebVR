# WebVR Video Player

A simple web-based 360-degree video player built with [A-Frame](https://aframe.io/).

## Features
- **360 Video Playback**: Immersive video experience.
- **Motion Controls**: Look around using mouse drag (desktop) or device orientation (mobile).
- **Local Video Upload**: Play your own 360 MP4 videos directly from your device.

## How to Use
1. **Open the Player**:
   You can open `index.html` directly in your browser.
   
   *Note: For the best experience and to avoid CORS (security) issues with some browsers, it is recommended to run a local server.*

   **Using Python (Recommended):**
   ```bash
   # Navigate to the project directory
   cd /path/to/webvr
   
   # Start a simple HTTP server
   python3 -m http.server
   ```
   Then open `http://localhost:8000` in your browser.

2. **Controls**:
   - **Play Video**: Click the play button to start.
   - **Upload**: Click "Upload Local Video" to select a file from your computer.
   - **Look Around**:
     - **Desktop**: Click and drag on the screen.
     - **Mobile**: Move your phone around (gyroscope) or drag on screen.
   - **Seek (Double Tap/Click)**:
     - **Rewind 10s**: Double click/tap the **LEFT** side of the screen.
     - **Forward 10s**: Double click/tap the **RIGHT** side of the screen.
   - **Keyboard Shortcuts**:
     - **Space**: Play/Pause
     - **Left Arrow**: Rewind 10s
     - **Right Arrow**: Forward 10s
