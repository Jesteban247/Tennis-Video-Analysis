# 🎾 AI Tennis Video Analysis

Welcome to the AI Tennis Video Analysis project! This repository contains code to detect, track, and analyze the movements of a tennis ball, players, and key points on the court using advanced deep learning techniques. The project leverages YOLO for player detection, a custom neural network for ball tracking, and a ResNet50 model for detecting court keypoints.

## 🎥 Video Demo




https://github.com/Jesteban247/Tennis-Video-Analysis/assets/135396733/12e86557-0b47-48df-84de-f32a7d420205



We have provided example output videos to showcase the performance of the models. You can find these videos in the videos directory.

## 🧠⚡ Features
- 🎾 Ball Detection and Tracking: Uses a customized TrackNet model to accurately detect and track the tennis ball in each frame of the video.
- 🏃‍♂️ Player Detection: Employs a YOLO v8 model to detect and track players on the court.
- 🏟️ Court Keypoints Detection: Detects key points on the tennis court using a pretrained ResNet50 model, refined for this specific task.
- 🌐 MiniMap Overlay: Displays a real-time minimap overlay showing player and ball positions on the court.
- 📊 Speed Calculation: Calculates and displays the speed of the tennis ball in km/h.

## 🚀 Usage
1. Open the `Project.ipynb` notebook.

2. Change the paths to your specific file locations if needed:
   ```python
	path_video = 'Tennis-Video-Analysis/Videos/Inputs/Test_1.mp4'
	path_ball_model = 'Tennis-Video-Analysis/Models/ball.pt'
	path_player_model = 'Tennis-Video-Analysis/Models/best.pt'
	path_keypoints_model = '/Tennis-Video-Analysis/Models/keypoints_model.pth'
	path_connections_file = 'Tennis-Video-Analysis/Configs/court_connections.txt'
	path_output_video = 'Tennis-Video-Analysis/Videos/Inputs/Test_output_1.mp4'
   ```

3. Run all cells in the notebook to process the video and generate the output.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Jesteban247/Tennis-Video-Analysis/blob/main/LICENSE) file for details.
