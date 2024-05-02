# 这个仓库和原作者的仓库有什么不同
- 主要我在较新的环境下运行成功：
```
Ubuntu24.04
Driver Version: 535.171.04
Python3.10
Pytorch1.13.1
CUDA11.7
```
- 原作者的运行环境是
```
Ubuntu16.04、Ubuntu18.04、Windows 10（inference）
Python3.6
Pytorch1.2
CUDA10.0 + CUDNN7.6
```
# 环境安装
- python 3.10
```
conda create -n 3.10 python=3.10
```
- pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7
```
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia
```
- opencv-python 4.9.0.80
```
pip install opencv-python
```
- detect images test
```
python detect_imgs.py --path ./test/
```