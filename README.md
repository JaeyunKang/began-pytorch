# BEGAN in PyTorch

PyTorch implementation of [BEGAN: Boundary Equilibrium Generative Adversarial Networks](https://arxiv.org/abs/1703.10717).

![alt tag](./assets/model.png)

## Requirements

- Python 2.7
- [PyTorch](https://github.com/pytorch/pytorch)
- [torch-vision](https://github.com/pytorch/vision)


## Usage

or you can use your own dataset by placing images like:

    dataroot
    └── YOUR_DATASET_NAME
        ├── xxx.jpg (name doesn't matter)
        ├── yyy.jpg
        └── ...

To train a model:

    $ python main.py --dataset folder --dataroot dataroot --cuda


## Results


### Generator output (64x64) with `gamma=0.5` after 20 epochs

![all_G_z0_64x64](./assets/fake_samples_epoch_020.png)


## Author

Jaeyun Kang 
