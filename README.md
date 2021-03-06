# Semantic Segmentation using a UNet architecture in PyTorch Lightning

This model is designed as template for semantic segmentation tasks using a [UNet](https://arxiv.org/abs/1505.04597) as the default backbone architecture. I've implemented this model in the PyTorch Lightning Bolts library, where it has been tested and documented.

I've also implemented the KittiDataModule - a class that conveniently prepares the KITTI segmentation dataset as PyTorch dataloaders. Note, you first have to download the KITTI dataset ([linked here](http://www.cvlibs.net/datasets/kitti/eval_semantics.php)) and provide the local path to the data.


UNet architecture:

<p align="center">
  <img src="u-net-architecture.png" width="500"/>
</p>
