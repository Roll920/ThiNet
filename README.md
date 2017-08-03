# ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression


Pretrained [caffe](https://github.com/BVLC/caffe) model of ICCV'17 paper:

"[ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression](https://arxiv.org/abs/1707.06342)"

For more details, please see our project page: [[ThiNet Project Page]](http://lamda.nju.edu.cn/luojh/project/ThiNet_ICCV17/ThiNet_ICCV17.html)


## Models

center 224x224 crop validation accuracy on ImageNet. We test on one M40 GPU with batch_size=32.

| Model  | Top-1 | Top-5 | #Param. | #FLOPs | f./b. (ms) |
| ------------- | ------------- | ------------- |  ------------- |  ------------- |  ------------- | 
| [ThiNet-GAP](http://lamda.nju.edu.cn/luojh/project/ThiNet_ICCV17/caffe_model/ThiNet-GAP.zip)  | 67.34%  | 87.92%  | 8.32M | 9.34B | 71.73/145.51 |
| [ThiNet-Tiny](http://lamda.nju.edu.cn/luojh/project/ThiNet_ICCV17/caffe_model/ThiNet-Tiny.zip) | 59.34% | 81.97% | 	1.32M | 2.01B | 29.51/55.83 |

**Note: These two models are trained with different image cropping method, see ``trainval.prototxt`` for more details.**



## Citation
If you find this work useful for your research, please cite:
```
@article{ThiNet_ICCV17,
  title={ThiNet: A Filter Level Pruning Method for Deep Neural Network Compression},
  author={Jian-Hao Luo, Jianxin Wu, and Weiyao Lin},
  journal={arXiv preprint arXiv:1707.06342},
  year={2017}
}
```

## Contact
Feel free to contact me if you have any question (Jian-Hao Luo luojh@lamda.nju.edu.cn).
