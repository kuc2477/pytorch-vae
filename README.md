# VAE PyTorch Implementation

PyTorch implementation of [Auto-Encoding Variational Bayes, arxiv:1312.6114](https://arxiv.org/abs/1312.6114)

![vae-graphical-model](./arts/vae.png)


## Installation

```
$ git clone https://github.com/kuc2477/pytorch-vae && cd pytorch-vae
$ pip install -r requirements.txt
```


## CLI

Implementation CLI is provided by `main.py`

#### Usage
```
$ ./main.py --help
$ usage: VAE PyTorch implementation [-h] [--dataset {mnist,cifar10,cifar100}]
                                  [--kernel-num KERNEL_NUM] [--z-size Z_SIZE]
                                  [--epochs EPOCHS] [--batch-size BATCH_SIZE]
                                  [--sample-size SAMPLE_SIZE] [--lr LR]
                                  [--weight-decay WEIGHT_DECAY]
                                  [--loss-log-interval LOSS_LOG_INTERVAL]
                                  [--image-log-interval IMAGE_LOG_INTERVAL]
                                  [--resume] [--checkpoint-dir CHECKPOINT_DIR]
                                  [--sample-dir SAMPLE_DIR] [--no-gpus]
                                  (--test | --train)

optional arguments:
  -h, --help            show this help message and exit
  --dataset {mnist,cifar10,cifar100}
  --kernel-num KERNEL_NUM
  --z-size Z_SIZE
  --epochs EPOCHS
  --batch-size BATCH_SIZE
  --sample-size SAMPLE_SIZE
  --lr LR
  --weight-decay WEIGHT_DECAY
  --loss-log-interval LOSS_LOG_INTERVAL
  --image-log-interval IMAGE_LOG_INTERVAL
  --resume
  --checkpoint-dir CHECKPOINT_DIR
  --sample-dir SAMPLE_DIR
  --no-gpus
  --test
  --train
```

#### Train
```
./main.py --train
```

#### Test
```
./main.py --test
```


## Reference
- [Auto-Encoding Variational Bayes, arxiv:1312.6114](https://arxiv.org/abs/1312.6114)


## Author
Ha Junsoo / [@kuc2477](https://github.com/kuc2477) / MIT License
