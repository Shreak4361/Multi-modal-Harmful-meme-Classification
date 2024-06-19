This contains csv file for text datasets
This project was made for my participation in BrainDead (ML competition) as part of Revelation fest in IIEST,Shibpur.
This project aims to develop a multimodal deep learning  model  using datset containg 3500( images and text )memes. This  model capable of processing and classifying both text and image data. The model integrates information from both modalities to enhance classification accuracy.
•	Performed text preprocessing using nltk library and image preprocessing augmentation steps using TensorFlow's ‘ImageDataGenerator’
•	Model  architecture includes  Convolutional Neural Networks (CNNs) for image data and Embedding layers for text data, merging these two modalities  into a unified representation. 
•	The model is compiled using the Adam optimizer and Sparse Categorical Crossentropy loss function .
•	Model accuracy is 70% with softmax as activation function of output layer.
