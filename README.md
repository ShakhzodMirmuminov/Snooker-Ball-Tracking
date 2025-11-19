# Snooker-Ball-Tracking

A computer vision-based tool for tracking individual snooker balls in pool game videos. This project provides precise ball detection, trajectory analysis, and visualization for snooker/pool game analysis.


## Features

- **Multi-ball Detection**: Track blue, black, white, or custom colored balls
- **Red Table Support**: Optimized for red-background snooker tables
- **Real-time Processing**: Process video files with adjustable parameters
- **Trajectory Visualization**: Draw ball paths and movement patterns
- **Multiple Output Formats**:
  - Tracked video with ball path
  - Ball-only isolated video
- **Perspective Correction**: Top-down view transformation for accurate positioning

## Installation

### Prerequisites
- Python 3.13.5+
- OpenCV
- NumPy
- Pandas

### Install Dependencies
```bash
pip install opencv-python numpy pandas 
```
# Usage
## Basic Ball Tracking
``` python 
from main import track_ball_two_outputs

# White ball tracking in red tables 
track_ball_two_outputs(
    video_path="video_of_your_game.mp4",
    ball_type="white",  # "white", "black", or "blue"
    output_tracked="tracked_output.mp4",
    output_ballonly="ball_only.mp4"
) 
```
## Command Line
```bash 
Code .
```
You can copy and paste to jupyter notebook  or in google collab you can use easily, git clone, change the colour of ball, table and it would easily track the ball.
```
## Output 
![image1](/img/3.png)
![image](/img/1.png)
![image2](/img/2.png)
