# paddleocr_persian

### This repository generated for text recognition paddleocr on the Shotor dataset.


## Steps to install the paddleocr package dependency:


## 1)Install Paddleocr compatible with the system (cuda11.2 & system linux)

python -m pip install paddlepaddle-gpu==2.4.1.post112 -f https://www.paddlepaddle.org.cn/whl/linux/mkl/avx/stable.html

## 2)clone Paddleocr

git clone https://github.com/PaddlePaddle/PaddleOCR.git

## 3)cd directory Paddleocr

cd /PaddleOCR

## 4)install requirement

pip install -r requirements.txt

## 5)insert dataset on Paddleocr directory (make folder dataset)

/Paddleocr/dataset


## 6) download dataset shotor from google drive 
 [Dataset Shotor] (https://drive.google.com/file/d/1kj8wQ45R63Gyp-Qv2mJaa1C4Y0u1JgEC/view?usp=sharing, https://drive.google.com/file/d/1zrZUJjeJgz0iAVeK8QmMZVAUdPDSpman/view?usp=sharing)

## 6) download pretrained model

mkdir pretrained_model

cd pretrained_model/

wget  https://paddleocr.bj.bcebos.com/PP-OCRv3/multilingual/arabic_PP-OCRv3_rec_train.tar

tar -xvf "arabic_PP-OCRv3_rec_train.tar"

rm -rf arabic_PP-OCRv3_rec_train.tar

