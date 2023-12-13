
This directory contains keyframes, features, annotations of two concepts 
(building and explosion_fire) of 6 videos from TRECVID 2005. The keyframes
are stored in the following directory.

.\keyframes
	.\TRECVID2005_194
	.\TRECVID2005_197
	.\TRECVID2005_240
	.\TRECVID2005_242
	.\TRECVID2005_253
	.\TRECVID2005_276		

Annotations of these two concepts can be found in the following directories. 
They can be considered as ground truths in your image classification project.

.\annotations
	.\building
	.\explosion_fire

The annotation values are binary, 1 or 0, indicating the presence or absence 
of the corresponding concept in each keyframe. For example, the following 
annotations indicate concept "building" is FALSE in both keyframes shot194_2_RKF
and shot194_3_NRKF_1.

0	% shot194_2_RKF
0	% shot194_3_NRKF_1

The image features, including 5x5 grid color moments (225-dimensions) 
and Gabor textures (48-dimensions), are located under directory "features". 

.\features
	.\gabor46
	.\grid5x5

The image features are grouped based on video files as well.
For example, the 5x5 grid color moment features for keyframes in the video file
TRECVID2005_194 can be found in .\features\grid5x5\TRECVID2005_194.txt. Each row 
contains the frame index and the feature vector for a keyframe. 
The order of the keyframes in each feature file is the same as that used in 
the annotation file. The first column is not part of the feature vector and thus
should be skipped in your experiment.

