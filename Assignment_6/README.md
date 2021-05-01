Note that this assignment is 20 points (additional 30 points towards extra credit if you do all of the below including optional assignments - extra credit used for catchup on midterm and quiz).

 

Please use the pointers i provided as just guidance (not copy paste code) - please type it out - it is for your practice and perfection - the more you write code the more you will become comfortable.  and use your own creativity to improve/implement better versions and try to get state of art solutions in accuracy etc.,.. Organize your colab with proper comments and sections to make it readable.

 

 

Upload all colabs/artifacts in github.

 

the homework has five parts

 

a) MANDATORY:  Implement complete autograd framework in python and numpy  and mnist classifier using the autograd framework.

Reference : grokking deep learning book and samples in github  - Please use this as example and implement from scratch. write unittests for your code.

https://github.com/iamtrask/Grokking-Deep-Learning/blob/master/Chapter13%20-%20Intro%20to%20Automatic%20Differentiation%20-%20Let's%20Build%20A%20Deep%20Learning%20Framework.ipynb (Links to an external site.)

 

Extra points : If you implement a new activation function, new optimizer and new loss function in this code.

 

b) MANDATORY : Build an CNN based image classifier (at least 3 - 5 categories) from a custom data set you acquire (either from images.google.com or other places

 

Implement in both keras as well as pytorch lightning (two colabs)

 

Reference code : https://keras.io/examples/vision/image_classification_from_scratch/ (Links to an external site.)

https://learnopencv.com/getting-started-with-pytorch-lightning/ (Links to an external site.)

 

Note that you will be buidling your own custom data set - you can use tips from  https://forums.fast.ai/t/download-images-from-google-image-search/63188/4 (Links to an external site.) as an example. you need to resize the images and appropriately build data set. publish both dataset and classifier and colab with all metrics properly. Integrate with tensorboard.

some inspiration :

https://developers.google.com/codelabs/tensorflow-4-cnns?hl=en&continue=https%3A%2F%2Fcodelabs.developers.google.com%2F#0 (Links to an external site.)

 

Extra points : If you create your own pooling layer- https://www.tensorflow.org/tutorials/customization/custom_layers and also implement in.  plain pytorch (Links to an external site.)

pytorch pointers : https://colab.sandbox.google.com/github/omerbsezer/Fast-Pytorch/blob/master/Learning_Pytorch/Pytorch_Playground.ipynb (Links to an external site.)    and.  
https://colab.sandbox.google.com/github/pranjalchaubey/Deep-Learning-Notes/blob/master/PyTorch%20Image%20Classification%20in%202020/Image_Classification_practice.ipynb#scrollTo=J2lXpTfRk7JO (Links to an external site.)   and https://colab.sandbox.google.com/github/omerbsezer/Fast-Pytorch/blob/master/Learning_Pytorch/Improved_CNN_Mnist.ipynb  (Links to an external site.)

(https://www.reddit.com/r/learnmachinelearning/comments/bm3hkp/fastpytorch_with_google_colab_pytorch_tutorial/ (Links to an external site.)))

 

Optional EXTRA CREDITS assignments  for catchup on midterm and quizzes  - This is just part 1 of extra credits.

c) EXTRA CREDIT : Transfer learning with keras and pytorch lightning  using pretrained models

Use state of art pretrained model  (supervised and unsupervised models) for classification (one supervised pretrained model (like imagenet based from tfhub) and one unsupervised pretrained model - like CLIP)

Sample code : 

(see notes of slide)

https://docs.google.com/presentation/d/1UxtHDwjViC7VpSb0zB-kajGQ-TwznQmc-7LsbHRfO3s/edit#slide=id.gcf0aed8eda_1_213   ( (Links to an external site.)

https://colab.sandbox.google.com/github/openai/clip/blob/master/Interacting_with_CLIP.ipynb (Links to an external site.)

 (Links to an external site.)

https://analyticsindiamag.com/hands-on-guide-to-openais-clip-connecting-text-to-images/ (Links to an external site.)) 

 

 (Links to an external site.)

 

https://codelabs.developers.google.com/codelabs/keras-flowers-tpu?hl=en&continue=https%3A%2F%2Fcodelabs.developers.google.com%2F#6 (Links to an external site.)

https://codelabs.developers.google.com/codelabs/tensorflowjs-teachablemachine-codelab?hl=en&continue=https%3A%2F%2Fcodelabs.developers.google.com%2F#0 (Links to an external site.)

 

Pytorch lightning transfer learning pointers : https://wandb.ai/wandb/wandb-lightning/reports/Transfer-Learning-Using-PyTorch-Lightning--VmlldzoyODk2MjA (Links to an external site.)

https://albertvillanova.github.io/blog/2020/11/17/pytorch-lightning-transfer-learning.html (Links to an external site.)

pytorch transfer learning pointers : https://colab.sandbox.google.com/github/omerbsezer/Fast-Pytorch/blob/master/Learning_Pytorch/TransferLearning.ipynb (Links to an external site.)

more pointers 

: https://www.reddit.com/r/learnmachinelearning/comments/bm3hkp/fastpytorch_with_google_colab_pytorch_tutorial/ (Links to an external site.)

 

Extra points : If you do advanced transfer learning strategies. like domain adaptation etc.,.

d) EXTRA CREDIT :  Implement modern conv net squeezenet and xception in KERAS - Goal is to write complex cnn architectures using keras high level apis from scratch

Sample colab : https://codelabs.developers.google.com/codelabs/keras-flowers-squeezenet?hl=en&continue=https%3A%2F%2Fcodelabs.developers.google.com%2F#0 (Links to an external site.)

e) EXTRA CREDIT : Implement 3d convolution network based classification - in colab (pytorch and keras implementations) - Goal is to move beyond 2d to 3d

try to find good data sets and solutions - look for state of art results

Example : https://keras.io/examples/vision/3D_image_classification/    or (https://towardsdatascience.com/step-by-step-implementation-3d-convolutional-neural-network-in-keras-12efbdd7b130 and https://github.com/miki998/3d_convolution_neural_net_MNET/blob/master/3DkerasConv_example.ipynb) (Links to an external site.)

Pytorch example : https://towardsdatascience.com/pytorch-step-by-step-implementation-3d-convolution-neural-network-8bf38c70e8b3 code https://github.com/miki998/3d_convolution_neural_net_MNET/blob/master/3DpytorchConv_example.ipynb (Links to an external site.)

Extra points : 3d covid mask detector implementation from scratch - some motivating hints - https://medium.com/analytics-vidhya/building-a-covid19-mask-detector-with-opencv-keras-and-tensorflow-fc5e311071f9 (Links to an external site.) and https://github.com/fnandocontreras/mask-detector
