The following repo has been set up to host the inital code file for the POC used as part of the CM4708 Coursework.

The code has been saved in a Jupyter Notebook complete with the outputs generated whne the notebook was run.

In the notebook the following actions are taken to prove that at least part of the system being proposed within the overall report submitted to uni can be undertaken.
1. The folders where the raw data and the converted data will be stored are specified.
2. The video footage is first converted from the .mpg file format to .mp4 format to allow footage to be viewed via Windows Media Player.
3. Following conversion to .mp4 I then randomly sample 5 frames from the converted footage and display these within the script to ensure that conversion was successful.
4. Now that the video footage has been converted to .mp4 I then apply CLAHE to the footage.  I convert each frame from the video to the LAB colour model, split it into it's component channels and apply CLAHE to the L channel before merging with the A & B channels and converting back to RGB.
5. Once CLAHE has been successfully applied to a video file I then randomly sample 5 frames from the original video and CLAHE'd video to show the comparison between the video footage.

