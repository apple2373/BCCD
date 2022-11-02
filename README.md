# BCCD
Cleaned Dataset of BCCD for white blood cell (WBC) classification. 

See [`BCCD_cropped`](./BCCD_cropped), which is compatible with [`torchvision.datasets.ImageFolder`](https://pytorch.org/vision/main/generated/torchvision.datasets.ImageFolder.html). 

## Source 
- Images are from: https://github.com/ParthaPratimBanik/An-Automatic-Nucleus-Segmentation-and-CNN-Model-based-Classification-Method-of-White-Blood-Cell/tree/main/wbc_nucleus_seg_localz
- labels.csv is from https://www.kaggle.com/datasets/paultimothymooney/blood-cells

If you want to replicate how we organize the image, see [`preprocess-bccd.ipynb`](./preprocess-bccd.ipynb).

## Statistics
| Label      |   Count |
|:-----------|--------:|
| neutrophil |     207 |
| eosinophil |      88 |
| lymphocyte |      33 |
| monocyte   |      20 |
| basophil   |       3 |

Total: 351
