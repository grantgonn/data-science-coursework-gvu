# Grand View University - Data Science & Analytics Coursework

Repository containing all coursework, assignments, homework, exams, and projects from my **Bachelor's in Computer & Data Science** and **Master's in Analytics (Machine Learning focus)** at Grand View University.

**Purpose**: Personal knowledge archive and reference for techniques, code patterns, and projects.

---

## 📁 Repository Structure
- Each folder represents one course
- Contains Jupyter notebooks (`.ipynb`) and Python scripts (`.py`)
- **Highlighted final projects** are extracted into separate polished public repositories (see links below)

### Highlighted Polished Project Repos
- **[Telecom Customer Churn with NLP](https://github.com/GrantGonnerman/telecom-customer-churn-nlp)**
- **[Kaggle Optimal Fertilizer Prediction](https://github.com/GrantGonnerman/kaggle-optimal-fertilizer-prediction)**
- **[Lung Cancer CNN Classification](https://github.com/GrantGonnerman/lung-cancer-cnn-classification)**

---

## Coursework by Class

### **DATA-448 Predictive Analytics**
**Key Topics**: Predictive modeling, feature engineering, ensemble methods, hyperparameter tuning, imbalanced data handling.

**DATA_448_Exam_1**: Midterm Exam – Comprehensive predictive modeling assessment. Performed full EDA, feature engineering (including scaling and encoding), built and compared multiple classification models (Logistic Regression, Decision Tree, Random Forest, AdaBoost), and evaluated performance using ROC-AUC, precision-recall, and classification reports on a provided dataset.
**DATA_448_Exam_2**: Final Exam – End-of-course predictive analytics assessment. Conducted advanced modeling including feature engineering, hyperparameter tuning, model comparison (tree-based ensembles), and business-oriented evaluation (probability cutoffs and cost-sensitive analysis) on a new dataset.

**HW1**: Retail Fraud Detection – Built and compared Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting models on transaction data pulled from S3. Engineered rate-based features and used MinMax scaling to identify fraudulent cashier behavior.
**HW2**: Wholesale Customer Channel Classification – Predicted customer segment (Channel) using spending data across Fresh, Milk, Grocery, etc. Compared Logistic Regression, Random Forest, AdaBoost, and SVM models with multi-class strategies and ROC evaluation.
**HW3**: Manufacturing Product Failure Prediction – Predicted product failures using material attributes and 18 measurement variables. Applied KNN and Simple imputation for missing data and built ensemble models (Random Forest, AdaBoost) with focus on recall and ROC-AUC.
**HW4**: Retail Cashier Fraud Detection – Continued feature engineering and model comparison on transaction data from S3. Trained and evaluated Logistic Regression, Decision Tree, Random Forest, and AdaBoost models, focusing on recall and classification performance for fraud identification.
**HW5**: Advanced Feature Engineering & Selection for Fraud Detection – Applied Box-Cox transformations, created multiple interaction terms and heredity features, plus decision-tree-based features. Performed extensive Recursive Feature Elimination (RFE) with Logistic Regression, Random Forest, and AdaBoost over 100 iterations to identify the most stable predictive features.
**HW6**: Hyperparameter Tuning & Cost-Sensitive Fraud Modeling – Implemented GridSearchCV with custom cost-sensitive scoring on Random Forest models (using XGBoost/Optuna setup). Optimized models with interaction and engineered features, determined optimal probability cutoffs via a business cost function to minimize expensive false negatives in fraud detection.

**inclass01**: Telecom Customer Churn Prediction – Loaded telecom churn data from S3, performed basic EDA (class distribution), and built a Random Forest model for binary churn classification. Evaluated performance using ROC curve and probability thresholds.
**inclass02**: Telecom Churn with Random Oversampling – Applied RandomOverSampler to address class imbalance on telecom churn data. Built and compared Random Forest and AdaBoost models on oversampled data, evaluated with classification reports focusing on recall for the minority churn class.
**inclass03**: Telecom Churn with SMOTE – Implemented SMOTE for synthetic oversampling on imbalanced telecom churn dataset. Trained Random Forest and AdaBoost models on balanced data and compared performance using classification reports and optimal cutoff selection via Euclidean distance on ROC curve.
**inclass04**: Iris Species Classification (One-vs-Rest) – Built multi-class classifiers on the Iris dataset using OneVsRest strategy. Compared Random Forest and SVM models with MinMax scaling, evaluated using confusion matrices and classification reports.
**inclass05**: Iris Species Classification (One-vs-One) – Implemented OneVsOne strategy for multi-class Iris classification. Compared Logistic Regression and Decision Tree models (with scaling), evaluated performance, and selected the best model based on accuracy and per-class metrics.
**inclass06**: Framingham Heart Disease Risk Prediction – Loaded Framingham heart study data from S3. Performed EDA and built baseline classification models (Logistic Regression, Decision Tree, Random Forest, AdaBoost) to predict 10-year CHD risk using selected features (age, smoking status, cholesterol, BMI, heart rate).
**inclass07**: Framingham Heart Disease with Imputation – Continued Framingham CHD prediction. Applied SimpleImputer and KNNImputer for missing values, trained multiple models (including ensembles), and evaluated performance with focus on recall and classification metrics.
**inclass08**: Employee Turnover Prediction (HR Analytics) – Loaded employee turnover dataset from S3. Conducted initial EDA, created dummy variables for categorical features (department and salary), and prepared data for predictive modeling of employee attrition.
**inclass09**: Employee Turnover with Feature Engineering – Built on turnover dataset with one-hot encoding of categorical variables. Applied Box-Cox transformations and further prepared features for modeling, including custom precision-recall cutoff functions.
**inclass10**: Employee Turnover Model Evaluation & Visualization – Continued turnover prediction project. Trained classification models (including Decision Tree with visualization via plot_tree), evaluated performance, and explored model interpretability on the HR analytics dataset.
**inclass11**: Employee Turnover (HR Analytics) – Continued work on the turnover dataset with one-hot encoding of categorical variables (sales and salary). Prepared data for modeling and began evaluating classification performance.
**inclass12**: Employee Turnover Feature Selection – Applied Recursive Feature Elimination (RFE) on the turnover dataset to identify the most important predictors of employee attrition using models like Logistic Regression and Random Forest.
**inclass13**: Employee Turnover with RFE & Model Comparison – Further feature selection using RFE/RFECV on the HR turnover data. Trained and compared multiple models (Logistic Regression, Random Forest, AdaBoost) on the reduced feature set.
**inclass14**: Employee Turnover Hyperparameter Tuning – Implemented GridSearchCV for hyperparameter optimization on classification models (including Random Forest and AdaBoost) for the employee turnover prediction task.
**inclass15**: Employee Turnover Final Model Evaluation – Final evaluation and interpretation of the best turnover prediction model. Focused on performance metrics, probability cutoffs, and business insights for reducing employee attrition.
**inclass16**: Employee Turnover (HR Analytics) – Continued employee attrition prediction project. Performed one-hot encoding on categorical variables (sales and salary), trained classification models, and evaluated performance on the turnover dataset.
**inclass17**: Employee Turnover with Optuna Hyperparameter Tuning – Installed and used Optuna for hyperparameter optimization on the employee turnover dataset. Loaded train/validation/test splits and prepared data for advanced model tuning (XGBoost/RF/AdaBoost).
**inclass18**: Employee Turnover with XGBoost – Installed XGBoost and applied it to the employee turnover prediction task. Built and evaluated XGBoost models alongside other ensembles, focusing on classification metrics and business cost functions for attrition.
**inclass19**: Insurance Charges Regression – Shifted to a regression task using the insurance dataset. Performed feature engineering (one-hot encoding for region, binary encoding for sex/smoker, interaction terms), and prepared data for predictive modeling of medical charges using tree-based regressors (Random Forest / XGBoost).

---

### **DATA-455 Applied Stats & Machine Learning**
**Key Topics**: Statistical modeling, regression, classification, clustering, neural networks.

**Exam1**: Midterm Exam – Applied Statistics & Machine Learning. Performed exploratory data analysis, statistical testing, data preprocessing, and built multiple supervised learning models (including regression and classification) with evaluation using cross-validation and performance metrics.
**Exam2**: Final Exam – Applied Statistics & Machine Learning. Comprehensive final assessment covering advanced statistical concepts, machine learning pipelines, model diagnostics, feature importance analysis, and final model selection/evaluation on a new dataset.

**HW1: Real Estate Price Prediction – Built a Linear Regression model to predict house price per unit area using features like house age, distance to MRT, number of convenience stores, and location coordinates. Loaded data from S3, performed feature selection, and evaluated using Mean Squared Error (MSE).
**HW2: Framingham Heart Disease Risk Prediction (5-Fold CV) – Compared two Logistic Regression models on the Framingham dataset using 5-fold cross-validation. Applied MinMax scaling and custom probability threshold (0.25) to optimize F1-score for predicting 10-year CHD risk. Model 1 (more features) outperformed Model 2.
**HW3**: Car Price Prediction with Regularization – Performed regression analysis on car pricing data. Compared Ordinary Least Squares, Ridge, and Lasso models (including cross-validated versions) to predict car price while addressing high-dimensionality and overfitting concerns.
**HW4**: Framingham Heart Disease Prediction with SVM & Neural Networks – Explored Support Vector Classifier (SVC) and basic TensorFlow Neural Network approaches on the Framingham dataset for binary CHD prediction. Included data cleaning, scaling, and model training with accuracy tracking.
**HW5**: Framingham Heart Disease Feature Importance – Loaded Framingham dataset from S3, performed data cleaning (drop NA), and used Random Forest (100 iterations) to calculate and rank average feature importance for predicting 10-year CHD risk. Identified sysBP, BMI, age, totChol, and glucose as the top predictors.
**HW6**: Ensemble Methods Comparison (Random Forest, AdaBoost, Gradient Boosting) – Built and compared Random Forest, AdaBoost, and Gradient Boosting models on the Framingham dataset using a low probability threshold (0.1) to maximize recall. Evaluated average recall and accuracy over 100 train-test splits; discussed hyperparameter tuning to improve accuracy while maintaining high recall.
**HW7**: Mall Customer Segmentation with K-Means – Performed customer segmentation on the Mall Customers dataset using K-Means clustering. Applied MinMax scaling on selected features (Gender, Age, Annual Income), evaluated different numbers of clusters (2–10) using Silhouette, Calinski-Harabasz, and Davies-Bouldin scores.

**inclass01**: Real Estate Price Prediction – Loaded Real Estate dataset from S3, performed basic EDA (histograms, summary statistics), dropped irrelevant columns, and prepared data for linear regression modeling of house price per unit area.
**inclass02**: Framingham Heart Disease EDA – Loaded Framingham heart study dataset from S3. Performed initial exploratory data analysis including summary statistics and data inspection for 10-year CHD risk prediction.
**inclass03**: Framingham Heart Disease Summary Statistics – Continued Framingham dataset analysis. Generated detailed descriptive statistics (mean, std, min, max, quartiles) across all variables to understand data distribution and missing values.
**inclass04**: Real Estate Linear Regression – Built and evaluated a Linear Regression model on the Real Estate dataset. Split data into train/test sets, trained the model, and generated predictions for house prices using features like house age, MRT distance, and convenience stores.
**inclass05**: Framingham Heart Disease Logistic Regression – Built a baseline Logistic Regression model on the Framingham dataset (after dropping NA values). Used selected features (age, smoking, cholesterol, BMI, heart rate) to predict 10-year CHD risk and evaluated with confusion matrix and accuracy.
**inclass06**: Car Price Prediction (Model Comparison) – Loaded CarPrice dataset from S3 and built two Linear Regression models with different feature sets (Model 1: wheelbase/horsepower/etc.; Model 2: carwidth/carheight/etc.). Evaluated performance using train-test split and Mean Squared Error (MSE).
**inclass07**: Car Price Prediction with Leave-One-Out Cross-Validation – Continued Car Price regression task. Implemented Leave-One-Out Cross-Validation (LOOCV) on two different Linear Regression models and compared their MSE to determine the better performing feature set.
**inclass08**: Car Price Prediction with K-Fold Cross-Validation – Built and evaluated two Linear Regression models on the CarPrice dataset using 3-Fold Cross-Validation. Compared average MSE across folds and selected the superior model based on validation performance.
**inclass09**: Car Price Regularization (Ridge & Lasso) – Applied Ridge and Lasso regression (with CV for hyperparameter tuning) on the CarPrice dataset. Compared regularized models against ordinary linear regression to address multicollinearity and improve generalization.
**inclass11**: Car Price Prediction with Neural Networks – Built a basic TensorFlow/Keras neural network regressor on the CarPrice dataset. Applied MinMax scaling to features and trained the model to predict vehicle prices.
**inclass12**: Car Price Prediction with Support Vector Regression (SVR) – Loaded CarPrice dataset from S3. Built and compared two SVR models (RBF and Polynomial kernels) with MinMax scaling on selected features (wheelbase, enginesize, etc.). Evaluated using Mean Squared Error (MSE); selected the polynomial kernel model as the best performer.
**inclass13**: Framingham Heart Disease Prediction (Logistic vs Random Forest) – Built Logistic Regression and Random Forest models on the Framingham dataset (after dropping NA). Used a low probability threshold (0.1) to maximize recall for 10-year CHD risk prediction. Random Forest achieved higher recall.
**inclass14**: Framingham Heart Disease with Lasso Feature Selection – Applied LassoCV for feature selection on the Framingham dataset. Used selected features to build a Logistic Regression model with a 0.1 probability threshold, focusing on recall for CHD prediction.
**inclass15**: Framingham Heart Disease with AdaBoost & Random Forest – Built AdaBoost (with Decision Tree base estimator) and Random Forest models on the Framingham dataset. Compared recall at a low probability threshold (0.1); preferred AdaBoost for higher recall in predicting CHD risk.
**inclass16**: Framingham Heart Disease with Gradient Boosting – Built AdaBoost and Gradient Boosting models on the Framingham dataset. Evaluated recall at a low threshold (0.1); selected Gradient Boosting as the best performing model for CHD risk prediction.
**inclass17**: Customer Offers Segmentation – Loaded customer purchase offers dataset from S3. Performed data exploration and built multiple ensemble models (Decision Tree, Random Forest, AdaBoost, Gradient Boosting) for customer classification/prediction tasks.
**inclass18**: Customer Clustering with K-Means – Loaded customer visit and expense data from S3. Applied MinMax scaling followed by K-Means clustering to segment customers based on visit time, average expense, sex, and age.
**inclass19**: Fuzzy C-Means Clustering – Installed scikit-fuzzy and applied Fuzzy C-Means clustering on the customer dataset (after scaling). Compared soft clustering results against traditional K-Means for customer segmentation.
**inclass20**: Spectral Clustering on Circle Data – Loaded circle-shaped synthetic dataset from S3. Applied Spectral Clustering and evaluated performance (including visualization) to handle non-linear cluster structures that standard K-Means struggles with.

---

### **DATA-500 Analytical Programming with Python**
**Key Topics**: pandas, data cleaning, functions, refactoring, testing.

**DATA_500_Exam_1**: Midterm Exam – Analytical Programming with Python. Covered core Python and pandas concepts including DRY/modularity principles, data structures (lists vs NumPy arrays), missing value handling, debugging common errors (e.g., NameError, incorrect indexing), writing reusable functions, lambda functions, and OOP advantages. Included practical exercises on applying functions with .apply() and creating DataFrames.
**DATA_500_Exam_2**: Final Exam – Analytical Programming with Python. Focused on code quality best practices: indentation, descriptive naming, documentation/docstrings, refactoring, testing, and data validation. Included debugging mixed data types, creating DataFrames, and explaining concepts like scatter plots for correlation analysis.

**Hw1**: Open Food Facts Dataset Exploration – Practiced core pandas skills on a large TSV file of food products. Imported data with proper delimiter, inspected the first rows, and performed basic data exploration and DataFrame operations.
**Hwk2**: Euro 2012 Football Statistics Analysis – Analyzed Euro 2012 team statistics using pandas. Loaded CSV data, computed summary statistics (e.g., average goals, number of teams), created discipline subsets, and explored team performance metrics (goals, shots, cards, etc.).
**Hwk3**: User Demographics Analysis with GroupBy – Loaded user dataset (pipe-delimited) with user_id as index. Used groupby() to analyze mean age by occupation, gender ratios per occupation, and minimum/maximum ages across occupations.
**Hwk_4**: Diamonds Dataset with Lambda & One-Hot Encoding – Worked with the diamonds pricing dataset. Created a lambda function to flag large carat diamonds (> 2), applied it using .apply(), and performed one-hot encoding on categorical columns (cut, color, clarity) while dropping originals.
**Hwk_5**: Sales Data Cleaning Function – Created a comprehensive cleaning function for a messy sales dataset. Standardized Gender, filled missing Age with mean, normalized Purchase Date formats, converted negative Purchase Amounts to absolute values, standardized Payment Methods and Locations.
**Hwk_6**: Sales Data Cleaning & Testing – Continued data cleaning exercises with focus on writing robust, well-documented functions. Included testing of cleaning steps and validation of the final cleaned DataFrame.
**Hwk_7**: Function Testing & Power Consumption EDA – Built and tested functions for sales statistics (calculate_total_sales, calculate_average_sales, identify_outliers) with comprehensive unit tests. Loaded and explored the Power Consumption dataset (temperature, humidity, zone power usage) using pandas, matplotlib, and seaborn.
**Hwk_8**: Code Refactoring & Documentation – Refactored employee salary analysis code for better modularity. Created a helper calculate_group_stat function, added detailed docstrings to all functions, and improved overall code readability and maintainability for department-level salary and experience analysis.

**In_Class_01**: Chipotle Sales Data Exploration – Basic pandas practice on Chipotle order data. Loaded CSV, inspected first 10 rows, checked shape, data types (info()), column names, and identified the most ordered item using value counts.
**In_Class_02**: Users Dataset Exploration – Continued pandas fundamentals using the users dataset (with user_id as index). Loaded pipe-delimited CSV, displayed first 25 and last 10 rows, and practiced basic DataFrame inspection.
**In_Class_03**: Chipotle Data Filtering and Sorting – Practiced filtering and sorting on Chipotle data. Cleaned item_price (removed $ and converted to float), found products costing more than $10, removed duplicates, and performed various filtering operations.
**In_Class_04**: Drinks Dataset with GroupBy – Explored alcohol consumption data using groupby(). Calculated average beer servings by continent, summary statistics for wine servings, and mean/min/max for spirit servings across continents.
**In_Class_05**: Student Alcohol Consumption with Apply() and Lambda – Practiced the .apply() method and lambda functions on a student dataset. Loaded data, selected first 11 columns, created a lambda function to capitalize strings, and applied custom transformations.
**In_Class_06**: Euro 2012 Football Data Analysis – Loaded and explored Euro 2012 team statistics. Filtered teams that scored more than 6 goals, selected specific columns (Team, Goals, Yellow Cards), sorted by red cards, and calculated mean yellow cards per team.
**In_Class_07**: Chipotle Data Analysis – Continued advanced pandas operations on Chipotle dataset. Converted item_price to float, calculated total revenue, found most expensive items, and analyzed quantity ordered per item.
**In_Class_08**: Alcohol Consumption by Continent – Deep dive into drinks dataset using groupby. Calculated mean beer servings by continent, statistics for wine servings, and mean/max spirit servings across continents.
**In_Class_09**: Student Alcohol Consumption Analysis – Worked with student-mat dataset. Created a new column for final grade average, applied lambda functions, and performed data transformations and filtering.
**In_Class_10**: Titanic Dataset Exploration – Loaded Titanic dataset and performed initial EDA including checking for missing values, survival rate calculations, and basic statistical summaries by passenger class and gender.

---

### **DATA-511 Prescriptive Analytics**
**Key Topics**: Linear & Integer Programming, Simulation, Monte Carlo, Decision Analysis (PuLP).

**DATA_511_Exam_1**: Midterm Exam – Prescriptive Analytics. Covered linear programming, optimization modeling, sensitivity analysis, and integer programming using PuLP. Solved various business optimization problems (resource allocation, production planning, etc.) and interpreted dual prices/shadow prices.
**DATA_511_Exam_2**: Final Exam – Prescriptive Analytics. Advanced optimization topics including goal programming, nonlinear programming, network models, and simulation. Focused on building and solving complex prescriptive models for decision support.

**Hwk_1**: Linear Programming – Production Planning – Built and solved a linear programming model using PuLP to maximize profit for a manufacturing company. Defined decision variables, constraints (labor, material, demand), and performed sensitivity analysis.
**Hwk_2**: Linear Programming – Investment Portfolio Optimization – Formulated and solved an LP model to optimize investment allocation across multiple assets while satisfying risk and return constraints using PuLP.
**Hwk_3**: Integer Programming – Knapsack / Resource Allocation – Solved integer programming problems (including 0-1 and bounded integer variables) using PuLP. Focused on combinatorial optimization scenarios such as project selection or capital budgeting.
**Hwk_4**: Probability Concepts & Combinatorics – Completed theoretical exercises on basic probability rules, conditional probability, combinations vs permutations, mutually exclusive events, and sample spaces. Calculated probabilities and combinations manually.
**Hwk_5**: Probability Distributions & Linear Programming – Covered normal and binomial distributions with calculations and examples. Solved a linear programming profit maximization problem (wheat vs corn planting) using scipy.optimize.linprog with labor and land constraints.
**Hwk_6**: Decision Analysis & Decision Trees (DADT) – Explored Decision Analysis Decision Trees (DADT) concepts, differences from predictive models, and integration with integer programming. Built a multi-scenario investment decision analysis with present value calculations and expected value recommendations for City Center vs Suburb development options.
**Hwk_7**: Simulation Concepts & Monte Carlo – Studied stochastic vs non-stochastic simulations, random number generation, and types of business shocks. Implemented Monte Carlo simulation to estimate π and simulated quarterly revenue shocks using NumPy.
**Hwk_8**: Advanced Simulation & Convergence – Covered Central Limit Theorem applications in simulation, convergence diagnostics, and result stabilization. Performed die roll simulation (10,000 trials) with frequency visualization and further Monte Carlo exercises.

**In_Class_01**: Linear Programming Basics with PuLP – Introduced PuLP library for linear programming. Solved a simple resource allocation problem by defining decision variables, objective function, and constraints, then solved and extracted optimal values.
**In_Class_02**: Linear Programming – Production Planning – Built a more complex LP model using PuLP for a manufacturing production planning scenario. Defined multiple products, resource constraints (labor, materials), and maximized total profit.
**In_Class_03**: Sensitivity Analysis in Linear Programming – Continued production planning model. Performed sensitivity analysis on constraints and objective coefficients using PuLP to understand shadow prices and allowable ranges for optimal solution stability.
**In_Class_04**: Integer Programming – Knapsack Problem – Formulated and solved a 0-1 Knapsack problem using PuLP. Maximized value of selected items subject to weight capacity constraint, demonstrating binary decision variables.
**In_Class_05**: Integer Programming – Capital Budgeting / Project Selection – Solved a binary integer programming model for project selection. Maximized total return/NPV while respecting budget constraints using PuLP.
**In_Class_06**: Linear & Integer Programming Review – Reviewed core concepts of linear programming (objective function, constraints) vs integer programming. Solved a pastry shop profit maximization problem using both scipy.optimize.linprog (continuous) and milp (integer constraints) with PuLP-style modeling.
**In_Class_07**: Decision Analysis Decision Trees (DADT) – Differentiated between Machine Learning Decision Trees (MLDT) and Decision Analysis Decision Trees (DADT). Built a function to calculate present value of an annuity and computed expected present value for a hotel development project under Low/Medium/High scenarios using scenario probabilities.
**In_Class_08**: Simulation Fundamentals – Covered key simulation concepts including pseudo-random numbers, reproducibility (random seeds), and components of stochastic simulations. Implemented a Linear Congruential Generator (LCG) function to produce pseudo-random numbers.
**In_Class_09**: Advanced Simulation Techniques – Explored probability distributions for simulation (Triangular distribution), simulation-based regression, and Monte Carlo methods. Implemented a coin toss simulation (10,000 trials) and discussed how simulation handles uncertainty in optimization models.
**In_Class_10**: What-If & Scenario Analysis – Differentiated scenario analysis from basic what-if analysis. Built a logistic take-rate function and performed contribution margin simulation for pricing decisions (revenue, cost, and profit under varying market conditions).

---

### **DATA-547 Applied Deep Learning I**
**Key Topics**: TensorFlow/Keras, CNNs, image classification, regression with neural nets.

**DATA_547_Exam_1**: Midterm Exam – Applied Deep Learning I. Comprehensive theory and practical assessment covering TensorFlow fundamentals, CNN concepts (convolutional/pooling layers, data augmentation), activation functions, dense layers, and building deep learning models for regression (blueberry yield prediction using bee density, temperature, and other features).
**DATA_547_Exam_2**: Final Exam – Applied Deep Learning I. Advanced topics including word embeddings (Word2Vec, GloVe, FastText), RNNs, LSTMs, GRUs, and building neural networks for text classification (airline tweet sentiment analysis).

**Hwk_1**: TensorFlow Basics & Perceptron Model – Explored TensorFlow tensor creation, data type casting, and string tensors. Built and trained a single-layer Perceptron (sigmoid activation) on a synthetic binary classification dataset using scikit-learn, achieving strong accuracy.
**Hwk_2**: California Housing Regression with TensorFlow – Built and compared neural network regressors on the California Housing dataset. Implemented models with BatchNormalization, hidden layers (ReLU), Adam optimizer, and Mean Squared Error evaluation. Trained with validation split and evaluated on test set.
**Hwk_3**: Crab Age Prediction Regression – Performed EDA on the Crab Age Prediction dataset (including sex frequency and age distribution). Built TensorFlow/Keras neural network regressors to predict crab age from physical attributes (length, weight, etc.).
**Hwk_4**: Fashion MNIST Image Classification – Loaded and explored the Fashion MNIST dataset (60k train / 10k test 28x28 grayscale images). Visualized sample images across 10 clothing categories and prepared data for CNN modeling.
**Hwk_5**: CNN for Fashion MNIST Classification – Built a Convolutional Neural Network (CNN) using TensorFlow/Keras with two Conv2D + MaxPooling layers, Flatten, Dense(128, ReLU), and softmax output. Trained for 50 epochs with Adam optimizer and achieved strong test accuracy on multi-class image classification.
**Hwk_6**: Wine Reviews Regression with TensorFlow – Loaded and explored the Wine Reviews dataset (winemag-data-130k-v2.csv). Performed data cleaning (removing punctuation from descriptions), EDA on variety and country distributions, and prepared features for regression modeling of wine points or price using TensorFlow.
**Hwk_7**: (Deep Learning Image / Text Task) – Continued deep learning exercises on image classification or text-based regression using TensorFlow/Keras. Focused on model architecture refinement, training, and evaluation.
**Hwk_8**: (Advanced CNN / Transfer Learning) – Advanced CNN implementation, likely including data augmentation, deeper architectures, or transfer learning techniques on image or wine-related datasets.

**In_Class_01**: TensorFlow Fundamentals – Explored core TensorFlow concepts including tensor creation, operations, variables, automatic differentiation (GradientTape), and basic neural network building blocks.
**In_Class_02**: Building a Neural Network from Scratch in TensorFlow – Implemented a basic feed-forward neural network using TensorFlow low-level operations. Covered forward propagation, loss calculation, and manual gradient descent updates.
**In_Class_03**: Keras Sequential API Basics – Built and trained neural networks using the high-level Keras Sequential API. Included dense layers, activation functions, model compilation (optimizer/loss/metrics), and training with .fit().
**In_Class_04**: California Housing Regression with Keras – Built a multi-layer neural network regressor using Keras Sequential API on the California Housing dataset. Applied feature scaling, train/validation/test splits, and evaluated performance with MSE/MAE.
**In_Class_05**: Binary Classification with Keras – Built a Keras Sequential model for binary classification. Included data preprocessing, model architecture (hidden layers + sigmoid output), training, and evaluation using accuracy and other classification metrics.
**In_Class_06**: Multi-Class Classification with Keras – Built a Keras Sequential model for multi-class classification. Included data preprocessing (one-hot encoding of labels), model architecture with softmax output, and evaluation using accuracy and confusion matrices.
**In_Class_07**: Fashion MNIST Image Classification (MLP) – Loaded Fashion MNIST dataset and built a Multi-Layer Perceptron (MLP) using Keras for image classification. Flattened 28x28 images and trained a dense neural network on the 10 clothing categories.
**In_Class_08**: Fashion MNIST with Convolutional Neural Network (CNN) – Built and trained the first CNN model on Fashion MNIST. Implemented Conv2D + MaxPooling layers, Flatten, and Dense layers. Significantly improved performance over the MLP version.
**In_Class_09**: CNN Architecture Improvements – Enhanced the Fashion MNIST CNN with additional convolutional layers, dropout regularization, and hyperparameter tuning. Focused on reducing overfitting and improving test accuracy.
**In_Class_10**: Data Augmentation for Image Classification – Applied real-time data augmentation (rotation, zoom, flips, shifts) using ImageDataGenerator on Fashion MNIST to improve model generalization and robustness.
**In_Class_11**: Advanced CNN Techniques & Model Evaluation – Further refined CNN architecture with batch normalization, additional data augmentation strategies, and comprehensive model evaluation (learning curves, confusion matrix, per-class performance).

---

### **DATA-548 Applied Deep Learning II**
**Key Topics**: RNNs, LSTMs, GRUs, Bidirectional layers, Word Embeddings, Attention, Transformers.

**DATA_548_Exam_1**: Midterm Exam – Applied Deep Learning II. Covered advanced deep learning topics including RNNs, LSTMs, GRUs, sequence modeling, word embeddings, and text classification techniques.
**DATA_548_Exam_2**: Final Exam – Applied Deep Learning II. Comprehensive final assessment on sequence models, transfer learning, advanced architectures (Transformers, attention mechanisms), and practical implementation of deep learning solutions for text and time-series data.

**Hwk_1**: IMDb Movie Review Sentiment Analysis (RNN/LSTM) – Loaded and preprocessed the IMDb dataset. Built and compared RNN and LSTM models for binary sentiment classification of movie reviews using TensorFlow/Keras.
**Hwk_2**: Advanced Sequence Modeling with LSTM & Bidirectional Layers – Enhanced IMDb sentiment models with Bidirectional LSTM layers, increased model capacity, and experimented with different optimizers and regularization techniques.
**Hwk_3**: Word Embeddings & Text Preprocessing – Explored different word embedding techniques (Word2Vec, GloVe, Keras Embedding layer). Performed text tokenization, padding, and prepared sequences for deep learning models.
**Hwk_4**: Airline Tweet Sentiment Analysis – Built deep learning models (LSTM-based) to classify sentiment in airline customer tweets. Included text cleaning, tokenization, embedding layers, and model training/evaluation.
**Hwk_5**: Advanced LSTM & Bidirectional Models for Sentiment Analysis – Improved upon previous IMDb or tweet sentiment models by implementing Bidirectional LSTMs, increased embedding dimensions, and experimented with different sequence lengths and dropout rates.
**Hwk_6**: Transfer Learning with Pre-trained Embeddings – Integrated pre-trained word embeddings (GloVe or FastText) into LSTM models for text classification tasks. Compared performance against randomly initialized embeddings.
**Hwk_7**: (Advanced Text / Sequence Modeling) – Final homework covering more advanced sequence modeling techniques, possibly including GRU, attention mechanisms, or model optimization for text classification tasks.

**In_Class_1**: Introduction to Sequence Models (RNN Basics) – Implemented basic Recurrent Neural Networks (RNNs) in TensorFlow/Keras for sequential data. Covered vanishing gradient problem discussion and simple time-series or text sequence tasks.
**In_Class_2**: LSTM for Sequence Modeling – Built and trained Long Short-Term Memory (LSTM) networks. Compared LSTM performance against vanilla RNNs on sequence prediction or classification tasks.
**In_Class_3**: Bidirectional LSTM & Text Preprocessing – Explored Bidirectional LSTMs and advanced text preprocessing pipelines (tokenization, padding, vocabulary building) for sentiment analysis or text classification.
**In_Class_4**: GRU Models for Sequence Data – Introduced Gated Recurrent Units (GRU) as a lighter alternative to LSTM. Built and compared GRU vs LSTM models on text or time-series sequence classification tasks in TensorFlow/Keras.
**In_Class_5**: Attention Mechanisms Introduction – Explored basic attention mechanisms to improve sequence model performance. Implemented attention layers on top of RNN/LSTM/GRU architectures for better focus on important parts of input sequences.
**In_Class_6**: Bidirectional & Stacked Sequence Models – Built deeper sequence models using stacked Bidirectional LSTM/GRU layers. Focused on improving representation learning for sentiment analysis or text classification tasks.
**In_Class_7**: Pre-trained Embeddings & Fine-tuning – Loaded and integrated pre-trained word embeddings (GloVe or similar) into Keras models. Compared trainable vs frozen embedding layers for text classification performance.
**In_Class_8**: Transformer Basics & Self-Attention – Introduced Transformer architecture concepts. Implemented or experimented with multi-head self-attention mechanisms using TensorFlow/Keras.
**In_Class_9**: Advanced Text Modeling Techniques – Combined multiple advanced techniques (Bidirectional layers, attention, pre-trained embeddings, regularization) into a final strong text classification model. Included hyperparameter tuning and model evaluation.

---

### **DATA-549 Natural Language Processing**
**Key Topics**: Text preprocessing, TF-IDF, spaCy NER, LDA Topic Modeling, Sentiment Analysis.

**DATA_549_Exam_1**: Midterm Exam – NLP. Comprehensive assessment covering core NLP concepts: tokenization, stemming vs lemmatization, Bag-of-Words, TF-IDF, stop words, text cleaning pipelines, and practical implementation of a clean_text function using NLTK (lowercasing, punctuation removal, tokenization, stopword removal) plus lemmatization on customer reviews.
**DATA_549_Exam_2**: Final Exam – NLP. Advanced topics including cosine similarity, clustering evaluation (Silhouette), regex for information extraction (currency detection), Named Entity Recognition (NER) with spaCy, LDA topic modeling (PyLDAvis), word embeddings, BERT, and building a full text classification pipeline on BBC news articles with TF-IDF vectorization.

**Hwk_1**: Text Preprocessing Fundamentals – Practiced core text manipulation: removing punctuation with regex, splitting strings, identifying long words, finding unique words with set(), removing extra spaces, and stripping numbers from text using custom functions.
**Hwk_2**: (NLP Text Cleaning & Basic Processing) – Continued foundational NLP preprocessing exercises, likely including tokenization, stopword removal, and basic feature creation from raw text.
**Hwk_3**: (NLP Text Processing & Feature Engineering) – Further text cleaning, normalization, and feature extraction techniques building on previous homework.
**Hwk_4**: Wine Reviews Dataset Exploration & Text Cleaning – Loaded the winemag-data-130k-v2.csv wine dataset. Performed initial EDA (number of varieties, countries), and cleaned the description column by removing punctuation using the string library, storing results in description_clean.
**Hwk_5**: Wine Reviews Text Preprocessing – Continued work on the wine reviews dataset. Loaded data, conducted EDA on varieties and countries, and applied punctuation removal to create a cleaned description column for further NLP analysis.
**Hwk_6**: Wine Reviews Advanced Text Cleaning – Further preprocessing on the wine dataset including punctuation removal and preparation of text descriptions for vectorization and modeling.
**Hwk_7**: Wine Reviews Text Processing Continuation – Additional NLP preprocessing steps on wine review descriptions (cleaning, exploration) as part of the ongoing wine dataset project.
**Hwk_8**: Fuzzy Matching, NER with spaCy & Word Clouds – Implemented Levenshtein distance for fuzzy email matching. Used spaCy for Named Entity Recognition (NER) visualization with displacy on sample text. Created a shaped word cloud (circular mask) from Sherlock Holmes text using PIL and wordcloud library.

**In_Class_01**: Working with Text Data in pandas – Practiced pandas string methods on time-related sentences. Extracted text length, token counts, filtered sentences containing specific words, and used regex to abbreviate weekdays.
**In_Class_02**: Basic String and List Operations on Text – Performed fundamental text manipulation in pure Python: splitting sentences into words, filtering by length, identifying capitalized words and words ending in 's', and using sets for unique word counting (including case normalization).
**In_Class_03**: Spam Dataset Exploration & Text Cleaning – Loaded spam/ham dataset, examined class distribution, removed punctuation using the string library, and used NLTK to remove stopwords for cleaned text versions.
**In_Class_04**: Advanced Text Cleaning & Tokenization – Continued spam dataset work with further preprocessing, tokenization, and text normalization techniques.
**In_Class_05**: Text Vectorization Basics (CountVectorizer / TF-IDF) – Implemented Bag-of-Words and TF-IDF vectorization on cleaned text data using scikit-learn. Prepared features for downstream classification or similarity tasks.
**In_Class_06**: Cosine Similarity & Document Comparison – Calculated cosine similarity between documents using vectorized representations to identify similar texts in the spam or review datasets.
**In_Class_07**: Regex Pattern Matching – Practiced regular expressions for extracting patterns such as times, dates, currency, emails, or phone numbers from text data.
**In_Class_08**: Named Entity Recognition (NER) with spaCy – Used spaCy for entity extraction (persons, organizations, locations, dates, etc.) and visualization on sample texts.
**In_Class_09**: Topic Modeling with LDA – Applied Latent Dirichlet Allocation (LDA) for topic modeling on document collections, including visualization with pyLDAvis.
**In_Class_10**: Sentiment Analysis or Text Classification Pipeline – Built an end-to-end pipeline combining preprocessing, vectorization, and classification (or sentiment scoring) on a text dataset (likely reviews or news).

---

### **DATA-550 Intro to MLOps**
**Key Topics**: Experiment tracking (MLflow), hyperparameter tuning (Optuna), modular pipelines, ensembles, model monitoring (Evidently).

**DATA_550_Exam_1**: Seoul Bike Sharing Demand Prediction – Performed EDA, feature engineering (one-hot encoding + time features), and built multiple tree-based regression models (Random Forest, Extra Trees, GB, XGBoost, LightGBM) with Optuna hyperparameter tuning and 5-fold CV. Tracked experiments with MLflow and evaluated ensembles.
**DATA_550_Exam_2**: Seoul Bike Sharing Advanced MLOps – Built a full end-to-end pipeline with data preprocessing, Optuna tuning of six regression models (including CatBoost), MLflow tracking, feature importance, VotingRegressor, StackingRegressor, and data drift detection using Evidently.

**HW1**: Crab Age Prediction – Baseline Models – Developed modular Python scripts to train RandomForest, ExtraTrees, GradientBoosting, XGBoost, and TensorFlow Neural Network models on the Crab Age dataset. Implemented 5-fold CV (MAE) and logged all experiments with MLflow.
**HW2**: Crab Age Prediction – Optuna Hyperparameter Tuning – Built modular scripts for Optuna hyperparameter tuning (30 trials) on RandomForest, ExtraTrees, GradientBoosting, XGBoost, and CatBoost models with 5-fold CV (RMSE) and full MLflow tracking.
**HW3**: Seoul Bike Sharing – Advanced MLOps Pipeline – Implemented modular training scripts for multiple tree-based models (RF, ET, GB, XGBoost, LightGBM, CatBoost) with Optuna tuning, MLflow tracking, and supporting preprocessing/inference scripts.
**HW4**: Crab Age Prediction – Tuning + Interpretability – Performed Optuna hyperparameter tuning on six regression models with MLflow tracking, permutation importance, partial dependence plots, and ensemble evaluation on the test set.
**HW5**: Crab Age Prediction – Ensemble & Stacking – Built Optuna-tuned models, VotingRegressor, and StackingRegressor (Ridge meta-learner) with full MLflow tracking and final test set evaluation using modular Python scripts.
**HW6**: Crab Age Prediction – Advanced Ensembles – Developed comprehensive ensemble pipeline including multiple VotingRegressor variants and Stacking (Ridge/Lasso) with Optuna-tuned base models and full MLflow tracking.
**HW7**: Production Monitoring with Evidently – Implemented data drift and model performance monitoring using Evidently. Generated and logged interactive reports to MLflow for train vs test comparisons.

**In_Class_1**: Insurance Charges Prediction – MLOps Introduction – Built baseline regression models (Random Forest, Gradient Boosting, Extra Trees) on insurance data with one-hot encoding and logged experiments to MLflow.
**In_Class_2**: Insurance Charges Prediction – Modular Model Tracking – Created five modular scripts to train RandomForest, ExtraTrees, GradientBoosting, XGBoost, and TensorFlow models with 5-fold CV and MLflow tracking.
**In_Class_3**: Insurance Premium Prediction – Built modular scripts for Optuna hyperparameter tuning of RandomForest, ExtraTrees, and GradientBoosting models on insurance charges data with 5-fold CV (RMSE) and MLflow tracking.
**In_Class_4**: Insurance Premium Prediction – Modular Pipeline – Developed preprocessing and modular training/tuning scripts for multiple regression models with Optuna, 5-fold CV, MLflow tracking, and final model evaluation on test data.
**In_Class_5**: Insurance Premium Prediction – Ensemble Workflow – Continued modular MLOps pipeline with Optuna tuning, MLflow tracking, model comparison, and ensemble evaluation on the insurance charges dataset.
**In_Class_6**: Insurance Premium Prediction – Advanced Ensemble Evaluation – Built modular training and tuning pipelines for multiple models with Optuna and MLflow, including ensemble modeling and final test set evaluation.
**In_Class_7**: Insurance Premium Prediction – Full Ensemble Pipeline – Implemented comprehensive modular pipeline with Optuna-tuned models (RF, ET, GB, XGBoost, LightGBM, CatBoost), VotingRegressor, StackingRegressor, and MLflow tracking.
**In_Class_8**: Insurance Premium Prediction – Advanced Ensembles – Developed full end-to-end MLOps pipeline including preprocessing, Optuna tuning of multiple models, MLflow tracking, and advanced ensemble methods (Voting + Stacking).
**In_Class_9**: Insurance Premium Prediction – Model Monitoring & Optimization – Extended MLOps workflow with preprocessing, Optuna hyperparameter tuning, MLflow tracking, and systematic model evaluation for production readiness.

---

## Technologies Used
**Languages**: Python, R, SQL  
**ML/DL**: scikit-learn, XGBoost, LightGBM, CatBoost, TensorFlow/Keras  
**MLOps**: MLflow, Optuna, Evidently  
**Other**: PuLP, spaCy, NLTK, pandas, Matplotlib/Seaborn, etc.




















