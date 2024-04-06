## Overview

This is the submission for Purdue's ECE 50024, Spring 2024.
By Justin Cooper, 4/6/2024

## Required Submodule

To run this code yourself, you will need to clone the following git project to this folder. If I knew how to work with submodules I would have made it a submodule.

```git clone git@github.com:timesler/facenet-pytorch.git```

## Important Files

I used .ipynb for all my runs. The most important files are listed below:

1. jtc_mtcnn_processing.ipynb -- Used to crop faces from images and save into a specified directory. Uses the MTCNN model from facenet-pytorch.

2. jtc_finetune.ipynb -- Used for transfer learning given our training images. This file also containts the test script used to perform a single run on all the test images and generate a submission .csv file.

