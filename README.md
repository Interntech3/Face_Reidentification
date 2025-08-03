Face Tracking and Re-identification using RetinaFace, Deep SORT, and ArcFace
It performs real-time face detection, tracking, and re-identification in video using:
  RetinaFace for face detection
  Deep SORT for tracking
  ArcFace (via InsightFace) for face recognition and re-identification

Features
1. Consistent face IDs across frames
2. Re-identification based on facial embeddings
3. Annotated video output with bounding boxes and face IDs

Requirements
1. Install the required Python libraries:
  pip install opencv-python torch numpy scikit-learn insightface

How to Run
  Make sure you have input.mp4 in the working directory. Then run:
  python retina+deepsort.py
  
Output
output_tracked.mp4: Video with tracked faces and identity labels
