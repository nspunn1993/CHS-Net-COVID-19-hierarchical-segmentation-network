# CHS-Net-COVID-19-hierarchical-segmentation-network
## Dataset
The CHS-Net is trained and evaluated on the synthesized dataset generated using publicly available COVID-19 CT segmentation datasets: COVID-19 CT segmentation nr. 2 [[1]](https://medicalsegmentation.com/covid19/) and COVID-19 CT lung and infection segmentation [[2]](https://zenodo.org/record/3757476#.X1nqY4vhWUn). These two datasets are merged to form an aggregated dataset that addresses the problem of limited availability of the COVID-19 data. The fused dataset consists of 3561 CT slices with dimensions as 256 x 256 x 1, each having associated lungs mask and COVID-19 infection mask. The ground truth label is a binary mask with 0 value being the background region and 1 value being the target region.
The complete dataset is available [here](https://drive.google.com/file/d/1nD8IgsqyKdcgxuI4lJ65ePS6pyv1dB3s/view?usp=sharing).

*The source code will be shared soon.*

## Citation
```
@article{punn2020chs,
  title={CHS-Net: A Deep learning approach for hierarchical segmentation of COVID-19 infected CT images},
  author={Punn, Narinder Singh and Agarwal, Sonali},
  journal={arXiv preprint arXiv:2012.07079},
  year={2020}
}
```
