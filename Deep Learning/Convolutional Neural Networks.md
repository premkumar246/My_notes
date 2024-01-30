<h1 style="font-family:Consolas; font-size: 25px;"> Convolutional Neural Networks</h1>

### What is Convoltuional Neural Network?
- A Convolutional neural networks also known as convnet , or CNNs are a special kind of neural networks for processing data that has a known grid-like topology like time series data(1D) or image data(2d)Convolutional Neural Networks 
- A Convolutional Neural network is a special type of Neural network which is used to process grid like topology like 1D time series data or 2D image data. 
- A convolutional network has three layers 
    - 1.Convolutional Layer 
    - 2.Pooling Layer
    - 3.Fully connected Layer 
### Inspired by Human Visual Cortex
- A convolutional Layer performs an operation called convolution over the matrix of inputs. 
- The CNNs are inspired by Human Visual Cortex. 
- In 1998 Yann Lecun build first successful Neural network in AT&T then Microsoft build optical recognition and hand writing recognition tools 
### Why not ANNs? 
- We can use ANNs but the results are not satisfactory always 
#### High computation cost 
- To build a ANN to process the image data we need to build network with units equal to the image pixels and subsequently the rest of the layers. 
- Images has a lot of pixels and to process these pixels using ANNs needs alot of matrix operations making the ANN as highly cost incurring activity. 
#### Overfitting
- As we tend to build a ANNs we tend to learn every minute detail of a training data and learn every detail and gets overfited and cannot perform good operation on testing data 
#### Loss of imp info spatial arangement of pixels 
- As in ANNs we convert the 2D data into 1D data we loose the features spatial arrangements and distance between them and positions which is also an important feature to extract in image data. 

### How CNNs Works? 
![convolutional network image](https://editor.analyticsvidhya.com/uploads/59954intro%20to%20CNN.JPG)
- A Convolutional Neural networks has a convolutional and padding layers along with the fully connected dense layers as ANNs. 
- The convolutional layer performs convolution operation which is similar to a matrix element-wise multiplication this required to extract the boundaries or density change in the image data. 
- By performing the convolution operation the images turned in to a low resolution images with well differentiated edges in it. 
- To perform convolution we use filters, which are nothing but square matrices used for element wise multiplication. 
- There can be multiple filters and each filter act as a edge detector. 
- Once we get the data where edges as detected that data is passed to a pooling layer where features are again goes thorugh a certain process which we see in detail in Pooling topic. 
- Once the data is ready after the pooling stage we flatten the images in to 1D tensor and pass them to a fully connected layer where it try to learn the features and perform tasks like any ANN do. 


### Application 
- image classification 
- Object Localization 
- Object detection 
- Face recognition 
- Image segmentation 
- Super Resolution 
- Colorization 
- Pose detection 

### CNN Road map 
- CNN basics 
- Biological Connection 
- convolutional operation 
     - Padding + Stride
     - Pooling 
- CNN Architecture 
- CNN vs Ann 
- Dog vs Cat 
- Data Augmentation 
- Popular CNN Architecture 
   - Lenet  
   - Alexnet 
   - Vgg net 
   - Resnet 
   - Xceptional module 
- Transfer learning 

