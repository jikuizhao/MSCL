
**Meta Supervised Contrastive Learning for Few-Shot
Open-Set Modulation Classification with Signal
Constellation** [[PDF](http:   .pdf)]



#### Abstract
In this work, we present an approach for few-shot
open-set modulation classification using signal constellation dia-
grams. Our method focuses on the Meta Supervised Contrastive
Learning (MSCL) algorithm. Leveraging the discriminative
power of supervised contrastive learning and the adaptability of
meta-learning, MSCL efficiently segregates classes. Incorporated
into our Automatic Modulation Classification (AMC) framework,
MSCL demonstrates superior performance in both few-shot and
open-set tasks, emphasizing its adaptability and efficiency

&nbsp;
<p align="center">
<img src='./assets/structure.png' width=800>
</p>
&nbsp;


If you find this code useful, consider citing our work:
```
@inproceedings{Jikui Zhao,
  title={Meta Supervised Contrastive Learning for Few-Shot
Open-Set Modulation Classification with Signal
Constellation},
  author={},
  booktitle=},
  pages={},
  year={}
}
```

### Requirements 
* Python 3
* [PyTorch](https://pytorch.org/) (version >= 0.4.1)
* [yaml](https://pyyaml.org/wiki/PyYAMLDocumentation)


### Dataset


### Training and Evaluating
1. Training
```
python main.py --cfg ./config/openfew/default.yaml
```

2. Testing
```
python main.py --cfg ./config/openfew/default.yaml --test
```

### Results and Models

#### Few-Shot

Model usage: unzip and move the entire directory under `./output`

