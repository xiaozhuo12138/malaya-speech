# Noise Reduction

Pretrained Malaya-Speech UNET models to do Noise Reduction.

**This directory is very lack of comments, able to understand Tensorflow, Tensorflow estimator, Tensorflow Dataset is really helpful**.

## how-to

1. Run any pretrained scripts,

**UNET**,

```bash
python3 unet.py
```

**RESNET-UNET**,

```bash
python3 resnet_unet.py
```

3. Export the model for production, example for UNET, [export/unet.ipynb](export/unet.ipynb)

## Download

1. UNET, last update 22th October 2020, [noise-reduction-unet-output-500k.tar.gz](https://f000.backblazeb2.com/file/malaya-speech-model/finetuned/noise-reduction-unet-output-500k.tar.gz)

Tensorboard, https://tensorboard.dev/experiment/o4xZQVvmRoWwgAf2LswKOA/

2. Resnet-UNET, last update 30th October 2020, [noise-reduction-resnet-unet.tar.gz](https://f000.backblazeb2.com/file/malaya-speech-model/finetuned/noise-reduction-resnet-unet.tar.gz)