# Boundary Loss for Breast Ultrasound Segmentation
Review of the paper [Boundary Loss for highly unbalanced Segmentation](https://arxiv.org/pdf/1812.07032.pdf)
for the Medical Image Analysis course of Master MVA 2022 by Hervé Delingette and Xavier Pennec.

We are reviewing the paper - written by Kervadec et al. - presenting the Boundary Loss, a new function
loss based on a distance metric on the space of contours, which alleviates this issue.
Furthermore, we have implemented several parts of the paper and experimented
the effect of the boundary loss for an unbalanced segmentation of noisy ultrasound
images.

## Code
Implementation inspired from the github [boundary-loss](https://github.com/LIVIAETS/boundary-loss).

## Data
We evaluated the boundary loss on the dataset presented in [Breast Ultrasound Images Dataset](https://pubmed.ncbi.nlm.nih.gov/31867417/).

Data available [here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset).

## Results
DSC: Dice Coefficient
<p align="center">
  <img width="600" height="250" src="https://user-images.githubusercontent.com/64415312/209369467-f442c8e1-868e-4ed3-816c-ebc515b9a083.png">
</p>

## Report
Report to find [here](https://github.com/AmbroiseOdonnat/BoundaryLoss/blob/main/Boundary_Loss_for_Breast_Ultrasound_Segmentation.pdf).

