#  Graph Contrastive Learning with Low-Rank Attention (LRA-GCL)
Implementation of Graph Contrastive Learning with Low-Rank Attention (LRA-GCL).
## Requirements
```
h5py==2.9.0
pandas==0.25.1
numpy==1.17.2
torch==1.7.0
torch-geometric==1.6.1
munkres==1.0.12
scipy==1.3.1
scikit_learn==0.22.1
networkx==2.6.3
```

## Sample Run 
Python train.py --dataset cora --lr 0.01 --epochs 500 --lambda 0.1 --gamma 0.2
