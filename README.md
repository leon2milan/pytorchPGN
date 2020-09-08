# Pointer Networl

This code is the implementation of paper [*Get To The Point: Summarization with Pointer-Generator Networks*](https://arxiv.org/pdf/1704.04368.pdf) with Pytorch.

# requirement

pytorch >= 1.1


## Step 1

```shell
nohup python train.py 2>&1 | tee out/train.out &
```
*note* Before training, you need process your data to certain format(separation with blank).
# Step 2

```shell
python predict.py
```



