# MaskRCNN-nuclei-segmentation-using-tensorflow

## Overview

Nuclei segmentation is the most crucial step toward the implementation of a computer-aided diagnosis system for cancer cells.An abberant  nuclear shape can be used to identify cancer cells.Methods for assessing nuclear size and shape typically involve identifying the nucleus via traditional image segmentation approaches.Here I am demonstrating how to identify and segmenting nuclei from image of cells.

For more you can refer to this link about nuclear shapes and human diseases https://www.ncbi.nlm.nih.gov/pubmed/15343274

## Dependencies
* Tensorflow
* keras
* python

more dependencies are mentioned in the requirement.txt file

## Getting Started
clone the repository https://github.com/matterport/Mask_RCNN.git ,This includes default COCO Datasets.


## Train the model 
`python3 samples/coco/coco.py train --dataset=/path/to/coco/ --model=coco`

## Test the model
`python3 samples/coco/coco.py evaluate --dataset=/path/to/coco/ --model=last`

## Labelling/Annotation

use VGG Image Annotator https://www.robots.ox.ac.uk/~vgg/software/via/via-1.0.1.html
