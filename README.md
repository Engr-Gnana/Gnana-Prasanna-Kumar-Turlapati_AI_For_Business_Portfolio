# Applied AI Solutions for Business and Technology<br>

**Gnana Prasanna Kumar Turlapati**<br>

## Reflection<br>

### What you learned across all modules

Across these seven projects, I progressed from classical tabular machine learning to ensemble methods, dimensionality reduction, deep neural networks, and natural language processing. A foundational takeaway from the early modules was the importance of preventing data leakage through clean train-test splits and understanding why raw accuracy can be misleading on imbalanced datasets learning instead to rely on confusion matrices, precision-recall trade-offs, F1 scores, and ROC-AUC curves. Working with Support Vector Machines and Decision Trees showed me how feature scaling directly impacts linear convergence, how regularization and tree depth prevent overfitting, and how aggregating many weak learners into an ensemble improves generalization. In later modules, I saw how dimensionality reduction techniques like PCA and t-SNE affect compute time and accuracy differently depending on the downstream model, and how Multi-Layer Perceptrons and NLP embedding architectures in TensorFlow and Keras transform raw images and unstructured text into high-accuracy classifiers.

### Skills you developed

**Data Preprocessing & Feature Engineering**: I learned how to build clean, leak-free preprocessing pipelines using Scikit-Learn (Pipeline, ColumnTransformer, SimpleImputer, OneHotEncoder, and StandardScaler) to handle missing values, encode categorical features, and standardize numerical scales. For unstructured data, I normalized image pixel arrays for neural networks and built custom text-cleaning pipelines using Python, nltk, CountVectorizer, and Keras Tokenizer with sequence padding to prepare raw SMS text for NLP modeling.

**Model Tuning & Evaluation**: I progressed from training baseline models (LinearRegression, SGDClassifier, LinearSVC) to optimizing complex ensembles (RandomForestClassifier) and neural networks in TensorFlow/Keras. I systematically tuned hyperparameters using GridSearchCV and RandomizedSearchCV, implemented custom learning-rate sweeps and EarlyStopping callbacks, and calibrated classification decision thresholds to balance precision, recall, F1-scores, and ROC-AUC on imbalanced datasets.

**Data & Diagnostic Visualization**: I used matplotlib and TensorBoard not just to explore raw datasets such as plotting geographic housing distributions, digit grids, and high-dimensional t-SNE clusters—but also to diagnose model behavior. I created Precision-Recall and ROC curves, decision-boundary contours, confusion matrices, and real-time training/validation loss curves to catch overfitting and visually explain model performance.

### How these projects prepare you for real-world ML tasks

In production environments, machine learning rarely succeeds on algorithm selection alone, it depends on clean, reproducible data engineering and rigorous error analysis. Wrapping preprocessing and modeling steps inside standardized pipelines directly prevents train-serve skew, while evaluating models beyond accuracy prepares me to align threshold tuning with real business costs in skewed domains like fraud detection, spam filtering, and medical diagnostics. Furthermore, experiencing practical engineering tradeoffs such as diagnosing convergence bottlenecks, weighing white-box tree interpretability against ensemble accuracy, avoiding blind dimensionality reduction on tree models, and safeguarding neural network training with automated checkpoints equips me to build reliable, scalable, and well-validated ML systems from raw data to user-facing inference.

### AI Statement

I used Generative AI as a collaborative learning and productivity aid across my seven machine learning and deep learning projects covering machine learning review, classification, support vector machines, decision trees, dimensionality reduction, artificial neural networks, and natural language processing. Specifically, I used it to clarify theoretical concepts like precision-recall trade-offs, kernel trick hyperparameters, and dimensionality reduction, debug Python code across Scikit-Learn, TensorFlow/Keras, and NLTK, troubleshoot library compatibility issues such as patching visualkeras for Keras 3, and refine the structure and clarity of my written reflections and explanations.

## Projects completed in this course:<br>

Project 1 Chapter 1: Machine Learning Review<br>
Project 2 Chapter 3: Classification<br>
Project 3 Chapter 5: Support Vector Machines<br>
Project 4 Chapter 6: Decision Trees<br>
Project 5 Chapter 8: Dimensionality Reduction<br>
Project 6 Chapter 10: Artificial Neural Networks<br>
Project 7 Chapter 16: Natural Language Processing<br>

## Link to the Project Notebooks:<br>
https://drive.google.com/drive/folders/1fblgu54raFFWgae3kz32BJl_cEOzG1Zh?usp=drive_link
