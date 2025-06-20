# 🚗 Real-Time Car Park Counter

A real-time car park monitoring system using **Computer Vision (CV)** to detect and track available parking spaces from video feeds. The system analyzes each frame, determines which spots are occupied or vacant, and displays the live count of available spaces.

## 🛠️ Features

- Detects and tracks parking space occupancy in real-time
- Processes video feeds from parking lot cameras
- Overlays occupied/vacant status on each spot
- Provides a live count of available parking spaces

## 📹 Demo

![car park demo](carParkImg.png)  
Video: `carPark.mp4`

## 🧠 Technologies Used

- **OpenCV (cv2)** – for image/video processing
- **NumPy** – for numerical operations
- **Pickle** – to store parking position data
- **cvZone** – for easy drawing and visual feedback

## 📁 Project Structure

```bash
.
├── main.py                  # Main script to run the counter
├── ParkingSpacePicker.py    # Tool to manually mark parking spot positions
├── CarParkPos               # Pickle file storing marked positions
├── carPark.mp4              # Sample video of the parking lot
├── carParkImg.png           # Sample image used for README
└── .idea/                   # PyCharm config folder (optional to track)
