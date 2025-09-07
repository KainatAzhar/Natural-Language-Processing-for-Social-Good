# NLP for Social Good: Toxic Comment Classification

### Project Overview
This project applies **Natural Language Processing (NLP)** and machine learning to address the critical issue of online toxicity and harassment. It develops a robust classification model capable of automatically identifying and flagging toxic comments on social media platforms. By providing an automated solution, this system can assist human moderators in creating a safer and more inclusive online environment.

### Dataset
The model is trained on a public dataset from the **Jigsaw Toxic Comment Classification Challenge** on Kaggle. This dataset contains a large number of social media comments with labels for various types of toxicity, including `toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, and `identity_hate`. This rich, real-world dataset makes the project highly relevant and impactful.

### Methodology
1.  **Data Preprocessing and Cleaning:** The raw text data is cleaned by removing punctuation, stop words, and special characters. The text is then tokenized and converted into a numerical format suitable for a neural network.
2.  **Model Architecture:** The project uses a Bidirectional Long Short-Term Memory (**Bi-LSTM**) network. This advanced recurrent neural network can process text sequentially, learning contextual relationships from both forward and backward directions, which is crucial for understanding the nuances of human language.
3.  **Training:** The Bi-LSTM model is trained to classify comments into one or more of the toxicity categories. The training process focuses on optimizing the model's ability to accurately identify toxic content while minimizing false positives.
4.  **Evaluation:** Model performance is evaluated using key metrics that are essential for imbalanced datasets, such as the **F1-score**, **Precision**, and **Recall**. These metrics provide a more comprehensive view of the model's effectiveness than simple accuracy alone.

### Concluded Results
The Bi-LSTM model successfully identifies different types of toxic comments with a high F1-score, showcasing its ability to handle a complex, multi-label classification problem. This project demonstrates proficiency in modern NLP techniques, ethical AI application, and the ability to build a practical system to combat a real-world social problem.

### Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- NLTK
- Jupyter Notebook
