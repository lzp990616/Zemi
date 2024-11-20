## Zemi Test

## 1. Create virtual environment
xxx

## 2. Dataset

* （1）在data_set文件夹下创建新文件夹"flower_data"
* （2）点击链接下载花分类数据集 [https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)
* （3）解压数据集到flower_data文件夹下
* （4）执行"split_data.py"脚本自动将数据集划分成训练集train和验证集val    

```
├── flower_data   
       ├── flower_photos（解压的数据集文件夹，3670个样本）  
       ├── train（生成的训练集，3306个样本）  
       └── val（生成的验证集，364个样本） 
```

根据代码改一下路径，或者根据路径改一下代码
然后debug

## 3. Train
python train.py
