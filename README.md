##conda环境
conda create -n tryon python=3.6

source activate tryon     or     conda activate tryon

conda install pytorch=1.1.0 torchvision=0.3.0 cudatoolkit=9.0 -c pytorch

conda install cupy     or     pip install cupy==6.0.0

pip install opencv-python

##JAVA
jdk 1.8

IDEA 2021.3.2

##使用方法
1.IDEA启动项目

2.前端调用127.0.0.1/api/pic/uploadPic上传图片，后端所需的data为图片名称，图片base64码与图片类型。调用127.0.0.1/api/pic/uploadmodelPic上传模特图，所需data与上相同。调用127.0.0.1/api/pic/getPic可以得到结果图片的url。




