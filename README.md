Fine-grained Image Retrieval
--------------------------
This is the Official Pytorch-Lightning implementation of the paper: "Fine-grained Hashing"(https://arxiv.org/abs/2). 
## Requirements
* Python3
* PyTorch
* PyTorch-Lightning
* Numpy
* pandas


--------------------------
## Dataset
We use the following 5 datasets: CUB200-2011, Aircraft, VegFru, NABirds and Food101.

--------------------------
## RUN

- The running commands for several datasets are shown below. 
```
python main.py --dataset cub --gpu 0, --batch_size=128 --code_length=32 --num_workers=4  --lr 0.008
python main.py --dataset aircraft --gpu 0, --batch_size=32 --code_length=32 --num_workers=4 --lr 0.035
python main.py --dataset vegfru --gpu 0, --batch_size=128 --code_length=32 --num_workers=4  --lr 0.005
python main.py --dataset nabirds --gpu 0, --batch_size=128 --code_length=32 --num_workers=4  --lr 0.008
python main.py --dataset food101 --gpu 0, --batch_size=128 --code_length=32 --num_workers=4  --lr 0.008
```


--------------------------
## Citation
If you find our work inspiring or use our codebase in your research, please cite our work.
```
@inproceedings{
    year={2023}
}
```