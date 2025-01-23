# Mental Health Chatbot

## Overview
This repository contains the implementation of a Mental Health Chatbot, leveraging machine learning and natural language processing to provide supportive and contextually relevant responses to user queries about mental health and happiness.

The chatbot is powered by three different approaches:
1. **Rule-Based Chatbot**
2. **Retrieval-Based Chatbot**
3. **Generative-Based Chatbot**

Each implementation is provided in the respective `.ipynb` files uploaded in this repository.

---

## Dataset

The dataset used for this project, `happiness.csv`, was meticulously curated from the book *Happiness Unlimited: Awakening With Brahmakumaris* by BK Shivani and Suresh Oberoi. The content focuses on principles of happiness and well-being, with structured question-and-answer data:

- **Questions:** Contain user inquiries about happiness and mental health.
- **Answers:** Provide contextually relevant responses inspired by the teachings of Brahmakumaris.

### Key Features:
- **Original Dataset Creation:** The dataset was created by extracting and formatting content from the book, ensuring structured and meaningful data for training.

---

## Preprocessing

To prepare the data for training, a robust preprocessing pipeline was implemented:

1. **Tokenization:** Breaking down text into smaller units (words or subwords).
2. **Vectorization:** Converting text data into numerical representations using techniques like Count Vectorizer and TF-IDF (Term Frequency-Inverse Document Frequency).
3. **Padding/Truncation:** Ensuring consistent sequence lengths for deep learning models.

These preprocessing steps ensured that the input data was clean, uniform, and suitable for training robust machine learning models.

---

## Implementations

### 1. Rule-Based Chatbot
- Utilizes predefined rules and patterns to generate responses.
- Suitable for straightforward and specific queries.

### 2. Retrieval-Based Chatbot
- Fetches the most relevant response from a predefined dataset using similarity measures.
- Ensures accurate and contextually appropriate answers.

### 3. Generative-Based Chatbot
- Employs a deep learning model (e.g., LSTM) to generate responses.
- Can produce more dynamic and creative answers compared to other methods.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mental-health-chatbot.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the respective Jupyter Notebook files:
   - Rule-Based Chatbot: `Rule_based.ipynb`
   - Retrieval-Based Chatbot: `Retrieval_based.ipynb`
   - Generative-Based Chatbot: `Generative_based1.ipynb`

4. Execute the cells in the notebook to train and interact with the chatbot.

---

## Applications
- Mental health support
- Providing insights on happiness and well-being
- Educational tools for understanding the principles of happiness
