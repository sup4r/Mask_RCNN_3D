# Mask-RCNN 3D

## Introduction

|**3d gif 1**|**3d gif 2**|**3d gif 3**|
| :--: | :--: | :--: | 
|![](images/fun3dgif_1.gif)|![](images/fun3dgif_2.gif)|![](images/fun3dgif_3.gif)|

As shown above, by putting two parallel white lines on a moving image, we can generate a 3D (look-like) image. This project puts this idea into use by exploit object detection and scene segmentation information generaged by [Mask-RCNN](https://github.com/matterport/Mask_RCNN).

Here are some demo images:

|**Original Image 1**|**New Image 1**|**Original Image 2**|**New Image 2**|
| :--: | :--: | :--: | :--: |
|![](images/family.jpg)|![](images/family_3d.jpg)|![](images/persons.jpg)|![](images/persons_3d.jpg)|


## Usage

Before start, please download the mask_rcnn_coco.h5 file from the [released page](https://github.com/matterport/Mask_RCNN/releases) and put it in the main folder.

Generating 3D effect image:

$ python 3d_image.py -i images/persons.jpe -o images/persons_3d.jpe

$ python 3d_image.py -i images/persons.jpe -o images/persons_3d.jpe -w 30 -d 20

## References

[Mask-RCNN](https://github.com/matterport/Mask_RCNN) and [Mask-RCNN-Shiny](https://github.com/huuuuusy/Mask-RCNN-Shiny)

