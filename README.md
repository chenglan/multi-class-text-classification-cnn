### Project: Classify Kaggle Consumer Finance Complaints

### Summary:

 - This is a multi-class text classification problem.
 - The purpose of this project is to classify Kaggle Consumer Finance Complaints into 11 classes. 
 - The model was built with Convolutional Neural Network (CNN) and word embeddings on Tensorflow.

### Data: [Kaggle Consumer Finance Complaints](https://www.kaggle.com/cfpb/us-consumer-finance-complaints)

 - Input: consumer_complaint_narrative

 - Output: product

 - Example:
 
 ```
product: Credit reporting
consumer_complaint_narrative: "someone in north Carolina has stolen my identity information and has purchased items including XXXX cell phones thru XXXX on XXXX/XXXX/2015. A police report was filed as soon as I found out about it on XXXX/XXXX/2015. A investigation from XXXX is under way thru there fraud department and our local police department.\n"
 ```

### Train:

 - Command: ```python3 train.py```

### Predict:

 - Command: ```python3 predict.py trained_model_directory test_file```
 - Example: ```python3 predict.py ./trained_model_11123 ./data/small_samples.json```

### Reference
 - [Implement a cnn for text classification in tensorflow](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)
