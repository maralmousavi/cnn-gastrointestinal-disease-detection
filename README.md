# Gastrointestinal Disease Detection using Deep Convolutional Neural Network

Implementing Deep Convolutional Neural Network Algorithm for Automatic detection of Gastrointestinal Disease.<br/>

There is a dataset with 8000 labeled images (Ksavir) available <br/>
Gastrointestinal (GI) tract (colonoscopy): https://datasets.simula.no/kvasir/

### Dataset Details
The Kvasir dataset consists of images, annotated and verified by medical doctors (experienced endoscopists), including several classes showing anatomical landmarks, phatological findings or endoscopic procedures in the GI tract, i.e., hundreds of images for each class. The number of images is sufficient to be used for different tasks, e.g., image retrieval, machine learning, deep learning and transfer learning, etc. The anatomical landmarks include Z-line, pylorus, cecum, etc., while the pathological finding includes esophagitis, polyps, ulcerative colitis, etc. In addition, we provide several set of images related to removal of lesions, e.g., "dyed and lifted polyp", the "dyed resection margins", etc. The dataset consist of the images with different resolution from 720x576 up to 1920x1072 pixels and organized in a way where they are sorted in separate folders named accordingly to the content. Some of the included classes of images have a green picture in picture illustrating the position and configuration of the endoscope inside the bowel, by use of an electromagnetic imaging system (ScopeGuide, Olympus Europe) that may support the interpretation of the image. This type of information may be important for later investigations (thus included), but must be handled with care for the detection of the endoscopic findings.

### Acuracy Deep Convolutional Networks
![Graph](https://github.com/maralmousavi/cnn-gastrointestinal-disease-detection/blob/master/images/accuracy-CNN-algorithm.png)

### ROC-Curve
![Graph](https://github.com/maralmousavi/cnn-gastrointestinal-disease-detection/blob/master/images/ROC-Curve.png)
