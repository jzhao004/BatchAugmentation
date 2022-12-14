# Batch Augmentation for Videos

Takes as input a batch of videos of dimension [B x ... x H x W] <br/>
Applies the same augmentation across frames in each video and different augmentations across videos

Includes:
1. RandomHorizontalFlip
2. RandomCrop
3. RandomResizedCrop
4. RandomErasing
5. Normalize

(Adapted from torchvision.transforms)
