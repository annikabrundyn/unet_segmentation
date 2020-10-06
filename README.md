# Semantic Segmentation using a UNet architecture in PyTorch Lightning

This model is designed as template for semantic segmentation tasks using a UNet as the default backbone architecture. I've implemented this model in the PyTorch Lightning Bolts library, where it has been rigorously tested and documented.

I've also implemented the KittiDataModule - a class that conveniently prepares the KITTI segmentation dataset as PyTorch dataloaders. Note, you first have to download the KITTI dataset and provide the local path to the data.

![](u-net-architecture.png, width='30')
