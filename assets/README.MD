# Voice Command Detection and Explosion Effect

This project implements a voice command detection system that listens for the Thai word "ระเบิด" ("explode"). Upon detecting the command, the program plays an explosion video along with a sound effect.

## Features
- **Voice Command Recognition**: Listens for the specific word "ระเบิด" using Google Speech Recognition API.
- **Explosion Effect**: Plays an explosion video and sound effect for a duration of 5 seconds when the command is detected.
- **Full-Screen Display**: Utilizes Pygame to create a 1920x1080 resolution display for video playback.

## Prerequisites
To run this project, the following dependencies must be installed:

### Python Libraries
- `pygame`
- `pyaudio`
- `numpy`
- `opencv-python`
- `speechrecognition`

### Installation
You can install the required libraries using the following commands:
```bash
pip install pygame pyaudio numpy opencv-python speechrecognition
```

### Additional Setup
- Ensure you have a microphone connected and properly configured.
- Place the explosion video file (`explosion.mp4`) in the same directory as the script.
- Place the explosion sound file (`explosion_sound.mp3`) in a folder named `sounds`.

## How to Run
1. Clone or download the repository.
2. Ensure all dependencies are installed.
3. Run the script:
   ```bash
   python main.py
   ```
4. Speak the word "ระเบิด" into the microphone.
5. The program will play the explosion video and sound effect if the command is recognized.

## Project Structure
- `main.py`: The main script for the project.
- `sounds/explosion_sound.mp3`: The sound effect played during the explosion.
- `explosion.mp4`: The video played during the explosion.

## Limitations
- Requires an internet connection for the Google Speech Recognition API.
- The program may not recognize the word "ระเบิด" in noisy environments.

## Customization
- To change the voice command, modify the word "ระเบิด" in the `detect_voice_command` function.
- Replace `explosion.mp4` and `explosion_sound.mp3` with your own video and sound files for a custom effect.

## Credits
- Developed using Python and popular libraries such as Pygame, OpenCV, and SpeechRecognition.

## License
This project is open-source and available under the MIT License.

