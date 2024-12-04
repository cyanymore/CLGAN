# CLGAN
Combining Generative Adversarial Network and Contrastive Learning for Infrared Image Generation

## Prerequisites
- python 3.7
- torch 1.13.1
- torchvision 0.14.1
- dominate
- visdom

## Trian
```
python train.py --dataroot [dataset root] --name [experiment_name] --phase train 
```

## Test
```
python test.py --dataroot [dataset root] --name [experiment_name] --phase test 
```

## Colorization results
### KAIST dataset
![KAIST](imgs/KAIST.png)


### LLVIP dataset
![LLVIP](imgs/LLVIP.png)


## Acknowledgments
This code heavily borrowes from [DCLGAN](https://github.com/JunlinHan/DCLGAN).
