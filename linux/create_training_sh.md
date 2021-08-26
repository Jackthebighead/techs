### create_training_sh
'Author: YUAN Yanzhe'
- sometimes you will need to run the training code on the backend process use the following commands
  - ```python 
       touch train.sh
       vim train.sh
       
       i
       echo hello world
       CUDA_VISIBLE_DEVICES=0 nohup python train.py > log/train.log 2>&1 & ( > ：一个>表示日志overwrite写入log文件）
       CUDA_VISIBLE_DEVICES=0 nohup python train.py >> log/train.log 2>&1 & （ >> ：连续两个>>表示日志append写入log文件）
       :wq
       
       chmod +x  xxx.sh
       mkdir log
       ./train.sh
    ```
