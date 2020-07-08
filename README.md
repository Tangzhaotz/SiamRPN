# Pytorch implementation of SiamRPN
## Contribution
- Support VSCode debug
- Support train and test
- Support 9 datasets evaluation

https://www.bilibili.com/video/BV1Y64y1T7qs 

## Preparation
```bash
First get VID dataset and youtube-bb dataset. 

The dataset in the baiduyundisk. Use this data to create lmdb.
链接:https://pan.baidu.com/s/1QnQEM_jtc3alX8RyZ3i4-g  密码:myq4

python bin/create_lmdb.py (Note that LMDB data format can speed up the data loading)
```
## Training
```bash
python ./bin/train_siamrpn.py 
```
## Testing
```bash
python ./bin/test_siamrpn.py 
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
