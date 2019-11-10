# Mr-Bean
Aim of this work: To find the run time of Mr Bean present in a video.

Requirements: Training Video, Testing Video

Procedure:
1. Video is nothing but image snaps. So, video processing is as similar as image processing.
2. Extract the snaps from the train video
3. Label it manually in a csv file. I labelled 1 for Mr Bean presence, 0 for absence.
4. This csv file will be our target. Our variables are images.
5. Fit the variables and target by using deep learning.
6. Now take the test video and extract the snaps.
7. These snaps are the testing ones.
8. By using the already trained model, prediction is done.

Result:
We got the total run time of Mr Bean in the video.

This work can be scalable.
