# MNIST model training
* ```models.py``` 為模型定義程式
* ```train.py``` 為模型訓練程式
# Installation
* create training enviroment
```
conda create -n env_name python=3.8
conda activate env_name
```
* install pytorch、torchvision
```
conda install pytorch==1.8.0 torchvision==0.9.0 cpuonly -c pytorch
```
* install torchsummary、PyYAML、tqdm、requests
```
pip install torchsummary PyYAML tqdm requests
```
# Training
```
python train.py
```
