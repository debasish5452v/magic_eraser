# Magic Eraser - Interactive Background Removal

A real-time computer vision application that lets users erase themselves from video using hand gestures, with particle and lightning effects.

## Features

- Real-time hand tracking and gesture recognition
- Interactive background removal
- Particle effects and lightning animations
- Smooth edge feathering
- User-friendly start button interface
- Keyboard controls for reset and clear

## Requirements

```python
opencv-python>=4.5.0
numpy>=1.19.0
mediapipe>=0.8.9
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/magic-eraser.git
cd magic-eraser
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the program:
```bash
python magicEraser.py
```

2. When the app starts:
   - Step out of frame when prompted for background capture
   - Touch the "START MAGIC" button with your index finger
   - Use your index finger to erase portions of the video
   
3. Controls:
   - `R` - Recapture background
   - `C` - Clear all erased areas
   - `Q` or `ESC` - Quit application

## How It Works

- Uses MediaPipe for hand landmark detection
- Tracks index fingertip position
- Creates a smooth mask for erased areas
- Adds particle effects and lightning for visual feedback
- Blends original frame with captured background

## Technical Details

- Resolution: Adapts to camera resolution
- Frame Rate: Real-time (depends on hardware)
- Supported Platforms: Windows, Linux, macOS
- Camera: Works with built-in and external webcams

## Contributing

Feel free to submit issues, fork the repository and create pull requests for any improvements.

## Acknowledgments

- OpenCV team for computer vision tools
- MediaPipe team for hand tracking
- NumPy team for numerical computations

## Author

Debasish Mahata
