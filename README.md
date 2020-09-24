# Residual Spatial Attention Network for Retinal Vessel Segmentation
This code is for the paper: Residual Spatial Attention Network for Retinal Vessel Segmentation. We report state-of-the-art performances on DRIVE and CHASE DB1 datasets.

Code written by Changlu Guo, University of Oulu.


We train and evaluate on Ubuntu 16.04, it will also work for Windows and OS.

## Code structure
* step1_generateEntropyMap is used for generating THD-HMM with entropy maps
* step2_THD_HMM-LSTM is used for training the BiLSTM with the generated THD-HMM for recognition and segmentation

## Quick start (example with OAD dataset)

train:
Run train_drive.py or train_chase.py

test:

Run eval_drive.py or eval_chase.py

For detailed parameter configuration, please read the paper.

## Environments

Keras 2.3.1  <br>
Tensorflow==1.14.0 <br>


##If you are inspired by our work, please cite this paper.

@misc{guo2020residual,
    title={Residual Spatial Attention Network for Retinal Vessel Segmentation},
    author={Changlu Guo and Márton Szemenyei and Yugen Yi and Wei Zhou and Haodong Bian},
    year={2020},
    eprint={2009.08829},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}


