## Jira Query Predictor with Vector Database

### Overview
This project leverages machine learning to predict Jira queries by utilizing solutions stored in a DVector database. The model is designed to enhance issue tracking and management by providing intelligent query suggestions based on historical data.

### Features
- **Predictive Modeling**: Uses advanced algorithms to predict Jira queries.
- **Vector Database Integration**: Efficiently retrieves and utilizes solution data stored in DVector for accurate predictions.
- **Automated Query Suggestions**: Enhances productivity by automating the query suggestion process.
- **Scalable and Adaptable**: Easily integrates with existing Jira setups and can be scaled to handle large datasets.

### Tech Stack
- **BERT Embeddings**: For transforming text data into meaningful vector representations.
- **Vector Database-FAISS**: To store and manage solution vectors.
- **Python**: Main programming language for model development and integration.
- **TensorFlow/PyTorch**: For building and training the machine learning models.
- **Flask/FastAPI**: For creating a web API to serve the model predictions.

### Getting Started
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/jiraModelCreation.git
    cd jiraModelCreation
    ```
2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Configure Database**:
    - Ensure your DVector database is set up and accessible.
    - Update the database configuration in `config.py`.

4. **Run the Model**:
    ```bash
    python model.py
    ```
### Colab Notebook
To make it easier to get started, we have provided a Google Colab notebook where you can run the model and see it in action without needing to set up a local environment. [Click here to open the Colab notebook](https://colab.research.google.com/drive/1DU9cZpYkXN9AzJJXt5pxI9VIxbv3Rdke?usp=sharing).
