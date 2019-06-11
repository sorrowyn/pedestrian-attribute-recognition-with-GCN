# pedestrian-attribute-recognition-with-GCN

## Preparation

<font face="Times New Roman" size=4>
  
**Prerequisite: Python 3.6 and torch 1.1.0 and torchnet and tqdm**

**Download and prepare RAP(v2) dataset and annotation then put in dataset directory**

</font>

## Train the model

<font face="Times New Roman" size=4>

   ```
   python transform_rap2.py     (transform data)
   python glove.py      (word2vec)
   python adj.py      (Adjacency matrix)
   python train.py      (weight file will locate in checkpoint directory)
   ``` 
</font>

## Demo

<font face="Times New Roman" size=4>
  
## checkpoint.pth.tar [Baidu Yun](https://pan.baidu.com/s/1N-b9ox7RQOq6rLez9Rn2Hg),password:n487 (training 100 epoch,initial lr 0.01)
   ```
   python demo.py
   ``` 
</font>

![image](https://github.com/2014gaokao/pedestrian-attribute-recognition-with-GCN/blob/master/image/demo_image_result.png)
