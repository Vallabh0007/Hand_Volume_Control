# Hand Volume Control 
## Description
This repository contains the Python code to develop your volume control using hand gesture recognition system. 

The app consists of 2 different modes:
1. __**Hand tracking Module:**__ This module will detect the presence of hand 
2. __**Volume Hand Control:**__ This will detect a hand by inheriting the above module and will change the volume of system in presence of hand.


## Packages Used
- OpenCV 
- math
- NumPy

## Files
Here's a list of files in the directory:
- `handtracking.py`: Contains all the functions to start and run the app
- `HandTrackingModule.py`: Will detect a hand and the landmarks associated to it
- `VolumeHandControl.py`: Detects landmarks of thumb and index fingers and adjusts volume as per its movements

## Usage
In order to start the application, do the following:
1) Clone the repo
```
git clone https://github.com/Vallabh0007/Hand_Volume_Control.git
```
2) Navigate into the folder, set up a virtual environment and activate it
3) Once you've activated the virtual environment, install the requirements
```
pip install -r requirements.txt
```
4) Navigate into the main folder and run the following command:
```
VolumeHandControl.py
```
6) Some of the features have been included in the snippets in the Application Interface section




## Application Interface
### `Detect Hand`
![Capture Background](imagesandgifs/capturingback.gif)

### `Data Thumb & Index finger`
![Collect Data](imagesandgifs/datamode.png)
![Collect Data 2](imagesandgifs/collecting_data.gif)

### `Alter volume according to hand gestures`
![Test Model](imagesandgifs/testing_model.gif)



