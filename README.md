# AI Aerial Image Change Detection
Detecting building changes using aerial image data (2022 Military AI Contest Korea)

Contributers : 남현재, 최한승, 이호은, 박원 (3크루1야근 팀)

Keywords : `Computer Vision` `Change Detection`  `Image Segmentation` `CNN` `Unet` `Ensemble model` 


## :sparkles: Task Description
Building change detection using aerial image data.


## :sparkles: Train Data Description
- **Input Images**: Before/After aerial images (png file format)
  
<img src="./2015_DMG_1LB_000006.png" alt="Sample Input" width="300" />

- **Output Images**: Change segmented by number 0, 1, 2, 3 (png file format)
  - Unchanged area      : 0
  - New Buildings       : 1
  - Changed Buildings   : 2
  - Destroyed Buildings : 3
    

<img src="https://raw.githubusercontent.com/1Park/ai-aerial-img-change-detection/main/2015_DMG_1LB_000006%20-%20Copy.png" alt="Sample Output" width="300" />

## :sparkles: Data Augmentation Technique

## :sparkles: Train Technique
Ensemble model of Unet, DeepLabV3Plus, and Mobilenet_v2.

## :sparkles: Evaluation Function
mIoU (mean Intersection over Union)

**Expected Evaluation Score** : 0.68 (ranked 19th place)
