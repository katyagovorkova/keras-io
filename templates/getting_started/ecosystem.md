# The Keras ecosystem

The Keras project isn't limited to the core Keras API for building and training neural networks.
It spans a wide range of related initiatives that cover every step of the machine learning workflow.

---

## KerasTuner

[KerasTuner Documentation](/keras_tuner/) - [KerasTuner GitHub repository](https://github.com/keras-team/keras-tuner)


KerasTuner is an easy-to-use, scalable hyperparameter optimization framework that solves the pain points of hyperparameter search. Easily configure your search space with a define-by-run syntax, then leverage one of the available search algorithms to find the best hyperparameter values for your models. KerasTuner comes with Bayesian Optimization, Hyperband, and Random Search algorithms built-in, and is also designed to be easy for researchers to extend in order to experiment with new search algorithms.

---

## AutoKeras

[AutoKeras Documentation](https://autokeras.com/) - [AutoKeras GitHub repository](https://github.com/keras-team/autokeras)

AutoKeras is an AutoML system based on Keras. It is developed by [DATA Lab](http://faculty.cs.tamu.edu/xiahu/index.html) at Texas A&M University.
The goal of AutoKeras is to make machine learning accessible for everyone. It provides high-level end-to-end APIs
such as [`ImageClassifier`](https://autokeras.com/tutorial/image_classification/) or
[`TextClassifier`](https://autokeras.com/tutorial/text_classification/) to solve machine learning problems in a few lines,
as well as [flexible building blocks](https://autokeras.com/tutorial/customized/) to perform architecture search.


---

## TensorFlow.js

[TensorFlow.js](https://www.tensorflow.org/js) is TensorFlow's JavaScript runtime, capable of running TensorFlow models in the browser or on a [Node.js](https://nodejs.org/en/) server,
both for training and inference. It natively supports loading Keras models, including the ability to fine-tune or retrain your Keras models directly in the browser.


---

## TensorFlow Lite

[TensorFlow Lite](https://www.tensorflow.org/lite) is a runtime for efficient on-device inference that has native support for Keras models.
Deploy your models on Android, iOS, or on embedded devices.


---

## Model optimization toolkit

The [TensorFlow Model Optimization Toolkit](https://www.tensorflow.org/model_optimization) is a set of utilities to make your inference models faster, more memory-efficient,
and more power-efficient, by performing *post-training weight quantization* and *pruning-aware training*.
It has native support for Keras models, and its pruning API is built directly on top on the Keras API.


---

## TFX integration

TFX is an end-to-end platform for deploying and maintaining production machine learning pipelines.
TFX has [native support for Keras models](https://www.tensorflow.org/tfx/guide/keras).


---



