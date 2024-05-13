# SLNet

# Environment

python 3.6

pytorch 1.7.1

torchvision 0.8.2

cuda 11.4

# Dataset

[OASIS](https://sites.wustl.edu/oasisbrains/]) dataset.

[IXI](https://brain-development.org/ixi-dataset/) dataset.

[LPBA](https://resource.loni.usc.edu/resources/atlases-downloads/) dataset.

[Mindboggle](https://osf.io/nhtur/) dataset.

# Training and Testing

If you want to retrain from scratch, first you need to download the original dataset, then perform all the processing operations mentioned in the paper using [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/), and finally use 'python train_Morph.py'.

If you want to directly test the results on OASIS, download the model 'morph.pth.tar' from the master branch and use 'python infer_Morph.py'.
