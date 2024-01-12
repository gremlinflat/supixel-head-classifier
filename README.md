# Supixel's Head Architectures

## Dataset structure

``` bash
    dataset
    ├── train
    │   ├── class1
    │   │   ├── img1.jpg
    │   │   ├── img2.jpg
    │   │   └── ...
    │   ├── class2
    │   │   ├── img1.jpg
    │   │   ├── img2.jpg
    │   │   └── ...
    │   ├── ...
    │   └── classN
    ├── test
    │   ├── class1
    │   │   ├── img1.jpg
    │   │   ├── img2.jpg
    │   │   └── ...
    │   ├── class2
    │   │   ├── img1.jpg
    │   │   ├── img2.jpg
    │   │   └── ...
    │   ├── ...
    │   └── classN
    └── val (OPTIONAL)
        ├── class1
        │   ├── img1.jpg
        │   ├── img2.jpg
        │   └── ...
        ├── class2
        │   ├── img1.jpg
        │   ├── img2.jpg
        │   └── ...
        ├── ...
        └── classN
```

## Logs

- (2024/01/06) Try `resnet18` on `cifar100` dataset -> transfer to 5 classes. result is not good.
- (2024/01/08) explore `vgg16` & `mobilenetv2` on custom dataset 5 classes. result is good, but model size is too large.
- (2024/01/13) final touch, migrating to `squeezenet1` and `squeezenet1_1`. result is good, model size is small. this is the best model could provide on given time.
