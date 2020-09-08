# Stroke Lesion Segmentation Using 3D Convolutional Neural Networks

In this project, we implement a 3D Convolutional Neural Network desgined for stroke lesion segmentation in MRI scans.

A research paper detailing the process, analysis, and results can be found in stroke_lesion_paper.pdf

The code is divided into 3 files. 2d.ipynb contains all data preparation, model construction and model testing for the 2d convolutional network. 3d.ipynb contains all data preparation, model construction and model testing for the 3d convolutional network. 3d-Advanced.ipynb includes an additional researched feature; when processing each voxel, we also feed in the symmetric voxel in order to utilize the quasi-symmetry property of the brain for our segmentation.
