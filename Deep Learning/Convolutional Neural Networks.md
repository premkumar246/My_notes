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

