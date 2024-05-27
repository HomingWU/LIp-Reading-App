# LIp-Reading-App
Keras implementation of the method described in the paper 'LipNet: End-to-End Sentence-level Lipreading' by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (https://arxiv.org/abs/1611.01599).

## Results
|       Scenario          | Epoch |  CER  |  WER  |  BLEU |
|:-----------------------:|:-----:|:-----:|:-----:|:-----:|
|  Unseen speakers [C]    |  N/A  |  N/A  |  N/A  |  N/A  |
|    Unseen speakers      |  178  |  6.19%  |  14.19%  |  88.21%  |
| Overlapped speakers [C] |  N/A  |  N/A  |  N/A  |  N/A  |
|   Overlapped speakers   |  368  |  1.56%  |  3.38%  |  96.93%  |

**Notes**:

- [C] means using curriculum learning.
- N/A means either the training is in progress or hasn't been performed.
- Your contribution in sharing the results of this model is highly appreciated :)

## Dependencies
* Keras 2.10.0
* TensorFlow 2.10.1
* PIP (for package installation)

## Dataset
This model uses GRID corpus (http://spandh.dcs.shef.ac.uk/gridcorpus/)

## Pre-trained weights
For those of you who are having difficulties in training the model (or just want to see the results), you can download and use the weights provided in the [weights]( model/) (trained by s1 dataset)

More details on saving and loading weights can be found in [Keras FAQ](https://keras.io/getting-started/faq/#how-can-i-save-a-keras-model).
