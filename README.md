# LBW Review System

## Overview
The LBW (Leg Before Wicket) Review System is a project aimed at detecting and analyzing ball movements in cricket matches, particularly focusing on LBW scenarios. The system utilizes the YOLOv8 algorithm for ball detection, trained on a diverse dataset consisting of various cricket balls (pink, red, white) and other balls such as tennis balls.

## Dataset
The YOLOv9 model has been trained on a comprehensive dataset available on [Roboflow](https://universe.roboflow.com/cricket-2rxrt/cricket-ball-detection/dataset/1). This dataset includes a wide range of cricket ball images captured from different angles and under various lighting conditions, enhancing the model's ability to accurately detect balls during matches.

## Access the pretrained model
[https://universe.roboflow.com/ahmed-ws/ball-detection-3afaq/model/5](https://universe.roboflow.com/ahmed-ws/ball-detection-3afaq/model/5)

## Metrics
The performance of the trained YOLOv8 model is evaluated using the following metrics:
- Mean Average Precision (mAP): 91.9%
- Precision: 86.3%
- Recall: 94.8%

![Metrics Image](https://i.ibb.co/2g5NFkC/download.png)

## Implementation
<a href="https://ibb.co/jHgJLnw"><img src="https://i.ibb.co/V32wvfC/Screenshot-2024-04-18-at-11-29-09-PM.jpg" alt="Screenshot-2024-04-18-at-11-29-09-PM" border="0"></a>
<a href="https://ibb.co/DYFrchM"><img src="https://i.ibb.co/0KLs4T9/Screenshot-2024-04-18-at-11-29-22-PM.jpg" alt="Screenshot-2024-04-18-at-11-29-22-PM" border="0"></a>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/jw1pcGk/Screenshot-2024-04-18-at-11-29-45-PM.jpg" alt="Screenshot-2024-04-18-at-11-29-45-PM" border="0"></a><br>
Some Overfitting
<br>
<a href="https://ibb.co/TLD6N3b"><img src="https://i.ibb.co/5FXmJHn/Screenshot-2024-04-18-at-11-29-31-PM.jpg" alt="Screenshot-2024-04-18-at-11-29-31-PM" border="0"></a>

[![Watch the video](https://img.youtube.com/vi/Oge4KK_aU78/0.jpg)](https://www.youtube.com/watch?v=Oge4KK_aU78)


## Usage
To utilize the LBW Review System:
1. Clone the repository: `git clone https://github.com/ahmedembeddedx/lbw-review-system`
2. Install the necessary dependencies.
3. Run the provided scripts for inference on cricket match videos or live streams.
4. Analyze the output for LBW scenarios and review decisions.

## Contributing
Contributions to the LBW Review System are welcome! If you have suggestions for improvements or encounter any issues, feel free to open an issue or submit a pull request.

## License
This project is licensed under the Apache License
