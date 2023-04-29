# eye-diseases-image-recognition

# Eye Disease Classification

### **Context of the Problem**

The field of medical diagnosis has always been challenging due to the complexity and diversity of human diseases. With the rise of Artificial Intelligence techniques, it has become possible to automate and optimize the process of diagnosis by leveraging large amounts of medical data.

Regarding the field of ``ophthalmology``, early detection and accurate diagnosis of eye diseases are critical to ensuing timely treatment and preverting vision loss. However, distinguishing between these diseases can be a challenging task. Our goal is to develop a deep learning model that can accurately classify 3 eye diseases - cataracts, glaucoma and diabetic retinopathy - and a no-disease eye - normal eye - based on a dataset of aproximatelly 1000 images of human retinal for each class.

**Kaggle dataset:** https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

**Link to the prepared dataset:** https://drive.google.com/drive/folders/1HEti1Qv_-iXiOf2zp2amG8XFgk-HPuLj?usp=sharing

### **Notebooks**

**1. explore**
*   Explore the type of images there are in the dataset
*   Understand the composition of the dataset (landscape, vertical or squared images)
*   Splitting the train dataset into train and validation batches

**2. preprocess&modelhandrafted**
*   Data preprocessing
*   Create a Base Model
*   Iteretivevly improve the results of the Base Model
*   Execute common CNN architectures on our dataset
*   Compare the results and choose the models to Hypertune 

**3. model_hyper_search**
*   For each of our best models conduct a hyperpameter search 
*   Run the best models with the hyperparameters achieved 
*   Compare te results of the original models vs the hypertuned

**4. Transfer_learning**
*  Run ResNet50, ResNet101, ResNet152, VGG16 and VGG19 with Transfer Learning
*  Compare the results with the handcrafted models and our best model from the previous notebooks
* Conclusion on the benefits of Transfer Learning
