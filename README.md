# Player Re-Identification in a Single Video
This project performs player tracking and re-identification using YOLOv11 and DeepSORT. Created as part of the LIAT.ai Internship Assignment.

## Overview
- Uses YOLOv model(Ultralytics) for player detection
- Tracks players across frames using DeepSORT
- Maintains consistent IDs even after players leave and re-enter

##  Files

| File | Description |
|------|-------------|
| `re_identification_in_a_single_video.py` | Main script |
| `best.pt` | YOLOv11 model 
| `15sec_input_720p.mp4` | Input video |
| `output_with_ids.mp4` | Output with tracked IDs

