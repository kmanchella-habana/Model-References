# Habana Deep Learning Examples for Training

***Please make sure that the version of the SynapseAI software stack installation
matches the version of the Docker images you are using. Our documentation on
docs.habana.ai is also versioned, so select the appropriate version.  The [Setup
and Installation](https://github.com/HabanaAI/Setup_and_Install) Github repository as well as the Model-References GitHub
repository have branches for each release version. Make sure you are selecting
the branch that matches the version of your SynapseAI software installation. For
example, if SynapseAI software version 0.15.4 is installed, then you would clone
the Model-References repository like this:***

```bash
% git clone -b 0.15.4 https://github.com/HabanaAI/Model-References
```

***To identify the SynapseAI software version installed, run the
[hl-smi](https://docs.habana.ai/en/latest/System_Management_Tools_Guide/System_Management_Tools.html#hl-smi-utility-options)
tool and look at the “Driver Version”.***

## Model List and Performance Data

Please visit [this page](https://developer.habana.ai/resources/habana-training-models/#performance) for performance information.

This repository is a collection of models that have been ported to run on Habana Gaudi training accelerators. They are intended as examples, and will be reasonably optimized for performance while still being easy to read.

## Computer Vision
| Models  | Framework |
| ------------- | ------------- |
| [ResNet 50 Keras](TensorFlow/computer_vision/Resnets/resnet_keras) | TensorFlow |
| [ResNeXt 50, 101, 152](TensorFlow/computer_vision/Resnets)  |TensorFlow |
| [SSD](TensorFlow/computer_vision/SSD_ResNet34) |TensorFlow |
| [Mask R-CNN](TensorFlow/computer_vision/maskrcnn) |TensorFlow |
| [DenseNet Keras](TensorFlow/computer_vision/densenet_keras) |TensorFlow |
| [UNet 2D](TensorFlow/computer_vision/Unet2D) | TensorFlow |
| [ResNet50, ResNext101](PyTorch/computer_vision/ImageClassification/ResNet)  | PyTorch |

## Natural Language Processing
| Models  | Framework |
| ------------- | ------------- |
| [BERT](TensorFlow/nlp/bert) | TensorFlow |
| [ALBERT](TensorFlow/nlp/albert) | TensorFlow |
| [Transformer](TensorFlow/nlp/transformer) | TensorFlow |
| [BERT](PyTorch/nlp/bert) | PyTorch |

## Recommender Systems
| Models  | Framework |
| ------------- | ------------- |
| [DLRM](PyTorch/recommendation/dlrm) | PyTorch |

## Reporting Bugs/Feature Requests

We welcome you to use the [GitHub issue tracker](https://github.com/HabanaAI/Model-References/issues) to report bugs or suggest features.

When filing an issue, please check existing open, or recently closed, issues to make sure somebody else hasn't already
reported the issue. Please try to include as much information as you can. Details like these are incredibly useful:

* A reproducible test case or series of steps
* The version of our code being used
* Any modifications you've made relevant to the bug
* Anything unusual about your environment or deployment
