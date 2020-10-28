## Сетап

```
git clone https://github.com/KonstantinKlepikov/graph_nets-1.git

git checkout -b GCN orgin/GCN

pip install -r requirements.txt
```

GCN_pytorch_simple.ipynb просто пример сверточной графовой сети

GCN_torchgeometric.ipynb пример с использованием torch_geometric

GCN_intro.ipynb небольшое интро
зшусу ща офлу

GCNs draw on the idea of Convolution Neural Networks re-defining them for the non-euclidean data domain. They are  convolutional, because filter parameters are typically shared over all locations in the graph unlike typical GNNs. 
- [GCN Blog](https://dsgiitr.com/blogs/gcn)
- [Jupyter Notebook](https://github.com/dsgiitr/graph_nets/blob/master/GCN/GCN_Blog%2BCode.ipynb)
- [Code](https://github.com/dsgiitr/graph_nets/blob/master/GCN/GCN.py)
- [Paper -> Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907)
