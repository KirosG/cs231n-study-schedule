# CS231n: Convolutional Neural Networks for Visual Recognition (Spring 2017)
cs231n learning notes

Website: [Convolutional Neural Networks for Visual Recognition (Spring 2017)](http://cs231n.stanford.edu/index.html)

Video: [CS231n Spring 2016](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)

**Course Syllabus**
##  **Lecture 1:**  Course Introduction  [**done!!!**]

### [slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture1.pdf) [**done!!!**]
- Computer vision overview 
- Historical context 
- Course logistics
### [video](https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) [**done!!!**]

## **Lecture 2:** Image Classification [**done!!!**]
### [slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture2.pdf) [**done!!!**]
- The data-driven approach 
- K-nearest neighbor 
- Linear classification I
### [video](https://www.youtube.com/watch?v=8inugqHkfvE&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=2) [**done!!!**]
### [python/numpy tutorial](http://cs231n.github.io/python-numpy-tutorial/) [**done!!!**]
### [image classification notes](http://cs231n.github.io/classification) [**done!!!**]
- Intro to Image Classification, data-driven approach, pipeline
- Nearest Neighbor Classifier
  - k-Nearest Neighbor
- Validation sets, Cross-validation, hyperparameter tuning
- Pros/Cons of Nearest Neighbor
  - [x] *accelerate the nearest neighbor lookup in a dataset (e.g. [FLANN](http://www.cs.ubc.ca/research/flann/))*
  - [x] *a visualization technique called [t-SNE](http://lvdmaaten.github.io/tsne/)*
- Summary
- Summary: Applying kNN in practice
  - [x] *If your data is very high-dimensional, consider using a dimensionality reduction technique such as PCA([wiki ref](http://en.wikipedia.org/wiki/Principal_component_analysis), [CS229ref](http://cs229.stanford.edu/notes/cs229-notes10.pdf), [blog ref](http://www.bigdataexaminer.com/understanding-dimensionality-reduction-principal-component-analysis-and-singular-value-decomposition/) )or even [Random Projections](http://scikit-learn.org/stable/modules/random_projection.html).*

- Further Reading

  Here are some (optional) links you may find interesting for further reading:

  - [x] *[A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf), where especially section 6 is related but the whole paper is a warmly recommended reading.*
  - [x] *[Recognizing and Learning Object Categories](http://people.csail.mit.edu/torralba/shortCourseRLOC/index.html), a short course of object categorization at ICCV 2005.*

### [linear classification notes](http://cs231n.github.io/linear-classify/) [**done!!!**]
- Intro to Linear classification
- Linear score function
- Interpreting a linear classifier
- Loss function
  - Multiclass SVM
  - - [x] *For example, it turns out that including the L2 penalty leads to the appealing **max margin** property in SVMs (See [CS229](http://cs229.stanford.edu/notes/cs229-notes3.pdf) lecture notes for full details if you are interested).*
  - Softmax classifier
  - SVM vs Softmax
- Interactive Web Demo of Linear Classification
- Summary
- Further Reading

  These readings are optional and contain pointers of interest.

 - - [x] [Deep Learning using Linear Support Vector Machines](http://arxiv.org/abs/1306.0239) from Charlie Tang 2013 presents some results claiming that the L2SVM outperforms Softmax.

## **Lecture3 :** Loss Functions and Optimization  [**done!!!**]

### [slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture3.pdf) [**done!!!**]
- Linear classification II
- Higher-level representations, image features
- Optimization, stochastic gradient descent

### [video](https://www.youtube.com/watch?v=qlLChbHhbg4&index=3&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) [**done!!!**]

### [linear classification notes](http://cs231n.github.io/linear-classify/) [**done!!!**] 

*same to Lecture2: linear classification notes*

- [x] [Linear Classification Loss Visualization Demo](http://vision.stanford.edu/teaching/cs231n-demos/linear-classify/)

### [optimization notes]() [**done!!!**]

- Introduction
- Visualizing the loss function

  - [x] *a Stanford class on the topic [convex optimization](http://stanford.edu/~boyd/cvxbook/)* (other project)
  - [x] *[Subderivative](https://en.wikipedia.org/wiki/Subderivative)*
- Optimization
  - Strategy #1: Random Search
  - Strategy #2: Random Local Search
  - Strategy #3: Following the gradient
- Computing the gradient
  - Numerically with finite differences
  - Analytically with calculus
- Gradient descent
- Summary


------

# **MARK!!!**

------



## **Lecture4:** Introduction to Neural Networks  [**done!!!**]

### [slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture4.pdf) [**done!!!**]

- Backpropagation
- Multi-layer Perceptrons
- The neural viewpoint

### [video]() [**done!!!**]

- [x] [Neural Networks Part 1](https://www.youtube.com/watch?v=i94OvYb6noo&index=4&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) [**done!!!**]
- [x] [Neural Networks Part 2](https://www.youtube.com/watch?v=gYpoJMlgyXA&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=5) [**done!!!**]

### [backprop notes](http://cs231n.github.io/optimization-2/) [**done!!!**]

- Introduction
- Simple expressions, interpreting the gradient
- Compound expressions, chain rule, backpropagation
- Intuitive understanding of backpropagation
- Modularity: Sigmoid example
- Backprop in practice: Staged computation
- Patterns in backward flow
- Gradients for vectorized operations
  - [x] *[Vector, Matrix, and Tensor Derivatives](http://cs231n.stanford.edu/vecDerivs.pdf)* 
- Summary
- References
  - [x] *[Automatic differentiation in machine learning: a survey](http://arxiv.org/abs/1502.05767)*

### [linear backprop example](http://cs231n.stanford.edu/handouts/linear-backprop.pdf) [**done!!!**]

### [derivatives notes](http://cs231n.stanford.edu/handouts/derivatives.pdf) (optional) [**done!!!**]

### [Efficient BackProp](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf) (optional) [**done!!!**]

### [Related]() (optional) [**done!!!**]

- [x] [Calculus on Computational Graphs: Backpropagation](http://colah.github.io/posts/2015-08-Backprop/)
- [x] [How the backpropagation algorithm works](http://neuralnetworksanddeeplearning.com/chap2.html)
- [x] [Video: Learning: Neural Nets, Back Propagation](https://www.youtube.com/watch?v=q0pm3BrIUFo)

## **Lecture5：** Convolutional Neural Networks [**done!!!**]

### [slides](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture5.pdf) [**done!!!**]
- History 

- Convolution and pooling 

- ConvNets outside vision

## [video]() [**done!!!**]
- [x] [ Neural Networks Part 3 / Intro to ConvNets](https://www.youtube.com/watch?v=hd_KFJ5ktUc&index=6&t=713s&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) [**done!!!**]
- [x] [ Convolutional Neural Networks](https://www.youtube.com/watch?v=LxfUGhug-iQ&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=7) [**done!!!**]

### [ConvNet notes](http://cs231n.github.io/convolutional-networks/) [**done!!!**]

- Architecture Overview
- ConvNet Layers
  - Convolutional Layer
    - [x] *The [Krizhevsky et al](http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks). architecture that won the ImageNet challenge in 2012 accepted images of size [227x227x3].*
    - [x] *However, the benefit is that there are many very efficient implementations of Matrix Multiplication that we can take advantage of (for example, in the commonly used [BLAS](http://www.netlib.org/blas/) API).*
    - [x] *As an aside, several papers use 1x1 convolutions, as first investigated by [Network in Network](http://arxiv.org/abs/1312.4400).*
    - [x] *A recent development (e.g. see [paper by Fisher Yu and Vladlen Koltun](https://arxiv.org/abs/1511.07122)) is to introduce one more hyperparameter to the CONV layer called the **dilation**.*
  - Pooling Layer
    - [x] *Many people dislike the pooling operation and think that we can get away without it. For example, [Striving for Simplicity: The All Convolutional Net](http://arxiv.org/abs/1412.6806) proposes to discard the pooling layer in favor of architecture that only consists of repeated CONV layers.*
  - Normalization Layer
    - [x] *For various types of normalizations, see the discussion in Alex Krizhevsky’s [cuda-convnet library API](http://code.google.com/p/cuda-convnet/wiki/LayerParams#Local_response_normalization_layer_(same_map)).*
  - Fully-Connected Layer
  - Converting Fully-Connected Layers to Convolutional Layers
    - [x] *An IPython Notebook on [Net Surgery](https://github.com/BVLC/caffe/blob/master/examples/net_surgery.ipynb) shows how to perform the conversion in practice, in code (using Caffe)*
- ConvNet Architectures
  - Layer Patterns
    - [x] *You should rarely ever have to train a ConvNet from scratch or design one from scratch. I also made this point at the [Deep Learning school](https://www.youtube.com/watch?v=u6aEYuemt0M).*
  - Layer Sizing Patterns
  - Case Studies (LeNet / AlexNet / ZFNet / GoogLeNet / VGGNet)
    - [x] **LeNet** ([LeNet](http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf))
    - [x] **AlexNet** ([AlexNet](http://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks), [ImageNet ILSVRC challenge](http://www.image-net.org/challenges/LSVRC/2014/))
    - [x] **ZF Net** ([ZF Net](http://arxiv.org/abs/1311.2901))
    - [x] **GoogLeNet** ([Szegedy et al](http://arxiv.org/abs/1409.4842), [Inception-v4](http://arxiv.org/abs/1602.07261))
    - [x] **VGGNet** ([VGGNet](http://www.robots.ox.ac.uk/~vgg/research/very_deep/), [pretrained model](http://www.robots.ox.ac.uk/~vgg/research/very_deep/))
    - [x] **ResNet** ([Residual Network](http://arxiv.org/abs/1512.03385), [batch normalization](http://arxiv.org/abs/1502.03167), some [recent experiments](https://github.com/gcr/torch-residual-networks), Kaiming’s presentation ([video](https://www.youtube.com/watch?v=1PGLj-uKT1w), [slides](http://research.microsoft.com/en-us/um/people/kahe/ilsvrc15/ilsvrc2015_deep_residual_learning_kaiminghe.pdf)), [Kaiming He et al. Identity Mappings in Deep Residual Networks](https://arxiv.org/abs/1603.05027) (published March 2016))
  - Computational Considerations
- Additional References
  - [x] [Soumith benchmarks for CONV performance](https://github.com/soumith/convnet-benchmarks)
  - [x] [ConvNetJS CIFAR-10 demo](http://cs.stanford.edu/people/karpathy/convnetjs/demo/cifar10.html) allows you to play with ConvNet architectures and see the results and computations in real time, in the browser.
  - [x] [Caffe](http://caffe.berkeleyvision.org/), one of the popular ConvNet libraries.
  - [x] [State of the art ResNets in Torch7](http://torch.ch/blog/2016/02/04/resnets.html)

## **Lecture 6:**  Training Neural Networks, part I [** **]

### [slides]() [**done!!!**]
- Activation functions, initialization, dropout, batch normalization

### [video]() [**done!!!**]

- [x] [Neural Networks Part 1](https://www.youtube.com/watch?v=i94OvYb6noo&index=4&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) [**done!!!**]
- [x] [Neural Networks Part 2](https://www.youtube.com/watch?v=gYpoJMlgyXA&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC&index=5) [**done!!!**]
- [x] [ Neural Networks Part 3 / Intro to ConvNets](https://www.youtube.com/watch?v=hd_KFJ5ktUc&index=6&t=713s&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC) [**done!!!**]

### [Neural Nets notes 1](http://cs231n.github.io/neural-networks-1/) [**done!!!**]

- Quick intro without brain analogies
- Modeling one neuron
  - Biological motivation and connections
  - Single neuron as a linear classifier
  - Commonly used activation functions
    - [x] ***Tanh**, [Krizhevsky et al](http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf)*
    - [x] ***Leaky ReLU**, [Delving Deep into Rectifiers](http://arxiv.org/abs/1502.01852)*
    - [x] ***Maxout**, One relatively popular choice is the Maxout neuron (introduced recently by [Goodfellow et al.](http://www-etud.iro.umontreal.ca/~goodfeli/maxout.html))*
- Neural Network architectures
  - Layer-wise organization
  - Example feed-forward computation
  - Representational power
    - [x] *see [Approximation by Superpositions of Sigmoidal Function](http://www.dartmouth.edu/~gvc/Cybenko_MCSS.pdf) from 1989 (pdf), or this [intuitive explanation](http://neuralnetworksanddeeplearning.com/chap4.html) from Michael Nielsen*
    - [x] *much more involved and a topic of much recent research. If you are interested in these topics we recommend for further reading:*
          - [x] *Deep Learning book in press by Bengio, Goodfellow, Courville, in particular [Chapter 6.4](http://www.deeplearningbook.org/contents/mlp.html).*
          - [x] *[Do Deep Nets Really Need to be Deep?](http://arxiv.org/abs/1312.6184)*
          - [x] *[FitNets: Hints for Thin Deep Nets](http://arxiv.org/abs/1412.6550)*
  - Setting number of layers and their sizes
    - [x] *but some attempts to understand these objective functions have been made, e.g. in a recent paper [The Loss Surfaces of Multilayer Networks](http://arxiv.org/abs/1412.0233).*
- Summary
- Additional references
 - [ ] [deeplearning.net tutorial](http://www.deeplearning.net/tutorial/mlp.html) with Theano
 - [ ] [ConvNetJS](http://cs.stanford.edu/people/karpathy/convnetjs/) demos for intuitions
 - [ ] [Michael Nielsen’s](http://neuralnetworksanddeeplearning.com/chap1.html) tutorials

### [Neural Nets notes 2](http://cs231n.github.io/neural-networks-2/) [**done!!!**]

- Setting up the data and the model
  - Data Preprocessing
    - [x] *[Principal Component Analysis (PCA)](http://en.wikipedia.org/wiki/Principal_component_analysis)* 
  - Weight Initialization
    - [x] *[Understanding the difficulty of training deep feedforward neural networks ](http://jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf)*
    - [x] *[Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification](http://arxiv-web3.library.cornell.edu/abs/1502.01852)*
  - Batch Normalization
    - [x] *[Batch Normalization](http://arxiv.org/abs/1502.03167)*
  - Regularization (L2/L1/Maxnorm/Dropout)
    - [x] ***Dropout**, [Dropout: A Simple Way to Prevent Neural Networks from Overfitting](http://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf)*, Recommended further reading for an interested reader includes:*
     - [x] *[Dropout paper](http://www.cs.toronto.edu/~rsalakhu/papers/srivastava14a.pdf) by Srivastava et al. 2014.*
     - [x] *[Dropout Training as Adaptive Regularization](http://papers.nips.cc/paper/4882-dropout-training-as-adaptive-regularization.pdf): “we show that the dropout regularizer is first-order equivalent to an L2 regularizer applied after scaling the features by an estimate of the inverse diagonal Fisher information matrix”.*
- Loss functions
- Summary

### Neural Nets notes 3 [**done!!!**]
- Gradient checks
  - *Stick around active range of floating point. It’s a good idea to read through [“What Every Computer Scientist Should Know About Floating-Point Arithmetic”*](http://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)
- Sanity checks
- Babysitting the learning process
  - Loss function
  - Train/val accuracy
  - Weights:Updates ratio
  - Activation/Gradient distributions per layer
  - Visualization
- Parameter updates
  - First-order (SGD), momentum, Nesterov momentum
    - [x] *We recommend this further reading to understand the source of these equations and the mathematical formulation of Nesterov’s Accelerated Momentum (NAG):*
          - [x] *[Advances in optimizing Recurrent Networks]() by Yoshua Bengio, Section 3.5.*
          - [x] *[Ilya Sutskever’s thesis](http://www.cs.utoronto.ca/~ilya/pubs/ilya_sutskever_phd_thesis.pdf) (pdf) contains a longer exposition of the topic in section 7.2*
  - Annealing the learning rate
  - Second-order methods
    - [x] *Additional references:* 
          - [x] *[Large Scale Distributed Deep Networks](http://research.google.com/archive/large_deep_networks_nips2012.html) is a paper from the Google Brain team, comparing L-BFGS and SGD variants in large-scale distributed optimization.*
          - [x] *[SFO](http://arxiv.org/abs/1311.2115) algorithm strives to combine the advantages of SGD with advantages of L-BFGS.*
  - Per-parameter adaptive learning rates (Adagrad, RMSProp)
    - [x] ***Adagrad** is an adaptive learning rate method originally proposed by [Duchi et al.](http://jmlr.org/papers/v12/duchi11a.html)*
    - [x] ***RMSprop**, everyone who uses this method in their work currently cites [slide 29 of Lecture 6](http://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf) of Geoff Hinton’s Coursera class.*
    - [x] ***Adam**,  [Adam](http://arxiv.org/abs/1412.6980) is a recently proposed update that looks a bit like RMSProp with momentum.*
    - [x] *[Unit Tests for Stochastic Optimization](http://arxiv.org/abs/1312.6055) proposes a series of tests as a standardized benchmark for stochastic optimization.*
- Hyperparameter Optimization
  - [x] ***Prefer random search to grid search.** As argued by Bergstra and Bengio in [Random Search for Hyper-Parameter Optimization](http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf), “randomly chosen trials are more efficient for hyper-parameter optimization than trials on a grid”*
- Evaluation
  - Model Ensembles
- Summary
- Additional References
  - [x] [SGD](http://research.microsoft.com/pubs/192769/tricks-2012.pdf) tips and tricks from Leon Bottou
  - [x] [Efficient BackProp](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf) (pdf) from Yann LeCun
  - [x] [Practical Recommendations for Gradient-Based Training of Deep Architectures](http://arxiv.org/pdf/1206.5533v2.pdf) from Yoshua Bengio

### tips/tricks(optional) [**done!!!**]
 - [x] [Stochastic Gradient Descent Tricks](http://research.microsoft.com/pubs/192769/tricks-2012.pdf)
 - [x] [Efficient BackProp](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf)
 - [x] [Practical Recommendations for Gradient-Based Training ofDeepArchitectures](http://arxiv.org/pdf/1206.5533v2.pdf)
 - [x] [Deep learning](http://www.nature.com/nature/journal/v521/n7553/full/nature14539.html)

## [Assignment #1 due](http://cs231n.github.io/assignments2017/assignment1/) [**done!!!**]

### [k-Nearest Neighbor classifier](https://github.com/LoserSun/cs231n-study-schedule/blob/master/assignment1/knn.ipynb) [**done!!!**]

### [Training a Support Vector Machine](https://github.com/LoserSun/cs231n-study-schedule/blob/master/assignment1/svm.ipynb) [**done!!!**]

### [Implement a Softmax classifier](https://github.com/LoserSun/cs231n-study-schedule/blob/master/assignment1/softmax.ipynb) [**done!!!**]

### [Two-Layer Neural Network](https://github.com/LoserSun/cs231n-study-schedule/blob/master/assignment1/two_layer_net.ipynb) [**done!!!**]

### [Higher Level Representations: Image Features](https://github.com/LoserSun/cs231n-study-schedule/blob/master/assignment1/features.ipynb) [**done!!!**]