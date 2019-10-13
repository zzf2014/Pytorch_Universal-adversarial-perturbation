# Python

A PyTorch implementation of universal attack. Refer to the original [*tensorflow code*](https://github.com/LTS4/universal). <br>
**But I find that when I use the same dataset(10,000), my code can only fool 30% images in Validation set(50,000). Looking forward to your help!**
## Usage

### Dataset
training dataset(Choose 10 imgs for each category): http://www.image-net.org/challenges/LSVRC/2012/dd31405981ef5f776aa17412e1f0c112/ILSVRC2012_img_train.tar
Validation dataset: http://www.image-net.org/challenges/LSVRC/2012/dd31405981ef5f776aa17412e1f0c112/ILSVRC2012_img_val.tar

### Get started

To get started, you can run the following demo code
```
python search.py
```

## Reference
[1] S. Moosavi-Dezfooli\*, A. Fawzi\*, O. Fawzi, P. Frossard:
[*Universal adversarial perturbations*](http://arxiv.org/pdf/1610.08401), CVPR 2017

