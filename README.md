# 🍽️ MouthCatcher - A Fun Gesture-Controlled Game!

MouthCatcher is a fun and educational game for kids that uses computer vision to detect mouth gestures! The game challenges players to "catch" eatable items by opening their mouth while avoiding non-eatable items. Using the camera, the game detects mouth gestures, making it an interactive and engaging experience for children.

## 🎮 Game Features

- **Interactive Gameplay**: Catch eatable items by opening your mouth to score points!
- **Fun with Learning**: Helps kids improve coordination and teaches about different foods.
- **Computer Vision**: Uses AI to detect whether the mouth is open or closed.
- **Real-Time Feedback**: Immediate visual feedback to make the game more engaging.
- **Game Over Logic**: The game ends if a player "eats" a non-eatable item!

## 🛠️ Technology Stack

- **Python**: Core programming language for the game logic.
- **OpenCV**: For real-time camera feed and image processing.
- **Mediapipe & CVZone**: For facial landmark and gesture detection.
- **AI-Powered FaceMesh**: Detects mouth opening and closing gestures.
  
## 🚀 How to Run the Game

1. **Clone the Repository**  
   Clone the game repository to your local machine:
   ```bash
   git clone https://github.com/Deepak-Vasoya/MouthCatcher.git
   cd MouthCatcher
   ```

2. **Install the Required Dependencies**  
   Ensure you have Python and the necessary libraries installed:
   ```bash
   pip install opencv-python mediapipe cvzone
   ```

3. **Run the Game**  
   Start the game by running the Python script:
   ```bash
   python main.py
   ```

## 🧠 How It Works

- **Mouth Detection**: The game uses face mesh detection to identify mouth gestures.
- **Eatable vs. Non-Eatable**: Items fall from the top of the screen. If the player opens their mouth for eatable items, they score points. If they open their mouth for non-eatable items, the game ends.
- **Real-Time Feedback**: Visual cues are provided to guide players and make the experience more immersive.

## 📂 Project Structure

```bash
.
├── Objects/
│   ├── eatable/      # Images of eatable items
│   └── noneatable/   # Images of non-eatable items
├── main.py           # Main script for the game
└── README.md         # Game documentation
```

## 📈 Future Enhancements

- **Additional Game Levels**: Introduce multiple levels with increasing difficulty.
- **New Gesture Controls**: Add more gestures for special powers or extra points.
- **Voice Commands**: Introduce voice commands to enhance the gaming experience.

## 📜 License
This project is licensed under the MIT License.

## 🙌 Acknowledgements

- **OpenCV**: For real-time video processing.
- **Mediapipe**: For efficient hand and face detection.
- **CVZone**: Simplifying gesture recognition for computer vision projects.

