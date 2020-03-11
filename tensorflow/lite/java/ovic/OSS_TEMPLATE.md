
# Model Name

## Authors
The **1st place winner** of the **4th On-device Visual Intelligence Competition** ([OVIC](https://docs.google.com/document/d/1Rxm_N7dGRyPXjyPIdRwdhZNRye52L56FozDnfYuCi0k/edit#)) of Low-Power Computer Vision Challenge ([LPCVC](https://lpcv.ai/))

* Last name, First name
* Last name, First name
* Last name, First name

## Description
<!-- Provide description of the model -->
The model submitted for the OVIC and full implementation code for training, evaluation, and inference

* OVIC track: Image Classification, Object Detection

### Algorithm
<!-- Provide details of the algorithms used -->

### Software
<!-- Provide details of the software used -->

## Model
|Model|Download|MD5 checksum|
|-|-|-|
|Model Name| Download Link (Size: KB)|MD5 checksum|

The model tar file contains the followings:
* Trained model checkpoint
* Frozen trained model
* TensorFlow Lite model

## Benchmark Results

### [4th OVIC Public Ranked Leaderboard](https://lpcvc.ecn.purdue.edu/score_board_r4/?contest=round4)
#### Image Classification (from the Leaderboard)
|Rank|Username|Latency|Accuracy on Classified|# Classified|Accuracy/Time|Metric|Reference Accuracy|
|-|-|-|-|-|-|-|-|
|1|Username|xx.x|0.xxxx|20000.0|xxx|0.xxxxx|0.xxxxx|

 * **Metric**: Accuracy improvement over the reference accuracy from the Pareto optimal curve
 * **Accuracy on Classified**: The accuracy in [0, 1] computed based only on the images classified within the wall-time
 * **\# Classified**: The number of images classified within the wall-time
 * **Accuracy/Time**: The accuracy divided by either the total inference time or the wall-time, whichever is longer
 * **Reference accuracy**: The reference accuracy of models from the Pareto optimal curve that have the same latency as the submission

#### Object Detection
|Rank|Username|Metric|Runtime|mAP over time|mAP of processed|
|-|-|-|-|-|-|
|1|Username|0.xxxxx|xxx.x|xxx|xxx|
* **Metric**: COCO mAP computed on the entire minival dataset
* **mAP over time**: COCO mAP on the minival dataset divided by latency per image
* **mAP of processed**: COCO mAP computed only on the processed images

## Dataset (Train and validation)

## Validation accuracy

## Training
Provide detailed training information (preprocessing, hyperparameters, random seeds, and environment) 

## Validation
Provide validation script with details of how to reproduce results.

## Inference

### Preprocessing steps

### Postprocessing steps

## References
Link to references

## License
Apache License 2.0
