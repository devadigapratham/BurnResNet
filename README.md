## ResNet + Burn 

### How to test it out ? 

1. Download the ResNet-18 pre-trained weights from `torchvision`

```sh
wget https://download.pytorch.org/models/resnet18-f37072fd.pth
```

2. Download a sample image for inference

```sh
wget https://upload.wikimedia.org/wikipedia/commons/2/26/YellowLabradorLooking_new.jpg
```

3. Run the example

```sh
cargo run --release YellowLabradorLooking_new.jpg
```

