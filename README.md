# paddleocr_persian

###This repository to run paddleocr on the Shotor dataset.


## Steps to install the paddleocr package dependency:


# 1)Install paddleocr compatible with the system (cuda11.2 & system linux)

python -m pip install paddlepaddle-gpu==2.4.1.post112 -f https://www.paddlepaddle.org.cn/whl/linux/mkl/avx/stable.html

# 2)clone paddleocr

git clone https://github.com/PaddlePaddle/PaddleOCR.git

# 3)cd directory Paddleocr

cd /PaddleOCR

# 4)install requirement

pip install -r requirements.txt

# 5)
# !cp /content/drive/MyDrive/pretrain_models -r /content/PaddleOCR #model train on dataset shotor
# !mkdir pretrained_model
# %cd pretrained_model/
# !wget  https://paddleocr.bj.bcebos.com/PP-OCRv3/multilingual/arabic_PP-OCRv3_rec_train.tar
# !tar -xvf "arabic_PP-OCRv3_rec_train.tar"
# !rm -rf arabic_PP-OCRv3_rec_train.tar
