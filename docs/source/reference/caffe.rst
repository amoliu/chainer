Caffe Reference Model Support
=============================

.. module:: chainer.caffe

`Caffe <http://caffe.berkeleyvision.org/>`_ is a popular framework maintained by `BVLC <http://bvlc.eecs.berkeley.edu/>`_ at UC Berkeley.
It is widely used mainly by computer vision community, and aims at fast computation and easy usage without any programming.
BVLC team provides trained reference models in their `Model Zoo <http://caffe.berkeleyvision.org/model_zoo.html>`_, one of the reason why this framework gets popular.

Chainer can import the reference models and emulate the network by :class:`~chainer.Function` implementations.
This functionality is provided by the :class:`CaffeFunction` class.

.. autoclass:: CaffeFunction
   :members: __call__
