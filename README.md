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

## Gesture Recognition Model
The model was built to recognize 7 different hand gestures and the absence of a hand. The encoding of the gestures is included in the demo file under the variable `GESTURE_ENCODINGS`. 
List of gestures recognized (in the order of the encodings):
1. `Fist`</br>
![Fist](imagesandgifs/fist.png)
2. `Five`</br>
![Five](imagesandgifs/five.png)
3. `None`</br>
![None](imagesandgifs/none.png)
4. `Okay`</br>
![Okay](imagesandgifs/okay.png)
5. `Peace`</br>
![Peace](imagesandgifs/peace.png)
6. `Rad`</br>
![Rad](imagesandgifs/rad.png)
7. `Straight`</br>
![Straight](imagesandgifs/straight.png)
8. `Thumbs`</br>
![Thumbs](imagesandgifs/thumbs.png)


## Application Interface
### `Capture Background`
![Capture Background](imagesandgifs/capturingback.gif)

### `Data Collection Mode`
![Collect Data](imagesandgifs/datamode.png)
![Collect Data 2](imagesandgifs/collecting_data.gif)

### `Testing Model Mode`
![Test Model](imagesandgifs/testing_model.gif)



## Questions/Contributions/Future Work
