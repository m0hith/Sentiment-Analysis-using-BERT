# Sentiment-Analysis-using-BERT
### Sentiment analysis model using the BERT (Bidirectional Encoder Representations from Transformers) model used to parse movie reviews and classify their sentiment (according to whether they are positive or negative)

- Work done as part of **ECE-GY 7123: Deep Learning** course offered by Department of ECE, NYU Tandon School of Engineering.
- Independently developed a sentiment analysis model using the BERT algorithm, which achieved an accuracy rate of 92% on a public IMDB Movie Reviews dataset.

- Conducted the data preprocessing by encoding text into vector-style representations using tokenization, and also maintaining consistent case-sensitivity. 

- Fine-tuned the BERT algorithm for sentiment analysis by appending a bidirectional GRU with 2 layers, 256 hidden dimensions, and dropout = 0.25 to perform the classification.

- Trained the modified resnet architecture using Binary Cross Entropy loss function, and Adam optimizer.

- Conducted an extensive analysis of the model's performance, including evaluating the model's accuracy, epoch wise loss reports, and running times.

- Documented the entire project, including the data preprocessing, fine-tuning process, evaluation metrics, and model deployment, ensuring easy replication by others and future reference.

### Dataset:
Large Movie Review Dataset. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for test validation as well.
