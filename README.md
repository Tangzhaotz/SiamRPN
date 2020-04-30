
# 本项目的主要工作
- 对SiamRPN的API接口进行优化，支持Vscode调试
- 支持Vscode端的训练和测试
- 添加部分注释
- 添加got10k评估工具，可用于评估，评估结果略低于论文
Refer to the link https://www.bilibili.com/video/BV1Y64y1T7qs 

## Data preparation:
```bash
First get VID dataset and youtube-bb dataset. 

python bin/create_dataset_ytbid.py 

The command above will get a dataset, The dataset in the baiduyundisk. Use this data to create lmdb.
链接:https://pan.baidu.com/s/1QnQEM_jtc3alX8RyZ3i4-g  密码:myq4

python bin/create_lmdb.py
```
## Training
```bash
python bin/train_siamrpn.py 
```
## Testing
```bash
python bin/test_siamrpn.py 
```

## Model Download:
```bash
Pretrained model on Imagenet: https://drive.google.com/drive/folders/1HJOvl_irX3KFbtfj88_FVLtukMI1GTCR

Model with 0.6xx AUC: https://pan.baidu.com/s/1vSvTqxaFwgmZdS00U3YIzQ  keyword:v91k
```
## Reference
```bash

[1] Li B , Yan J , Wu W , et al. High Performance Visual Tracking with Siamese Region Proposal Network[C]// 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2018.
[2] https://github.com/HelloRicky123/Siamese-RPN
```
