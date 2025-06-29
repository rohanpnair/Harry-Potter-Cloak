🧥 Invisible Cloak using OpenCV

A fun computer vision project that simulates an invisibility cloak effect using OpenCV. When a specific color (in this case, blue) is detected in the webcam feed, it is replaced by a captured background, creating an illusion of invisibility.

📦 Features

Captures background before starting the effect.

Detects a specific color in the frame (HSV color range).

Replaces detected color regions with the previously captured background.

Real-time video display.

Simple and clean implementation with OpenCV.

🛠️ Technologies Used

Python 3

OpenCV

NumPy

📑 How It Works

Capture Background: User moves out of the frame and background frames are captured.

Color Detection: Detects a specific color range (e.g. blue cloak) in each video frame using HSV color space.

Masking: Creates a mask for the selected color and processes it using morphological operations.

Image Blending: Combines background and foreground based on the mask to create the invisibility effect.

Display: Shows the result in real-time. Press 'q' to quit.

