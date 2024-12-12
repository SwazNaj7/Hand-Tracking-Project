# Hand-Tracking-Project

This project implements hand tracking using OpenCV and MediaPipe. It includes several scripts to demonstrate hand tracking and control volume using hand gestures.

## Project Structure

### Files

- `handtrackingmodule.py`: Contains the `handDetector` class for detecting hands using MediaPipe.
- `handtrackmin.py`: A minimal example demonstrating hand tracking.
- `myHandTracker.py`: Uses the `handDetector` class to track hands.
- `VolumeHandControl.py`: Controls the system volume using hand gestures (not provided in the excerpts).
- `requirements.txt`: Lists the dependencies required for the project.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/SwazNaj7/Hand-Tracking-Project
    cd Hand-Tracking-Project
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Running the Hand Tracking Module

To run the hand tracking module, execute the following command:
```sh
python handtrackingmodule.py
```
To use the volume hand control script, execute the following command:
```sh
python VolumeHandControl.py
