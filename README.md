# Gnana-Prasanna-Kumar-Turlapati_AI_For_Business_Portfolio

# Applied AI for Business Learning Portfolio - Hands-On Projects

# Applied AI Solutions for Business and Technology

# Gnana Prasanna Kumar Turlapati<br>

## Reflection<br>

### What you learned across all modules

Across these seven projects, I progressed from classical tabular machine learning to ensemble methods, dimensionality reduction, deep neural networks, and natural language processing. A foundational takeaway from the early modules was the importance of preventing data leakage through clean train-test splits and understanding why raw accuracy can be misleading on imbalanced datasets learning instead to rely on confusion matrices, precision-recall trade-offs, F1 scores, and ROC-AUC curves. Working with Support Vector Machines and Decision Trees showed me how feature scaling directly impacts linear convergence, how regularization and tree depth prevent overfitting, and how aggregating many weak learners into an ensemble improves generalization. In later modules, I saw how dimensionality reduction techniques like PCA and t-SNE affect compute time and accuracy differently depending on the downstream model, and how Multi-Layer Perceptrons and NLP embedding architectures in TensorFlow and Keras transform raw images and unstructured text into high-accuracy classifiers.

### Skills you developed (e.g., data preprocessing, model tuning, visualization)

**Data Preprocessing & Feature Engineering**: Built reproducible, leak-free pipelines using Scikit-Learn(Pipeline,ColumnTransformer,SimpleImputer,StandardScaler, OneHotEncoder) alongside custom transformers (FunctionTransformer) to engineer domain-specific tabular features. Normalized image pixel intensities applied PCA for variance-preserving compression, and built NLP text-cleaning pipelines using nltk, CountVectorizer, Keras Tokenizer, and pad_sequences.

**Model Training & Validation**: Trained and benchmarked a wide range of models from linear baselines (LinearRegression, SGDClassifier, LinearSVC) and kernelized SVMs (SVC) to tree-based ensembles (DecisionTreeRegressor, RandomForestClassifier, custom 1,000-tree bagging ensembles) and deep neural networks (Flatten, Dense, Embedding, and GlobalAveragePooling1D layers in Keras). Validated generalization rigorously using k-fold and stratified cross-validation (cross_val_score, cross_val_predict).

**Model & Hyperparameter Tuning**: Replaced guesswork with systematic optimization using GridSearchCV and RandomizedSearchCV across continuous distributions, calibrated classification decision thresholds to balance precision and recall targets, and implemented custom Keras callbacks (ExponentialLearningRate, EarlyStopping, ModelCheckpoint) to identify optimal learning rates and prevent overfitting.

**Visualization & Diagnostic Prototyping**: Used matplotlib, plot_tree, visualkeras, graphviz, and TensorBoard to inspect geographic price clusters, decision boundaries, precision-recall/ROC curves, t-SNE digit manifolds, network architectures, and live training loss curves, as well as ipywidgets to build an interactive spam detection inference interface.

### How these projects prepare you for real-world ML tasks

In production environments, machine learning rarely succeeds on algorithm selection alone, it depends on clean, reproducible data engineering and rigorous error analysis. Wrapping preprocessing and modeling steps inside standardized pipelines directly prevents train-serve skew, while evaluating models beyond accuracy prepares me to align threshold tuning with real business costs in skewed domains like fraud detection, spam filtering, and medical diagnostics. Furthermore, experiencing practical engineering tradeoffs such as diagnosing convergence bottlenecks, weighing white-box tree interpretability against ensemble accuracy, avoiding blind dimensionality reduction on tree models, and safeguarding neural network training with automated checkpoints equips me to build reliable, scalable, and well-validated ML systems from raw data to user-facing inference.

### AI Statement (Write a paragraph on how you used Generative AI for these projects)

Throughout these seven projects, I used Gemini as a collaborative learning and productivity assistant to support my workflow. Specifically, I utilized Gemini to clarify complex machine learning and evaluation concepts such as precision-recall trade-offs, confusion matrices, kernel hyperparameters, and neural network callbacks as well as to troubleshoot syntax, library compatibility issues, and boilerplate code for data visualizations and model evaluations. Gemini also assisted me in organizing and summarizing my technical notes across modules into clear documentation. All data preprocessing pipelines, model training experiments, hyperparameter tuning choices, and final analytical interpretations were executed, verified, and written independently by me to ensure a complete understanding of the material.

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
