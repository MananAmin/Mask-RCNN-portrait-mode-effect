# Mask-RCNN-portrait-mode-effect

Original [Mask-RCNN](https://github.com/matterport/Mask_RCNN) is mainly used in object detection and scene segmentation.
I'm simply using Mask-RCNN model for Instance Segmentation. And then adding blur effect on background.
(note: keep only main person (person with maximum area covered in image) if there are multiple)

For download this weights of mask-rcnn [download page (use V2 coco)](https://github.com/matterport/Mask_RCNN/releases) and put it in the main folder.

Intensity of blur can be change: (input from user)

Some Result

<br><img src="ss1.png" style="width:auto ; height: auto; margin-left: 50px; " /> <br>

And also blur person 

<br><img src="ss2.png" style="width:auto ; height: auto; margin-left: 50px; " /> <br>


# Credits:

[Mask-RCNN](https://github.com/matterport/Mask_RCNN) 
