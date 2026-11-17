# Final AI Application: Smart Tourism Question Classifier

## 1. Project Overview

The Smart Tourism AI Classifier is a beginner-friendly machine learning application that classifies tourism-related questions into five categories. It helps organize questions about tourist destinations in Pakistan.

## 2. Problem Statement

Tourists ask different types of questions about destinations, accommodation, routes, weather, and safety. This application automatically identifies the category of a tourism question using a machine learning model.

## 3. Method and Technologies

The application uses:

- Python
- Google Colab
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Multinomial Naive Bayes
- IPyWidgets for the interactive interface

The model converts text questions into numerical features using TF-IDF and predicts their categories using Multinomial Naive Bayes.

## 4. Question Categories

1. Attractions
2. Routes
3. Accommodation
4. Weather
5. Safety

## 5. Dataset and Evaluation

- Total sample questions: 100
- Training questions: 80
- Testing questions: 20
- Task 3 test accuracy: 90%

The 90% accuracy is from the existing evaluation on a 20-question test split. It is not a guarantee of real-world performance.

## 6. Application Demo

The application provides an interactive question input box and a classification button.

Example outputs:

| Input Question | Predicted Category |
|---|---|
| What is the weather in Murree? | Weather |
| Where can I find hotels in Hunza? | Accommodation |
| Is it safe to travel to Swat? | Safety |

The application also displays a confidence score and confidence level for each prediction.

## 7. Error Handling

The application checks for empty input and displays an error message when the user submits a blank question.

## 8. Limitations

- The dataset contains a limited number of sample questions.
- The model may incorrectly classify unfamiliar or ambiguous questions.
- Confidence scores are model estimates and do not guarantee prediction correctness.
- The application classifies questions only; it does not provide verified live tourism information.
- More diverse real-world data and further testing are needed to improve performance.

## 9. Ethics and Responsible AI

- Do not enter private or sensitive personal information.
- Predictions should not be treated as verified travel, weather, or safety advice.
- Users should independently verify important travel and safety information from reliable sources.
- The model may perform
