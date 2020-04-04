# 100 Days Of ML Code

## Day 1 : March 30, 2020 _MNIST GAN_

**Today's Progress:**_ Today I worked on DCGAN (Deep Convolutional Generative Adversarial Network). Implemented on the MNIST handwritten digits dataset to generate Handwritten digits.

**Thoughts:** I will try DCGAN on slightly more complex datasets such as Fashion MNIST and CIFAR-10.

**Link of Work:** 
- [ipynb](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day1%20:%20MNIST%20GAN/mnist_gan.ipynb)

xdg![DCGAN](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day1%20:%20MNIST%20GAN/dcgan.gif)

**References**

- [DCGANs (Deep Convolutional Generative Adversarial Networks)](https://towardsdatascience.com/dcgans-deep-convolutional-generative-adversarial-networks-c7f392c2c8f8)
- [Deep Convolutional Generative Adversarial Network TensorFlow Core](https://www.tensorflow.org/tutorials/generative/dcgan)

## Day 2: March 31, 2020 _CIFAR-10_

**Today's Progress:** Built a network for CIFAR-10 dataset comprising Convolution, Max Pooling, Batch- Normalization and Dropout layers.
Studied about dropout and batch normalization in detail and various ways to avoid overfitting in a network.

**Thoughts:** Looking forward to tweak the model and obtain a better accuracy and reduce the number of parameters.

**Link of Work:**

- [ipynb](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day2%20:%20CIFAR-10/cifar10.ipynb)
- [test.py](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day2%20:%20CIFAR-10/test1.py)

**References**

- [Achieving 90% accuracy in Object Recognition Task on CIFAR-10 Dataset with Keras: Convolutional Neural Networks - Machine Learning in Action ](https://appliedmachinelearning.blog/2018/03/24/achieving-90-accuracy-in-object-recognition-task-on-cifar-10-dataset-with-keras-convolutional-neural-networks/)
- [CIFAR-10 Image Classification in TensorFlow - Towards Data Science ](https://towardsdatascience.com/cifar-10-image-classification-in-tensorflow-5b501f7dc77c)

## Day 3 : April 1, 2020 _Transfer Learning with InceptionV3_

**Today's Progress:** Today my goal was to get started with transfer learning and understand the architecture. I chose [InceptionV3](https://en.wikipedia.org/wiki/Inceptionv3) begin with. Started building the model by picking weights from Imagenet on Inception as the base model. Added a couple of dense layer with dropouts to complete the model.
The model was trained on 'Cats vs Dogs' dataset for 10 epochs with a training accuracy of 98.69%.

**Thoughts:** I am looking forward to implement the concept of Transfer Learning on a more project with a gain of accuracy.
Also I am excited to try out more architectures such as ResNet, VGG and AlexNet. 

**Link of Work:**
- [ipynb](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day3:%20Transfer%20Learning%20with%20InceptionV3/cats_vs_dogs_inceptionv3.ipynb)

**References**

- [Master Transfer learning by using Pre-trained Models in Deep Learning	](https://www.analyticsvidhya.com/blog/2017/06/transfer-learning-the-art-of-fine-tuning-a-pre-trained-model/)
- [tf.keras.applications.InceptionV3 TensorFlow Core v2.1.0](https://www.tensorflow.org/api_docs/python/tf/keras/applications/InceptionV3)

- [Using Inception-v3 from TensorFlow Hub for transfer learning ](https://medium.com/@utsumuki_neko/using-inception-v3-from-tensorflow-hub-for-transfer-learning-a931ff884526)

## Day 4 : April 2 , 2020 *Mask RCNN*

**Today's Progress:**  Today I tried to understand the idea behind Mask Region-based Convolution Neural Network better known as Mask RCNN. While going though the references I also learned the following things
- Object Localization
- Instance Segmentation
- Semantic Segmentation
- ROI Pooling

**References**

- [GitHub - matterport/Mask_RCNN: Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow](https://github.com/matterport/Mask_RCNN)
  
- [Mask R-CNN with OpenCV - PyImageSearch](https://www.pyimagesearch.com/2018/11/19/mask-r-cnn-with-opencv/)

- [Review: DeepMask (Instance Segmentation) - Towards Data Science](https://towardsdatascience.com/review-deepmask-instance-segmentation-30327a072339)

## Day 4 : April 3 , 2020 *Mask RCNN on Images*

**Today's Progress:** Today I implemented Mask RCNN on Images. I used Open CV as the platform to work. The model which I took for this task was trained on InceptionV2 on the COCO Dataset. 

**Thoughts:** I am planning to implement Mask-RCNN next on videos. I want to work on the challenges with the video and learn about video processing all together.

**Link of Work:** 
- [mask_rcnn.py](https://github.com/AvikantSrivastava/100-days-of-ML-Code/blob/master/Day4%20and%205%20:%20Mask%20RCNN/mask_rcnn.py)

**References**

- [Mask R-CNN with OpenCV - PyImageSearch](https://www.pyimagesearch.com/2018/11/19/mask-r-cnn-with-opencv/)

  
<!-- ## Day # : ########## *Dog Breed*

**References**
- https://medium.com/@claymason313/dog-breed-image-classification-1ef7dc1b1967
- https://medium.com/@utsumuki_neko/using-inception-v3-from-tensorflow-hub-for-transfer-learning-a931ff884526
- https://medium.com/tensorflow/introducing-tensorflow-datasets-c7f01f7e19f3
- https://towardsdatascience.com/dog-breed-classification-hands-on-approach-b5e4f88c333e
- https://www.tensorflow.org/api_docs/python/tf/keras/applications/InceptionV3
- https://github.com/novasush/Parallelization-with-TFDS/blob/master/TFDS_Parallel.ipynb -->

<!-- tools to edit markdown -->
<!-- http://tools.buzzstream.com/meta-tag-extractor -->
