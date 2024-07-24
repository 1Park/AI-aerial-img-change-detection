# ai-aerial-img-change-detection
Detecting building changes using aerial image data (2022 Military AI Contest Korea)


## Task Description
Building change detection using aerial image data.


## Train Data Description
- **Input Images**: Before/After aerial images (jpg file format)
- **Output Images**: Change segmented by number 0, 1, 2, 3 (jpg file format)
  - Unchanged area      : 0
  - New Buildings       : 1
  - Changed Buildings   : 2
  - Destroyed Buildings : 3
    
![Sample Input](https://raw.githubusercontent.com/1Park/ai-aerial-img-change-detection/main/data/train/x/2015_DMG_1LB_000006.png)
![Sample Output](https://raw.githubusercontent.com/1Park/ai-aerial-img-change-detection/main/2015_DMG_1LB_000006%20-%20Copy.png)

## Data Augmentation Technique

## Train Technique
Ensemble model of Unet, DeepLabV3Plus, and Mobilenet_v2.

## Evaluation Function
mIoU (mean Intersection over Union)
