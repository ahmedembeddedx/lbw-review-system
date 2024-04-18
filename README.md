# LBW Review System

## Overview
The LBW (Leg Before Wicket) Review System is a project aimed at detecting and analyzing ball movements in cricket matches, particularly focusing on LBW scenarios. The system utilizes the YOLOv8 algorithm for ball detection, trained on a diverse dataset consisting of various cricket balls (pink, red, white) and other balls such as tennis balls.

## Dataset
The YOLOv8 model has been trained on a comprehensive dataset available on [Roboflow](https://universe.roboflow.com/cricket-2rxrt/cricket-ball-detection/dataset/1). This dataset includes a wide range of cricket ball images captured from different angles and under various lighting conditions, enhancing the model's ability to accurately detect balls during matches.

## Metrics
The performance of the trained YOLOv8 model is evaluated using the following metrics:
- Mean Average Precision (mAP): 83.0%
- Precision: 98.9%
- Recall: 71.4%

![Metrics Image](https://storage.googleapis.com/roboflow-platform-cache/tK1MTcXnQBerH07Z5XG0a07fY6M2/0UFJ6Xr15lnGmKBJQ9A6/3/results.png)

## Implementation
<img src="https://i.ibb.co/ct2R2W5/Screenshot-2024-04-18-at-11-29-09-PM.png" alt="Screenshot-2024-04-18-at-11-29-09-PM" border="0">
<img src="https://i.ibb.co/1mtfwhL/Screenshot-2024-04-18-at-11-29-22-PM.png" alt="Screenshot-2024-04-18-at-11-29-22-PM" border="0">
<img src="https://i.ibb.co/2S3959w/Screenshot-2024-04-18-at-11-29-45-PM.png" alt="Screenshot-2024-04-18-at-11-29-45-PM" border="0">
<br>
### Some Overfitting
<br>
<img src="https://i.ibb.co/xmPtYRH/Screenshot-2024-04-18-at-11-29-31-PM.png" alt="Screenshot-2024-04-18-at-11-29-31-PM" border="0">

## Usage
To utilize the LBW Review System:
1. Clone the repository: `git clone https://github.com/ahmedembeddedx/lbw-review-system`
2. Install the necessary dependencies.
3. Run the provided scripts for inference on cricket match videos or live streams.
4. Analyze the output for LBW scenarios and review decisions.

## Contributing
Contributions to the LBW Review System are welcome! If you have suggestions for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License -
