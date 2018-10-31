# MXNet2Caffe: Convert MXNet model to Caffe model

You are welcome to file issues either for bugs in the source code, feature requests!


## Brief Guide

Given a MXNet Model, MXNet2Caffe can automatically generate both `.prototxt` and `.caffemodel`.

1. Before starting using MXNet2Caffe, you need to manually set the path in `find_caffe.py` and `find_mxnet.py`.

2. simply run `python json2prototxt.py` to generate the corresponding `.prototxt`.

3. using `python mxnet2caffe.py` to generate the corresponding `.caffemodel`.


## TODO


