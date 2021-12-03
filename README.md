# semantic_keypoint_training
Pytorch based training of a semantic keypoint detector

Pytorch-based implementation of the keypoint detector at https://github.com/geopavlakos/object3d, the training code of which is based on https://github.com/princeton-vl/pose-hg-train. See those repositories for more details on usage, data format, etc.

Training a new model is done with

`python train.py --name NAME --keypoints --dataset_dir PATH/TO/DATASET [other options]`
