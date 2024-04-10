# Fisher-Markov-Selector

## This is the python implementation of the paper ["The Fisher-Markov Selector: Fast Selecting Maximally Separable Feature Subset for Multi-Class Classification with Applications to High-Dimensional Data"](https://picture.iczhiku.com/resource/paper/wHifiaTUwqZrkmMX.pdf).

The code has two steps for linear feature selection:

1) Calculating the coefficients of features (θj): by default, the program uses γ = -0.5.
2) We use β as a threshold to select important features with coefficients ≥ β.


## How to cite

If you find this repository useful in your work, please consider citing it:

``` bibtex
@article{cheng2010fisher,
  title={The fisher-markov selector: fast selecting maximally separable feature subset for multiclass classification with applications to high-dimensional data},
  author={Cheng, Qiang and Zhou, Hongbo and Cheng, Jie},
  journal={IEEE transactions on pattern analysis and machine intelligence},
  volume={33},
  number={6},
  pages={1217--1233},
  year={2010},
  publisher={IEEE}
}

Aram Ansary Ogholbake is the author of the python implementation.
```



