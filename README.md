This is the task that was given to me during my intership. The main goal was to acquire a segmentation model for a detection of defects on bolts (scratches, deformations, chips and others).
As part of the task I:
1) Collected the data, preprocessed and manually annoteted it with the help of [``` Roboflow ```](https://roboflow.com/annotate) platform.
2) Trained Roboflow v3.0 as "fast-to-get" model for comparing it with my custom ones.
3) Tested several segmentation models constructed with [``` segmentation_models.pytorch ```](https://github.com/qubvel-org/segmentation_models.pytorch) with different architectures such as Unet, PSPNet, and DeepLabV3
   and corresponding to them backbones like efficientnet-b1, se_resnext50_32x4d, and resnet34.
5) Performed segmentation with the best (in terms of metrics and mask quality) models.

**P.S. This "project" served as a code quality demonstration in January of 2025 and remains to do that due to the good balance between task complexity and code amount.** 
