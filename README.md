# Football Match Analysis

![screenshot](https://github.com/RITIKSHARMAOFFICIAL/Football_match_analysis/assets/96929769/e548b2f0-00ef-4da7-8d5b-6e223de27485)


## Introduction

Welcome to the Football Match Analysis project! This project aims to harness the power of artificial intelligence to detect and track players, referees, and footballs in a video using YOLO, one of the leading AI object detection models available. The core objectives of this project include:

1. **Player, Referee, and Football Detection**: Leveraging YOLO for accurate identification and tracking.
2. **Team Assignment**: Using Kmeans for pixel segmentation and clustering to assign players to their respective teams based on t-shirt colors.
3. **Ball Acquisition Analysis**: Measuring each team's ball acquisition percentage throughout the match.
4. **Player Movement Tracking**: Utilizing optical flow to measure camera movement between frames for precise player movement tracking.
5. **Perspective Transformation**: Implementing perspective transformation to convert pixel movement into real-world measurements (meters).
6. **Performance Metrics**: Calculating players' speed and the distance covered during the match.

This project is designed to address real-world problems and is suitable for both beginners and experienced machine learning engineers.

## Modules Used

This project leverages several powerful modules to achieve its goals:

1. **YOLO**: AI object detection model for identifying and tracking objects.
2. **Kmeans**: For pixel segmentation and clustering to detect t-shirt colors.
3. **Optical Flow**: To measure camera movement between frames.
4. **Perspective Transformation**: To represent the scene's depth and perspective.
5. **Performance Metrics**: To calculate speed and distance covered per player.

## Trained Models

The trained models for this project can be accessed via the following link:
[Download Trained Models](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Input Video

The video used for training the model can be accessed via the following link:
[Download Input Video](https://drive.google.com/file/d/1NMkSqE30TF3aKrrQ31-K32MDJIxH1WIM/view?usp=drive_link)

## Sample Output Video

To see the model in action, check out this sample output video:
[Download Output Video](https://github.com/RITIKSHARMAOFFICIAL/Football_match_analysis/blob/main/output_video.avi)

## Project Files

All the files related to this project can be accessed via the following link:
[Download Project Files](https://drive.google.com/drive/folders/1K-5ouOQN-AjKFbQrU0lUwB5GXpgP-Yjs?usp=drive_link)

## Requirements

To run this project, ensure you have the following dependencies installed:

- Python 3.x
- Ultralytics
- Supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/RITIKSHARMAOFFICIAL/Football_match_analysis.git
   ```

2. **Install Dependencies**:
   ```bash
   pip install ultralytics supervision opencv-python numpy matplotlib pandas
   ```

3. **Download Trained Models**: Ensure you have downloaded the trained models from the link provided above and place them in the appropriate directory.

4. **Run the Project**:
   ```bash
   python main.py
   ```

## Contributing

I welcome contributions to enhance this project! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
