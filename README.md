# MVP-re  
## 0612:  
1. 下载nuScenes数据集的Trainval和Test;  
2. 安装Apex:  
- `git clone https://github.com/NVIDIA/apex`  
- `cd apex`  
- `pip install -v --disable-pip-version-check --no-cache-dir ./`  
3. 新建一个conda环境：  
- `conda create -n MVP python=3.9`  
- `conda activate MVP`  
- `pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html`  
4. 安装Centeroint和detectron2
