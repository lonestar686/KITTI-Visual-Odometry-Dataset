## http://cvlibs.net/datasets/kitti/eval_semantics.php
## https://omnomnom.vision.rwth-aachen.de/data/rwth_kitti_semantics_dataset.zip

### DATASET FOR SEMANTIC SEGMENTATION

###Download dataset from https://omnomnom.vision.rwth-aachen.de/data/rwth_kitti_semantics_dataset.zip
###Convert RGB label images using masks_kitti.ipynb
###Download deeplab_resnet.ckpt
###Change fine_tune.py configuration (example is given)
###Change https://github.com/DrSleep/tensorflow-deeplab-resnet/blob/master/deeplab_resnet/image_reader.py#L115 to decode_png
###Run fine_tune.py