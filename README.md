# Pytorch implementation of SiamRPN

## Description
My code https://github.com/HonglinChu/SiamRPN

## File tree
```
.
├── bin
├── got10k
└── siamrpn
```

## Data preparation
```bash
First get VID dataset and youtube-bb dataset. 

python bin/create_dataset_ytbid.py 

The command above will get a dataset, The dataset in the baiduyundisk. Use this data to create lmdb.
link:https://pan.baidu.com/s/1QnQEM_jtc3alX8RyZ3i4-g  password:myq4

python bin/create_lmdb.py
```
## Train
```bash
python bin/train_siamrpn.py 
```
## Test
```bash
python bin/test_siamrpn.py 
```

## Model
```bash
Pretrained model on Imagenet: https://drive.google.com/drive/folders/1HJOvl_irX3KFbtfj88_FVLtukMI1GTCR

Model with 0.6xx AUC: https://pan.baidu.com/s/1vSvTqxaFwgmZdS00U3YIzQ  keyword:v91k
```
## Reference
```bash

[1] Li B , Yan J , Wu W , et al. High Performance Visual Tracking with Siamese Region Proposal Network[C]// 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2018.
[2] https://github.com/HelloRicky123/Siamese-RPN

```
