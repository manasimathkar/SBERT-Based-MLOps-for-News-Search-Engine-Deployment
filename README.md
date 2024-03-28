# SBERT Based MLOps for News Search Engine Deployment

## Aim
<br><br>
This project aims to improve the search experience for news articles by leveraging the
Sentence-BERT (SBERT) model and the ANNOY approximate nearest neighbor library.
The project will be deployed on AWS using Docker containers and exposed as a Flask
API, allowing users to query and retrieve relevant news articles easily.
<br><br>
## Methodology
<br>Data Preprocessing:<br>
Clean and preprocess the news article dataset, including tokenization,
removal of stop words, and normalization.<br>
<br>SBERT Training:<br>
Train the Sentence-BERT (SBERT) model using the preprocessed news
articles to generate semantically meaningful sentence embeddings.<br>
<br>ANNOY Indexing:<br>
Utilize the ANNOY library to create an index of the SBERT embeddings,
enabling fast and efficient approximate nearest neighbor search.<br>
<br>Deployment on AWS with Docker:<br>
Containerize the project components, including the Flask API, SBERT
model, and ANNOY index, using Docker. Then deploy the Docker containers on AWS EC2 Instance.
<br><br>

