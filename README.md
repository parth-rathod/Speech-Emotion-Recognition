# Speech-Emotion-Recognition

### Abstract
1) In the past decade a lot of research has gone into Automatic Speech Emotion Recognition (SER). The primary objective of SER is to improve man-machine interface. It can also be used to monitor psycho physiological state of a person in lie detectors. In recent time speech emotion recognition also has applications in medicine and forensics.
2) The task of speech emotion recognition is very challenging for following reasons. First it is not clear which speech features are powerful in distinguishing between emotions. Second issue is that how a certain emotion is expressed generally depends on the speaker, his or her culture and environment. Most of the work has focused on monolingual emotion classification making an assumption there is no cultural difference among speakers. This project aims to capture the correct prediction of speech emotions by using Machine Learning techniques.


## Problem Description
The task of speech emotion recognition is very challenging for following reasons. First it is not clear which speech features are powerful in distinguishing between emotions. Second issue is that how a certain emotion is expressed generally depends on the speaker, his or her culture and environment. Most of the work has focused on monolingual emotion classification making an assumption there is no cultural difference among speakers. This project aims to capture the correct prediction of speech emotions by using Machine Learning techniques

## Data Description
The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) contains 3120 files. The database contains 10 professional actors (5 female, 5 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression. All conditions are available in three modality formats: Audio-only (16bit, 48kHz .wav), Audio-Video (720p H.264, AAC 48kHz, .mp4), and Video-only (no sound). 

Audio-only files
Audio-only files of all actors (01-10) are available:
•	Speech file (Audio_Speech_Actors_01-10.zip) contains 600 files: 60 trials per actor x 10 actors = 600. 
•	Song file (Audio_Song_Actors_01-10.zip) contains 440 files: 44 trials per actor x 10 actors = 440.

Audio-Visual and Video-only files
Video files are provided as separate zip downloads for each actor (01-10), and are split into separate speech and song downloads:
•	Speech files (Video_Speech_Actor_01.zip to Video_Speech_Actor_10.zip) collectively contains 1200 files: 60 trials per actor x 2 modalities (AV, VO) x 10 actors = 1200.
•	Song files (Video_Song_Actor_01.zip to Video_Song_Actor_10.zip) collectively contains 880 files: 44 trials per actor x 2 modalities (AV, VO) x 10 actors = 880.

In total, the RAVDESS collection includes 3120 files (600+440+1200+880 files).


## Evaluation Metrics
Classifier	        No. of Emotions	    Speech Database	    Average Accuracy
MLP	                    8	                  RAVDESS	            80%
Neural Networks	        8	                  RAVDESS	            63.31%
Random Forest	          8	                  RAVDESS	            60%

