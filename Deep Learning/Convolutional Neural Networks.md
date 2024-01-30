<h1 style="font-family:Consolas; font-size: 25px;"> Convolutional Neural Networks</h1>

## Introduction to Convolutional Neural Networks
### What is Convoltuional Neural Network?
- Convolutional Neural Networks (CNNs or ConvNets) are a class of deep neural networks that are particularly well-suited for tasks involving visual data, such as image and video recognition. 
- CNNs have proven to be highly effective in computer vision tasks, outperforming traditional methods in various applications. 
- The architecture of CNNs is inspired by the visual processing that occurs in the human brain.

#### Key characteristics of Convolutional Neural Networks:

1. **Convolutional Layers:**
   - CNNs use convolutional layers to automatically and adaptively learn spatial hierarchies of features from input data.
   - Convolution involves applying filters (kernels) to small overlapping regions of the input data to extract local features.
   - These filters slide or convolve across the input, capturing patterns such as edges, textures, and shapes.

2. **Pooling Layers:**
   - Pooling layers downsample the spatial dimensions of the input, reducing computational complexity and the number of parameters.
   - Common pooling operations include max pooling (selecting the maximum value in a region) and average pooling (calculating the average value).

3. **Activation Functions:**
   - Activation functions, such as Rectified Linear Unit (ReLU), are applied after convolution and pooling layers to introduce non-linearity into the network.
   - Non-linearity is essential for enabling the network to learn complex patterns and relationships in the data.

4. **Fully Connected Layers:**
   - Following convolutional and pooling layers, CNNs often have one or more fully connected layers.
   - These layers combine the learned features to make final predictions or classifications.

5. **Hierarchical Feature Learning:**
   - CNNs learn hierarchical representations of features, starting with low-level features like edges and gradually progressing to more complex and abstract features.

6. **Parameter Sharing:**
   - The use of shared weights in convolutional layers allows the network to learn a set of filters that can be applied across the entire input.
   - Parameter sharing reduces the number of parameters in the model, making it more efficient and capable of generalizing to new data.

7. **Spatial Invariance:**
   - CNNs exhibit spatial invariance, meaning they can recognize patterns regardless of their position in the input space.
   - This property is beneficial for tasks like object recognition where the position of an object in an image may vary.

8. **Transfer Learning:**
   - CNNs can leverage pre-trained models on large datasets for specific tasks (e.g., ImageNet), allowing for transfer learning to new tasks with smaller datasets.


### Inspired by Human Visual Cortex
- A convolutional Layer performs an operation called convolution over the matrix of inputs. 
- The CNNs are inspired by Human Visual Cortex. 
- In 1998 Yann Lecun build first successful Neural network in AT&T then Microsoft build optical recognition and hand writing recognition tools.

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

- Computer vision is a field of artificial intelligence (AI) that enables machines to interpret and understand visual information from the world. 
- It involves the development of algorithms and systems that can analyze and make decisions based on visual data. 
- The applications of computer vision are diverse and span across various industries. Here are some notable applications:

1. **Image and Video Recognition:**
   - **Object Recognition:** Identifying and classifying objects within images or video streams.
   - **Facial Recognition:** Recognizing and verifying individuals based on facial features.
   - **Gesture Recognition:** Interpreting human gestures for human-computer interaction.

2. **Medical Imaging:**
   - **Diagnostic Imaging:** Assisting in medical diagnosis through the analysis of images from X-rays, MRIs, CT scans, and other medical imaging modalities.
   - **Pathology Analysis:** Automated analysis of pathology slides for detecting abnormalities or diseases.

3. **Autonomous Vehicles:**
   - **Object Detection:** Identifying and tracking objects in the surroundings for navigation and collision avoidance.
   - **Lane Detection:** Recognizing road lanes to assist in autonomous driving.

4. **Robotics:**
   - **Object Manipulation:** Enabling robots to identify and manipulate objects in their environment.
   - **Navigation:** Providing robots with the ability to navigate through environments using visual data.

5. **Augmented Reality (AR) and Virtual Reality (VR):**
   - **AR Applications:** Overlaying digital information onto the real-world view, enhancing user experiences.
   - **VR Simulations:** Creating realistic virtual environments for immersive experiences.

6. **Security and Surveillance:**
   - **Intrusion Detection:** Monitoring areas for unauthorized access or suspicious activities.
   - **Anomaly Detection:** Identifying unusual patterns or behaviors in surveillance footage.

7. **Retail:**
   - **Object Recognition for Inventory Management:** Automating inventory tracking and management in retail stores.
   - **Customer Analytics:** Analyzing customer behavior for personalized marketing and improved store layouts.

8. **Agriculture:**
   - **Crop Monitoring:** Analyzing satellite or drone imagery to monitor crop health and yield predictions.
   - **Weed Detection:** Identifying and managing weed infestations in fields.

9. **Entertainment:**
   - **Content Recommendation:** Analyzing user preferences and behavior for personalized content recommendations.
   - **Video Game Development:** Implementing realistic graphics and character animations.

10. **Document Analysis:**
    - **Optical Character Recognition (OCR):** Extracting text from images or scanned documents.
    - **Document Classification:** Categorizing and organizing documents based on content.

11. **Industrial Quality Control:**
    - **Defect Detection:** Identifying defects or irregularities in manufactured products.
    - **Quality Assurance:** Ensuring the quality of products through visual inspection.

12. **Environmental Monitoring:**
    - **Wildlife Monitoring:** Tracking and monitoring wildlife populations using camera traps.
    - **Climate and Weather Analysis:** Analyzing satellite imagery for weather prediction and environmental monitoring.


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

## History behind the Evolution of CNNs

- Resources : <a href='https://www.youtube.com/watch?v=IOHayh06LJ4'>Hubel and Wiesel's Cat Experiments video (1959-1968)</a>
    - 
