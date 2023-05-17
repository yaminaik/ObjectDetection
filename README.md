# ObjectDetection On Satellite Imagery

## Abstract
Object detection in satellite imagery plays a crucial role in various domains such as urban planning, disaster response, and environmental monitoring. The SpaceNet7 dataset, a benchmark dataset for object detection using satellite imagery, provides a rich collection of high-resolution imagery along with accurately annotated object labels. This paper presents a comprehensive study on object detection using the SpaceNet7 dataset, exploring different state-of-the-art techniques and evaluating their performance. Our findings demonstrate the efficacy of deep learning models in detecting buildings, enabling accurate and efficient analysis of satellite imagery for a wide range of applications.

## Respository Details:
There are 3 models with colab repository, loss curves,Precision Values and Pictures of Dataset during Training:
Faster_Rcnn_Adam: This uses FasterRcnn Model with Adam Optimizer.

Faster_Rcnn_Cosine:This uses FasterRcnn Model with with a Cosine Decay Learning Rate schedule.

SSD_Cosine:This uses SSD Model with with a Cosine Decay Learning Rate schedule.


## Refrences:
https://github.com/cloud-annotations/cloud-annotations/blob/main/training/notebooks/colab/object_detection.ipynb
https://github.com/tensorflow/models/tree/master/research/object_detection
