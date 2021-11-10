Graph Convolutional Networks in PyTorch
====

PyTorch implementation of Graph Convolutional Networks (GCNs) for semi-supervised classification [1].
I used pytorch version to perform analysis to see effects of changing the number of layers, adding symmetric normalization, using GPU to understand accuracy deviation of the GCN. Pygcn.ipynb contains notebook used.


![Graph Convolutional Networks](figure.png)

This implementation makes use of the Cora dataset from [2].

## Installation

```python setup.py install```

## Requirements
  
  * PyTorch 0.4 or 0.5
  * Python 2.7 or 3.6

## Usage


```python train.py```

## References

[1] [Kipf & Welling, Semi-Supervised Classification with Graph Convolutional Networks, 2016](https://arxiv.org/abs/1609.02907)

[2] [Sen et al., Collective Classification in Network Data, AI Magazine 2008](http://linqs.cs.umd.edu/projects/projects/lbc/)

## Cite

Please cite this paper if you use this code in your own work:

```
@article{kipf2016semi,
  title={Semi-Supervised Classification with Graph Convolutional Networks},
  author={Kipf, Thomas N and Welling, Max},
  journal={arXiv preprint arXiv:1609.02907},
  year={2016}
}
```
