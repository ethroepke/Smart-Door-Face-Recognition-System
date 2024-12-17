# Smart Door Face Recognition System

A Raspberry Pi-based system for enhancing home security and convenience. This project uses a camera to detect and recognize faces at the door, greeting known visitors and saving images of unknown faces for later identification.

## Features
- **Face Recognition**: Detects and identifies faces using a pre-trained facial recognition model.
- **Greeting System**: Welcomes known individuals with a personalized audio message.
- **Data Storage**: Saves unrecognized faces to a local database for later labeling.
- **Customizable**: Easily add names to unknown faces via a database or web interface.

## Hardware Requirements
- Raspberry Pi 4
- Raspberry Pi Camera Module (or USB webcam)
- USB or 3.5mm speaker
- MicroSD Card (with Raspberry Pi OS installed)
- (Optional) Door sensor for event-based triggering

## Software Requirements
- Raspberry Pi OS
- Python 3
- Libraries:
  - OpenCV
  - `face-recognition` (based on `dlib`)
  - `pyttsx3` (Text-to-Speech)
  - SQLite3 (for local database)
