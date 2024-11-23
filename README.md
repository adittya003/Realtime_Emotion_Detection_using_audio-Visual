File Descriptions

Audio Emotion Detection

audio-emotion-detection-final.ipynb - Trained the model here on RAVDESS and CREMA-D datasets
audio_emotion_detection.h5 - Trained model with weights
real_time_audio_emotion_detection.ipynb - Added function to record and detect audio emotion in real-time

Video Emotion Detection

Custom_model_visual_emotion_detection.ipynb -  using Customed CNN layers to Train FER-2013 Dataset

DeepFace_visual_emotion_detection.ipynb -  contains Deepface model to predict the emotion

mobileNet_visual_emotion_detection.ipynb - contains MobileNet model to predict the emotion, trained under FER-2013 dataset

Yolo_visual_emotion_detection.ipynb - contains yolov11 model to predict the emotion, trained under FER-2013 dataset



Integrated Notebook:

Final_Audio_pluss_visual.ipynb - final model where we use both audio and visual to predict emotion. Here we record an video which also contains video. replace video_path variable to what 
ever video path you want to perform emotion detection on. Use ffmpeg model to extract the audio from the video. Do analysis on video using DeepFace and audio using our audio model.
