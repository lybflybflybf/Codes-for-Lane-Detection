# Tensorflow-SCNN
Tensorflow version of SCNN. (expected release date: 2018.11.20)

### Timeline
Tensorflow version of SCNN is writing in progress. I will clean the codes and make them readable soon!

### Prerequisites
- [Tensorflow](https://www.tensorflow.org/)

### Installation
    conda create -n tensorflow_gpu pip python=3.5
    source activate tensorflow_gpu
    pip install --upgrade tensorflow-gpu==1.3.0

### Testing
    cd lane-detection-model
    CUDA_VISIBLE_DEVICES="0" python tools/test_lanenet.py 

### Training
    cd lane-detection-model
    CUDA_VISIBLE_DEVICES="0" python tools/train_lanenet.py --net vgg --dataset_dir /path/to/CULane-dataset/

### Tensorflow version of SCNN (single GPU)
Working in progress (2018.10.23 ~ 2018.11.20), multiple GPU version will be available soon!


### Acknowledgement
This repo is built upon [SCNN](https://github.com/XingangPan/SCNN) and [LaneNet](https://github.com/MaybeShewill-CV/lanenet-lane-detection)

### Contact
If you have any problems in reproducing the results, just raise an issue in this repo.
