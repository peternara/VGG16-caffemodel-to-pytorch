# VGG16-caffemodel-to-pytorch
This repository converts an Image-Net pretrained VGG16 caffemodel to a pytorch version.

How to use
1. You need to download the prototxt and the caffemodel of VGG16 pretrained on Image-Net. Their file names are 'VGG_ILSVRC_16_layers_deploy.prototxt' and 'VGG_ILSVRC_16_layers.caffemodel'.
2. You need to install caffe. The version this repositoy used is caffe_dss (https://github.com/Andrew-Qibin/caffe_dss). 
3. You need to install pytorch 0.4.0, if you want to keep consistent with this repository.
4. You need to modify imname in the code as the path of some testing image on your computer.
