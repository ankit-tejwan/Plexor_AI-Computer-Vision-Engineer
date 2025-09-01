# Plexor_AI-Computer-Vision-Engineer-
Plexor_AI-Computer Vision Engineer 

#Input: 
Accept video files (MP4, AVI, MOV). Handle scenes with and without phone usage.

Detection: Identify handheld phones (in hand, on lap, near face). Ignore unrelated objects.

Output: Video with bounding boxes and confidence labels. Maintain the same resolution & FPS as input. Preserve original audio

Performance: Handle partial occlusions. Ignore static phones (e.g., lying on a table). Process near real-time

Optional Enhancements: Log timestamps of phone usage. Generate a summary report.


Out of Scope: Detecting other distractions (books, tablets). Real-time streaming (unless specified). Multi-person tracking (unless required)
# Yes, we can customise as we need.

✅Success Criteria
-Bounding boxes appear only for active phone usage
-No false positives
-Smooth playback

#Custom training  detection model and epochs only 50, and input data size only 23 images 
and labelling using the labelling tool

<img width="1049" height="250" alt="Screenshot 2025-09-01 155229" src="https://github.com/user-attachments/assets/89207538-d0a7-4aab-ae1d-135232029222" />

# model testing and evaluation 

<img width="1253" height="445" alt="Screenshot 2025-09-01 155256" src="https://github.com/user-attachments/assets/0a425991-d34e-4692-a67b-407eee73b375" />
 # if False positive, then refinement is needed as per the CV[computer vision techniques] knowledge 
 
 <img width="1268" height="449" alt="Screenshot 2025-09-01 155157" src="https://github.com/user-attachments/assets/3095a5c1-c6cc-4660-8038-ebdbef526ddf" />

 # demo video URL
 Access from this URL 
 https://drive.google.com/file/d/1WUOmLpuIr2fE1GM9jFNHIWsj4yLlC5SG/view?usp=sharing
