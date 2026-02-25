# Pytorch 环境搭建

## 先查看自己是否有GPU

cmd中输入nvidia-smi查看自己显卡型号和CUDA版本



![image-20260225225505001](./images/image-20260225225505001.png)

## 安装Anaconda

下载地址：[Index of /anaconda/archive/ | 清华大学开源软件镜像站 | Tsinghua Open Source Mirror](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/)

![image-20260225231245647](./images/image-20260225231245648.png)

![image-20260225231509432](./images/image-20260225231509432.png)

### 配置环境变量

环境变量里选择path

![image-20260225232121061](./images/image-20260225232121061.png)

添加这三个环境变量后保存

![image-20260225232319177](./images/image-20260225232319177.png)

### 验证是否安装成功

![image-20260225232443337](./images/image-20260225232443337.png)

打开Anaconda Prompt后输入conda --version回显版本号代表安装成功

![image-20260225232554825](./images/image-20260225232554825.png)

## 创建虚拟环境

conda create -n pytorch python=3.10

![image-20260225233000737](./images/image-20260225233000737.png)

## 激活虚拟环境

conda activate pytorch

下载pytorch

pip install torch==2.7.0 torchvision==0.22.0 torchaudio==2.7.0 --index-url https://download.pytorch.org/whl/cu118

![image-20260225235304228](./images/image-20260225235304228.png)

验证是否安装成功，返回True代表安装成功了


![image-20260225235530653](./images/image-20260225235530653.png)
