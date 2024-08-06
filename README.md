# Using-the-SQuAD-dataset-for-Question-and-Answers
# Question-Answering (Q&A) System using Deep Learning

## Objective
To create a Q&A system that accurately answers questions based on given contexts using a pre-trained deep learning model.

## Model Selection
Utilized the **DistilBERT** model from the Hugging Face Transformers library for its efficiency and effectiveness in understanding natural language.

## Data Preparation
- Loaded SQuAD-style datasets for training and testing.
- Developed a function (`create_squad_dict`) to preprocess and structure the dataset into a usable format.

## Tokenization
Implemented tokenization of input questions and contexts using the DistilBERT tokenizer, ensuring compatibility with the model.

## Model Training
- Configured training parameters using `TrainingArguments`, including learning rate, batch size, and evaluation strategy.
- Trained the model with the `Trainer` class, employing a training loop that includes loss calculation and optimization.

## Prediction Generation
Created a function to generate predictions from the model for a set of question-context pairs, comparing model outputs with true answers.

## Evaluation Metrics
- Computed the F1 score to evaluate the model's performance, achieving an average F1 score of approximately 0.67, indicating a reasonable level of accuracy.

## Outcome
Successfully developed a functional Q&A system that demonstrates the capability to understand context and provide accurate answers based on the trained model.

## Tools and Libraries
- **Transformers**
- **Pandas**
- **Torch**
- **Datasets**


