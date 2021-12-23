# Multiclass Classification by mmWave FMCW Radars using Machine Learning on Range-Angle Images

## Introduction
The range of applications of Frequency-Modulated Continuous Wave (FMCW)
Radars has increased over the last few years. They have been used in numerous
applications from automotive industries to the agricultural sector and many
more. In this report, a multiclass classification method for FMCW radar,
operating in frequency in the range 76GHz to 81GHz, is presented. The dataset
consists of Range-Angle Images of four classes namely Buffalo, Cat, Dog, and
Human. Object Detection model YOLO v3 is applied to get the results. The
mean average precision achieved is 98.32%.

## System Description
The system consists of Texas Instruments FMCW mmWave Radar, which is
operated in the frequency range 76GHz to 81GHz. It consists of three
transmitters and four receivers. The radar is oriented by 90 degrees for the
experiments conducted. 100 frames, with a frame periodicity of 40ms, are
collected and are stored in binary format. This binary file is later post-processed
in MATLAB.

## Measurements and Signal Processing
There are four classes in this experiment, namely Buffalo, Cat, Dog and Human.
The experiments are conducted in a practical outdoor environment as can be
seen in the below pictures. For Buffalo class, the buffalo is placed at 8m from
the radar and its side view is measured. For Cat class, two cases are measured,
5m and 7m from the radar, and its side view is used. For Dog class, the dog is
placed at 6m from the radar and its side view is used. And lastly, for the Human
class, there are two cases, 5m and 9m. The collected raw binary files are post-
processed in MATLAB to generate Range-Angle heatmap images.

## Dataset
Dataset
The dataset consists of heatmap images which are generated from the binary
raw file using MATLAB. The best ones are selected, and a total of 628 images
are generated. Out of which, 483 images are used for training and 145 for
testing. 

Following are some of the samples of the dataset in the order top-left and top
right buffalo and cat respectively, and bottom left and bottom right dog and
human respectively.

<img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/sample_imgs/Picture1.jpg" width="500"/> <img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/sample_imgs/Picture2.jpg" width="500"/>
<img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/sample_imgs/Picture3.jpg" width="500"/> <img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/sample_imgs/Picture4.jpg" width="500"/>

## Preprocessing
For the data to be fed into the YOLO model, markings are made to each image
which will act as ground truth for our model. LabelImg software is used to mark
the bounding boxes on the images. A text file is generated for each image which
contains its class, x-coordinate, y-coordinate, width and height.

## Performance Metrics and Results
Three performance metrics are used to validate the results, precision, recall and
F1-score.

The test is run for 2400 iterations and the mean average precision calculated is
98.32%, with the average IoU being 74.64%. The test set consists of 145
samples, and 142 are being rightly classified. As shown in the below screenshot,
the model has rightly predicted Buffalo 100%, Cat 100%, Dog 100% and
Human 93.28%. Performance metrics calculated are: precision 0.97, recall 0.98
and F1-score 0.98.

<img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/accuracy.jpg" width="500"/>

## Detections
<img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/detections/Picture1.jpg" width="500"/> <img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/detections/Picture2.jpg" width="500"/>
<img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/detections/Picture3.jpg" width="500"/> <img src="https://github.com/ahmedrehman16/Multiclass-Classification-Using-FMCW-Radars/blob/main/images/detections/Picture4.jpg" width="500"/>
