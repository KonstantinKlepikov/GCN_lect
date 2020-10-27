## Сетап

```
git clone https://github.com/KonstantinKlepikov/graph_nets-1.git

git checkout -b orgin/GCN GCN

pip install -r requirements.txt
```

<h2 align="center"> 2. A Review : Graph Convolutional Networks (GCN) </h2>
<img align="right" width="500x" src="/GCN/img/gcn_architecture.png">

GCNs draw on the idea of Convolution Neural Networks re-defining them for the non-euclidean data domain. They are  convolutional, because filter parameters are typically shared over all locations in the graph unlike typical GNNs. 
- [GCN Blog](https://dsgiitr.com/blogs/gcn)
- [Jupyter Notebook](https://github.com/dsgiitr/graph_nets/blob/master/GCN/GCN_Blog%2BCode.ipynb)
- [Code](https://github.com/dsgiitr/graph_nets/blob/master/GCN/GCN.py)
- [Paper -> Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907)
