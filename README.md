## Project Description

The project focuses on implementing machine learning models for predicting data exfiltration via DNS in the domain of cybersecurity. Divided into two distinct parts, it revolves around the creation and evaluation of both static and dynamic models.

### Static Model (Part I)

- **Objective**: Develop a predictive binary classifier based on batch data obtained from top-secret files provided by Ring Canada (RC) and the Cyber Threat Intelligence (CTI).
- **Tasks**:
  - Conduct data analysis to understand feature distributions, imbalances, and data patterns.
  - Perform feature engineering, transforming string values for model compatibility and handling missing or categorical data.
  - Use statistical techniques for feature selection and filter out the most effective features for model training.
  - Train multiple models, select the best-performing one based on metrics, and evaluate its performance on a test set.

### Dynamic Model (Part II)

- **Objective**: Implement an alternative analysis using Online Learning to simulate a continuous data stream and make real-time predictions.
- **Tasks**:
  - Set up a simulated real-time data stream using Kafka and relevant dependencies.
  - Utilize the previously trained static model and a dynamic model for continuous analysis.
  - Evaluate and compare the performance of both models on incoming data stream windows.
  - Decide when to retrain the dynamic model based on its performance and justify the decision.
  - Assess the effectiveness of the dynamic model compared to the static model and draw conclusions regarding its suitability in a continuous data stream scenario.
