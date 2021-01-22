# NICF
- added conda environment nicf.yml file

## TODO:
- add docstrings


## To run from windows:
- copy data from benchmark datasets into data folder ./data/data
    - ml-100k
- python launch.py -data_path ./data/data/ -environment env -T 40 -ST [5,10,20,40] -agent Train -FA FA -latent_factor 50 \
-learning_rate 0.001 -training_epoch 3000 -seed 145 -gpu_no 0 -inner_epoch 50 -rnn_layer 2 -gamma 0.8 -batch 50 -restore_model False


## Citation:


```
@inproceedings{10.1145/3397271.3401181,
author = {Zou, Lixin and Xia, Long and Gu, Yulong and Zhao, Xiangyu and Liu, Weidong and Huang, Jimmy Xiangji and Yin, Dawei},
title = {Neural Interactive Collaborative Filtering},
year = {2020},
isbn = {9781450380164},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3397271.3401181},
doi = {10.1145/3397271.3401181},
booktitle = {Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval},
pages = {749–758},
numpages = {10},
keywords = {recommender systems, cold start, meta-learning, reinforcement learning},
location = {Virtual Event, China},
series = {SIGIR '20}
}
```