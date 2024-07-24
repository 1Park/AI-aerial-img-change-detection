# ai-aerial-img-change-detection
Detecting building changes using aerial image data (2022 Military AI Contest Korea)

Task description
Building change detection using aerial image data

Train data description
input images: Before/After aerial images (jpg file format)
output images: change segmented by number 0, 1, 2, 3 (jpg files)
	Unchanged area: 0
	New building : 1
	Changed building: 2
	building destroyed: 3

Data Augmentation Technique


Train Technique
Ensemble model of Unet, DeepLabV3Plus, and Mobilenet_v2


Evaluation function
mIoU (mean Intersection over Union)
