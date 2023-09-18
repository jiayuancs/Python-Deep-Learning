# Python for Deep Learning

Notes on learning to use Python for data analysis and deep learning.

## Conda environment

```shell
conda create -n dl python=3.11

conda activate dl

pip install -r requirements.txt
```

Install [PyTorch](https://pytorch.org/) for CPU or GPU platform

```shell
# CPU platform
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

# or GPU platform
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```
