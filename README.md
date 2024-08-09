# 基于信息抽取技术的密集型文本机器可读方法

## 方法总览

![image](https://github.com/user-attachments/assets/1277faee-703f-4d3e-bb40-c5e729c483b6)


## 什么是机器可读？

“机器可读” ，即将非结构化的文本转换成结构化数据，这有助于机器对现有的密集型文本内容进行及时、有效、大规模地提取和应用，有助于构建领域知识图谱、训练领域大模型。

## 密集型文本知识抽取当前存在的问题？

密集型文本，具有极强的领域性，通常包含大量的数据、图表、概念，专有名词等，具有文本组织结构复杂、上下文关系联系紧密等特点。因此，将密集型文本转换成机器可读的结构化数据时，存在以下问题：

Q1: 上下文依赖与特征不足

现有的实体识别方法在面临密集型文本时，易受到上下文长距离依赖的影响、导致特征处理不充分、模型泛化性和鲁棒性不佳的问题。

Q2:噪声干扰与语义歧义

现有的关系抽取方法在面临密集型的标准文本时，易遭受大量无关上下文信息和语义歧义等噪声的影响。


### Reqirements
torch==1.6.0 

nltk==3.6.2 

numpy==1.19.5

scikit-learn==0.24.2

scipy==1.5.4	

sentencepiece==0.1.95

transformers==3.0.2

tokenizers==0.8.1rc1

gdown==4.2.0

### Datasets:
download_nyt10.sh

download_nyt10m.sh

download_wiki20m.sh


### Train:
train_nyt10d.sh

train_nyt10m.sh

train_wiki20m.sh
