# [Physics-Informed Deep Operator Control](https://arxiv.org/abs/2112.14707)
Physics-Informed Deep Operator Control (PIDOC), a deep learning method for controlling nonlinear chaos.

![schematic view of Physics-Informed Deep Operator Control](/doc/PINC_schematic.jpg)

## What is PIDOC?

PIDOC is based on [PINNs](https://maziarraissi.github.io/PINNs/), is a general framework can be used for control nonlinear dynamics, achieved by the encoded control trajectory in the losses. Right now, PIDOC has only been used for control the [van der Pol systems](https://www.sciencedirect.com/topics/mathematics/van-der-pols-equation) ([Zhai & Sands, 2022](https://doi.org/10.3390/math10030453)). However, if carefully tuned, it can be applied to more complex systems.

## How to use PIDOC?

To play with our simple example cases, you need to first download and convert your [tensorflow](https://www.tensorflow.org/) to version [1.x](https://www.tensorflow.org/api_docs/python/tf/compat/v1/); ([Google Colab](https://colab.research.google.com/) is a great platform for it) or directly download it through

~~~
pip install tensorflow==1.15.0
~~~

Then download our repo:
~~~
git clone https://github.com/hanfengzhai/PIDOC
~~~

Open the simple case of the van der Pol dynamics:

~~~
cd vanderPol
~~~



## Why does PIDOC work?



## What's the limitation?


***

### Cite PIDOC

If you use our package please considering cite:
~~~
@Article{math10030453,
AUTHOR = {Zhai, Hanfeng and Sands, Timothy},
TITLE = {Controlling Chaos in Van Der Pol Dynamics Using Signal-Encoded Deep Learning},
JOURNAL = {Mathematics},
VOLUME = {10},
YEAR = {2022},
NUMBER = {3},
ARTICLE-NUMBER = {453},
URL = {https://doi.org/10.3390/math10030453},
ISSN = {2227-7390},
DOI = {10.3390/math10030453}
}
~~~
