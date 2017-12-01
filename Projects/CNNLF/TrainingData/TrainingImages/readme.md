# Generate Training Data for Single CNN Model

## Brief Intro
This folder contains the materials for single CNN model training data generation in our paper.
As mentioned in our paper, we use BSDS-500 dataset for illustration.
Notes: The matlab code for generating training samples will be provided soon. 

## Detail
- generate_single_train.m: 80% of the dataset are used for training data generation. (Currently Unavailable)
- generate_single_test.m: the remaining images for validation data. (Currently Unavailable)
- store2hdf5.m: zip the data and store the them into .h5 format. (Currently Unavailable)
- The folder 'TrainingImages' contains the HEVC-compressed (QP=22,27,32,37) images and their corresponding label images (only luma channel is provided).
- The folder 'TrainingImages\Label' contains uncompressed BSDS500 dataset in .bmp format.
- The folder 'TrainingImages\qp**' contains HEVC-compressed BSDS500 dataset in .bmp format, where ** denotes the QP value.
- Download link: https://github.com/Codersadis/codersadis.github.io/tree/master/Projects/CNNLF/TrainingData/TrainingImages

## Test
- Platform: MATLAB
- OS info: Win10 HomeBasic 64bit && 16G Memory
- Version: MATLAB 2017a

## Tips
- Modify the parameters to adapt your tasks when generating data.

## Reference
- Arbelaez, Pablo, et al. "Contour detection and hierarchical image segmentation." IEEE transactions on pattern analysis and machine intelligence 33.5 (2011): 898-916.

## Author
- cmjia@pku.edu.cn

## License
- GPL v3, see LICENSE   
