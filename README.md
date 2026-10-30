# Autonomous Vehicle Lane Detection Using OpenCV

## Project Overview

This project implements a lane detection system for autonomous driving applications using Python and OpenCV. It processes road videos captured from a front-facing camera and identifies lane markings using computer vision techniques.

The system detects lane boundaries and overlays them on the original video to demonstrate how lane detection can support road understanding in autonomous vehicles.

## Objectives

- Detect lane markings from road videos.
- Apply image processing techniques to identify road lanes.
- Highlight detected lane boundaries.
- Generate a processed output video.
- Understand the application of computer vision in autonomous driving.

## Technologies Used

- Python
- OpenCV
- NumPy
- Google Colab
- Matplotlib

## Methodology

The project follows these steps:

1. **Video Input:** Upload a road or dashcam video.
2. **Grayscale Conversion:** Convert video frames into grayscale images.
3. **Gaussian Blur:** Reduce image noise and unnecessary details.
4. **Canny Edge Detection:** Identify edges and lane boundaries.
5. **Region of Interest:** Focus on the road area where lane markings are expected.
6. **Hough Line Transform:** Detect straight-line segments representing lane markings.
7. **Lane Visualization:** Draw detected lane boundaries over the original video.
8. **Output Generation:** Save the processed video as an MP4 file.

## Project Structure

```text
autonomous-vehicle-lane-detection/
│
├── autonomous_vehicle_lane_detection.ipynb
├── autonomous_vehicle_lane_detection.py
├── lane_detection_output.mp4
├── requirements.txt
└── README.md
```

## Output Video

The project generates a processed video showing the detected lane boundaries.

**Output file:** `lane_detection_output.mp4`

[View or Download Lane Detection Output](lane_detection_output.mp4)

## How to Run the Project

### Using Google Colab

1. Open the Jupyter Notebook in Google Colab.
2. Run the notebook cells.
3. Upload a road or dashcam video when prompted.
4. Allow the system to process the video frames.
5. View the lane detection results.
6. Download the generated output video.

### Install Dependencies Locally

```bash
pip install -r requirements.txt
```

Run the Python script:

```bash
python autonomous_vehicle_lane_detection.py
```

## Applications

- Autonomous driving research
- Advanced Driver Assistance Systems (ADAS)
- Road lane monitoring
- Computer vision applications
- Intelligent transportation systems

## Limitations

- Performance depends on video quality and lighting conditions.
- Curved roads may not be detected accurately.
- Rain, shadows, glare, and faded lane markings can affect detection.
- The current implementation uses classical computer vision techniques and is not a complete autonomous driving system.

## Future Enhancements

- Implement deep learning-based lane detection.
- Improve detection on curved roads.
- Add real-time camera processing.
- Integrate lane departure warning functionality.
- Evaluate performance under different weather and lighting conditions.

## Author

**Harish Kumudan**

B.Sc. Data Science

GitHub: [HARI-008](https://github.com/HARI-008)
