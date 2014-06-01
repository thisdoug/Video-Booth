Video Booth
===========
Frustrated with the photobooth software not allowing 720p video recording this collection of code scripts is intended to creat an easy interface to record 720p video from a webcam directly to a computer.

###The Elements:
- Hardware
- Mac Computer
- Webcam
- Arduino Leonardo w/ Pushbutton

###Software
- Quicktime Player 10
- Automator
- Arduino

###The Setup
The arduino with a pushbutton provides a simple interface for the users (visitors of the wedding) to start and stop the video recording. the Arduino Leonardo is used because of its built in keyboard emulation library.

Running on the mac are a couple of Automator scripts.

- **Startup**, which opens Quicktime 10 and opens a new movie recording, setting it to fullscreen.
- **Start Capture**, which opens a countdown movie full screen so people have a chance to prepare. After the countdown it closes that window and returns to the record window full screen, also begining the recording.
- **Stop Capture**, which stops the recording and saves it. It then opens a new movie recording and sets it to full screen so people can see themselves when they sit down in front of the computer.

