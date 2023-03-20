# Clone 
```
git clone https://github.com/jo1132/KoBERT.git
```

# Install libraries
```python
export TORCH_CUDA_ARCH_LIST=8.0
apt update
apt upgrade -y
wget https://developer.download.nvidia.com/compute/cuda/repos/wsl-ubuntu/x86_64/cuda-keyring_1.0-1_all.deb
dpkg -i cuda-keyring_1.0-1_all.deb
apt-get update
apt-get -y install cuda
/usr/local/bin/python -m pip install --upgrade pip
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install git+https://git@github.com/SKTBrain/KoBERT.git@master
pip install pandas jupyter
```

# Run
```pyhon
cd KoBERT
python KoBERT.py
```
