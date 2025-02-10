# Activity_Recognition_Model_Testing

This Repository demonstrates action recognition using a pre-trained Long-term Recurrent Convolutional Network (LRCN) model. The model processes a sequence of video frames and predicts the action being performed.


# Workflow:

- Load the trained LRCN model.
- Read the input video and extract frames.
- Pre-process frames by resizing and normalizing.
- Store frames in a sequence and pass them to the model.
- Predict the action for each sequence and overlay the result on the video frames.
- Save the output video with predicted labels displayed.


The final output is a processed video where each frame is labeled with the predicted action, providing a real-time visual representation of activity recognition.
