# Motion Detection Alarm with OpenCV

This Python script uses OpenCV to detect motion in a live video feed from your webcam. When motion is detected, an alarm sounds. You can toggle the alarm on and off using the 't' key and quit the program with the 'q' key.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- imutils (`pip install imutils`)
- winsound (for Windows)

## How to Use

1. Clone this repository or download the script.

2. Install the required libraries using the provided commands.

3. Run the script using Python:

   ```bash
   python MotionAlarm.py

# Working 
- The webcam feed will appear, and motion detection is turned off initially.
- Press 't' to toggle motion detection on and off.
- If motion is detected for a certain period (default is 30 frames), an alarm will sound.
- Press 'q' to quit the program.

#  Customization
You can adjust the frame width and height by changing the values in the `cap.set(...)` lines.
You can customize the alarm sound by modifying the `winsound.Beep(...)` line in the `beep_alarm()` function.
