# Vehicle Counting and Speed Estimation using YOLOv8 and OpenCV

This project involves implementing vehicle detection, counting, and speed estimation using YOLOv8 for object detection and OpenCV for subsequent analysis. The system identifies vehicles in videos, counts them, and estimates their speeds based on their movement.

## Project Overview

- **Vehicle Detection with YOLOv8:**
  - Utilized YOLOv8 for accurate vehicle detection in video streams or recorded videos.
  - Employed pre-trained YOLOv8 weights for object detection of vehicles.

- **Vehicle Counting:**
  - Implemented vehicle counting algorithms based on detected bounding boxes to count the number of vehicles passing through defined regions or frames.

- **Speed Estimation:**
  - Utilized frame timestamps and vehicle tracking information to estimate vehicle speeds based on distance covered and time elapsed.

## Project Structure

- `yolov8_detection/`: Contains code for vehicle detection using YOLOv8.
- `vehicle_counting/`: Includes code for vehicle counting algorithms.
- `speed_estimation/`: Holds code for vehicle speed estimation based on tracking information.
- `videos/`: Source videos used for vehicle detection and speed estimation.

## Usage

1. **YOLOv8 Detection:**
   - Access the `yolov8_detection/` directory for YOLOv8 detection code and instructions.
   - Execute the code to detect vehicles in the provided videos or video streams.

2. **Vehicle Counting:**
   - Navigate to the `vehicle_counting/` directory to access vehicle counting algorithms.
   - Run the code to count vehicles based on detected bounding boxes.

3. **Speed Estimation:**
   - Visit the `speed_estimation/` directory for code related to vehicle speed estimation.
   - Execute the code to estimate vehicle speeds using tracking information.

## Requirements

- Python 3.x
- YOLOv8 framework
- OpenCV library for video processing and analysis
- Input videos for vehicle detection and speed estimation

## Resources

- [Link to YOLOv8 Framework Documentation](yolov8_documentation_link)
- [Link to OpenCV Documentation or Tutorials]

## License

This project is licensed under the [License Name] License - see the [LICENSE](LICENSE) file for details.

## Contributors

- [Your Name]
- [Other Contributors, if applicable]
