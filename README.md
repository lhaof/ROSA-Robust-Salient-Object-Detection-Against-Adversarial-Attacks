# ROSA: Robust Salient Object Detection Against Adversarial Attacks

## Updated on 2020/5/31: the code of segmentwise shielding and bilateral filter have not been released. You may re-implement them by yourself. I may update the implementation later.

This is an implementation of 'ROSA: Robust Salient Object Detection Against Adversarial Attacks', published in IEEE Transactions on Cybernetics, 2019. 

If you find this code helpful, please cite the following paper.
```
@article{li2019rosa,
  title={ROSA: Robust Salient Object Detection Against Adversarial Attacks},
  author={Li, Haofeng and Li, Guanbin and Yu, Yizhou},
  journal={IEEE Transactions on Cybernetics},
  pages={1--13},
  year={2019}
}
```

## How to Use
Our method is a robust framework that protect a FCN from adversarial attacks. Our method consists of three components: segmentwise pixel shuffling, FCN backbone, CRF refinement. The code of pixel shuffling has not been released. The pairwise energy term is defined by the output of bilateral filter. The code of bilateral filtering has not been released. You may implement them by yourself.

The following is the model weights of a trained DSS+ROSA:

https://pan.baidu.com/s/1YV1NnBPbE_Usy57Y7C5fUQ password: lipc
