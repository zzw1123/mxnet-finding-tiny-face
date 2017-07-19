# mxnet-finding-tiny-face
**This is an inference-only implementation for MXNet of [tiny face](https://github.com/peiyunh/tiny).**
See the following references for more information:
```
"Finding Tiny Faces."
Peiyun Hu, Deva Ramanan
arXiv preprint arXiv:1612.04402, 2016.
```
[https://arxiv.org/abs/1612.04402](https://arxiv.org/abs/1612.04402)

## Getting Started
  * Download the origin author's model [from here.](https://www.cs.cmu.edu/~peiyunh/tiny/hr_res101.mat)
  * Transform the origin Matconvnet model to MXNet model using matconvnet_hr101_to_mxnet.py.

## Declaration:

* the code is used to do face detection 
* forked by chinakook/hr101_mxnet
* and added some Batch processing codes to read images from a folder named"./data/images_stair_enter/"
* then save them in the result file "./results/test_stair_enter_results/"

* average processing time is 2.6 seconds
* total processing time is 164.96s while processing 55 images which is obviously faster than the original code by matlab（https://github.com/peiyunh/tiny） which is 212s.

## Using method:

* python mx_tiny.py
