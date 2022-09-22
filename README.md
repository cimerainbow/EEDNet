# LMGCN
LMGCN: A Learnable Multi-Gradient Convolutional Network for Efficient Edge Detection

# 
All results is evaluated on Python 3.8 with PyTorch 1.11.0+cuda113 and MATLAB R2018b.\
 We only publish our test results on the BSDS500, NYUDv2  and Multicue datasets for now. \
 The implementation details of code will be updated after the paper is officially published.


## Datasets
We use the links in RCF Repository (really thanks for that). \
The augmented BSDS500, PASCAL VOC, and NYUD datasets can be downloaded with:

```
    wget http://mftp.mmcheng.net/liuyun/rcf/data/HED-BSDS.tar.gz
    wget http://mftp.mmcheng.net/liuyun/rcf/data/PASCAL.tar.gz
    wget http://mftp.mmcheng.net/liuyun/rcf/data/NYUD.tar.gz
```
Multicue Dataset is Here
```
    https://drive.google.com/file/d/1-tyt_KyzlYc9APafdh5mHJzh2K_F2hM8/view?usp=sharing
```

## Tools
The evaluation program of ODS OIS is here:
```
    https://github.com/pdollar/edges
```
The PR curve tool is here:
```
    https://github.com/MCG-NKU/plot-edge-pr-curves
```
The code for the visualization parameter L. 
```
    # We will upload it later.
```



All the efficiency indicators are obtained on the P100 provided by the Colab platform:
```
    # We will prepare a notebook for training and reasoning about LMGCN 
    # You can run on the Colab platform with one click.
    
    https://colab.research.google.com/
```

## Reference
When building our codeWe referenced the repositories as follow:
 
1. [Pidinet](https://github.com/cimerainbow/pidinet, "pidinet")
2. [RCF](https://github.com/yun-liu/rcf, "rcf")
3. [HED Implementation](https://github.com/xwjabc/hed, "hed")


