# ai-aerial-img-change-detection
Detecting building changes using aerial image data (2022 Military AI Contest Korea)

## Task Description
Building change detection using aerial image data.

## Train Data Description
- **Input Images**: Before/After aerial images (jpg file format)
- **Output Images**: Change segmented by number 0, 1, 2, 3 (jpg files)
  - Unchanged area: 0
  - New building: 1
  - Changed building: 2
  - Building destroyed: 3

## Data Augmentation Technique

## Train Technique
Ensemble model of Unet, DeepLabV3Plus, and Mobilenet_v2.

## Evaluation Function
mIoU (mean Intersection over Union)
