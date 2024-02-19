# Training neural networks with Tensorflow 2 and the Keras Functional API

The Sequential model API is great for developing deep learning models in most situations, but it also has some limitations. One example is that it is not straightforward to define models that may have multiple different input sources, produce multiple output destinations or models that re-use layers. The Keras Functional API is a way to create models that are more flexible than the tf.keras.Sequential API. The functional API can handle models with non-linear topology, models with shared layers, and models with multiple inputs or outputs. The Keras Functional API provides a more flexible way for defining models. It specifically allows you to define multiple input or output models as well as models that share layers. More than that, it allows you to define ad hoc acyclic network graphs. The main idea that a deep learning model is usually a directed acyclic graph (DAG) of layers. So the Functional API is a way to build graphs of layers. Additionally, we will also talk about how regularization can help with model performance.

## Learning Objectives

- Understand embeddings and how to create them with the feature column API
- Understand Deep and Wide models and when to use them
- Understand the Keras Functional API and how to build a deep and wide model with it
- Understand how regularization can help improve the performance of a model.

## Training neural networks with Tensorflow 2 and Keras Functional API

- [Video - Neural Networks with Keras Functional API](https://www.coursera.org/learn/intro-tensorflow/lecture/MwZp4/neural-networks-with-keras-functional-api)

- [Video - Regularization: The Basics](https://www.coursera.org/learn/intro-tensorflow/lecture/PV6Bl/regularization-the-basics)

- [Video - Regularization: L1, L2, and Early Stopping](https://www.coursera.org/learn/intro-tensorflow/lecture/nrWEF/regularization-l1-l2-and-early-stopping)

- [Video - Regularization: Dropout](https://www.coursera.org/learn/intro-tensorflow/lecture/Jg9u8/regularization-dropout)

- [Video - Serving models in the Cloud](https://www.coursera.org/learn/intro-tensorflow/lecture/t5bwl/serving-models-in-the-cloud)

- [Video - Lab intro Keras Functional API](https://www.coursera.org/learn/intro-tensorflow/lecture/BcfHC/lab-intro-keras-functional-api)

- [Lab - The Keras Functional API](./Labs/4_keras_functional_api.ipynb)

- [Reading - Readings](https://www.coursera.org/learn/intro-tensorflow/supplement/Rrqls/readings)

---

# Summary

Here we summarize the TensorFlow topics we covered so far in this course. We'll revisit core TensorFlow code, the tf.data API, Keras Sequential and Functional APIs and end with scaling your machine learning models with Cloud AI Platform.

## Learning Objectives

- Recap the TensorFlow topics covered from the basics, to the Keras Sequential and Functional APIs, the tf.data.Dataset API, and more

## Module Summary

- [Video - Course Summary](https://www.coursera.org/learn/intro-tensorflow/lecture/fCFux/course-summary)

- [Reading - Quiz Questions to ALL Lessons](https://www.coursera.org/learn/intro-tensorflow/supplement/ziVvN/quiz-questions-to-all-lessons)

- [Reading - Course Slide](https://www.coursera.org/learn/intro-tensorflow/supplement/7SZLp/course-slide)