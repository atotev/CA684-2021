## c684-2021

#### Starting Nvidia Tensorflow Docker Image
`docker run --shm-size=1g --ulimit memlock=-1 --ulimit stack=67108864 --name c684-2021-tf -it --gpus all -p 8888:8888 -p 16006:16006 -v /src/c684-2021:/workspace/C684_Assignment nvcr.io/nvidia/tensorflow:21.02-tf2-py3`

#### Starting Nvidia PyTorch Docker Image (AMNet)
`docker run --gpus all --shm-size 8G -it -v /src/AMNet:/C684_Assignment nvcr.io/nvidia/pytorch:20.12-py3`

Note: AMNet fork with modifications - https://github.com/atotev/AMNet

#### Attention Maps Signal Example
![](att_maps-video10001.gif)
