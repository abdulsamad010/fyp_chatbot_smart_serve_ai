# SmartServeAI Chatbot

An intelligent AI-powered chatbot developed for the SmartServeAI platform to assist users in finding services, answering queries, and providing platform-related guidance through Natural Language Processing and Machine Learning.

## Overview

The SmartServeAI Chatbot is designed to understand user intentions and deliver relevant responses based on a custom-built dataset focused on service provider and service seeker interactions.

The project includes:

- Custom intent-based dataset development
- Data preprocessing and cleaning
- Machine Learning model training
- DistilBERT fine-tuning
- LSTM model experimentation
- Chatbot integration with the SmartServeAI application
- Model evaluation and performance improvement

## Features

- Intent classification using NLP techniques
- Service-related query handling
- Smart response generation
- Custom training dataset
- DistilBERT-based chatbot model
- LSTM-based chatbot experimentation
- Integrated chatbot deployment
- Scalable architecture for future enhancements

---

## Project Structure

```text
fyp_chatbot_smart_serve_ai/
│
├── chatbot/
│   ├── chatbot_models/
│   │   ├── chatbot_model.pkl
│   │   ├── vectorizer.pkl
│   │   └── readme.md
│   │
│   ├── DistilBERT3 (2).ipynb
│   ├── chatbot_code.ipynb
│   ├── final_model_integrated_in_app (1).ipynb
│   ├── lstm_of_final_model_for_app.ipynb
│   ├── ssai_integrated_model2.ipynb
│   ├── main.py
│   └── models/
│
├── dataset/
│   ├── SmartServeAI_final_dataset.json
│   ├── balanced_dataset_final.json
│   ├── dataset_improved_final.json
│   ├── smartserve_dataset_expanded.json
│   ├── smartserve_dataset_final.json
│   ├── smartserve_dataset_final_clean.json
│   └── other dataset versions
│
└── README.md
```

---

## Technologies Used

### Programming Language

- Python

### Libraries & Frameworks

- TensorFlow / Keras
- Scikit-learn
- Transformers (Hugging Face)
- DistilBERT
- Pandas
- NumPy
- NLTK

### Development Tools

- Jupyter Notebook
- Google Colab
- GitHub

---

## Dataset Development

The chatbot was trained using a custom dataset specifically created for the SmartServeAI platform.

The dataset contains:

- User intents
- Service-related queries
- Provider-related queries
- Account management queries
- Booking and hiring queries
- Complaint and support queries
- General platform assistance

Several dataset versions were created during development to improve intent balance, response quality, and model performance.

---

## Machine Learning Models

### Traditional NLP Model

A machine learning pipeline using:

- Text Vectorization
- Intent Classification
- Pickle-based model deployment

Files:

- `chatbot_model.pkl`
- `vectorizer.pkl`

### DistilBERT Model

Fine-tuned DistilBERT model for enhanced contextual understanding and intent recognition.

Notebook:

- `DistilBERT3 (2).ipynb`

### LSTM Model

LSTM-based deep learning model explored for sequence understanding and response prediction.

Notebook:

- `lstm_of_final_model_for_app.ipynb`

---

## Model Integration

The final chatbot model was integrated into the SmartServeAI application to provide real-time assistance to users.

Integration notebooks:

- `final_model_integrated_in_app (1).ipynb`
- `ssai_integrated_model2.ipynb`

---

## Research & Development Process

1. Dataset Collection
2. Data Cleaning
3. Intent Engineering
4. Dataset Expansion
5. Model Training
6. DistilBERT Fine-Tuning
7. LSTM Experimentation
8. Performance Evaluation
9. Application Integration
10. Final Testing and Deployment

---

## Future Improvements

- Multilingual support
- Voice-based interaction
- Generative AI integration
- Recommendation system integration
- Real-time service booking assistance
- Continuous learning pipeline

---

## Contributors

### Final Year Project (FYP)

**SmartServeAI: Intelligent Service Connection Platform**

- Abdul Samad
- Muhammad Huzaifa Yousaf
- Nauman Haroon

---

## License

This project was developed for academic and research purposes as part of a Final Year Project.
