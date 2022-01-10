Trash pollution in the ocean has a significant impact on the environment and on the presence and diversity of marine life. While there have been some political and social efforts to reduce the amount of trash we produce, the existing trash needs
to be dealt with efficiently and at a large scale. 
One method of cleaning up the trash in our oceans is to use autonomous underwater robots (ROVs) to scan the ocean, visually detect trash in the water, and remove it. In order to do this, ROVs
require advanced computer vision algorithms that can detect trash in the difficult conditions of the deep sea. 
Previous work in this area has shown moderate success, however my aim was to improve these results. My approach used two deep learning object detection architectures, Faster RCNN and YOLOv5. While
the performances of the two models were similar, YOLOv5 had better mAP scores and was able to carry out efficient inference on video data, making it more appropriate for the task.