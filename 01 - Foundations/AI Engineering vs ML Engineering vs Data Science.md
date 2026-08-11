
These three roles are closely related, so it is easy to confuse them. There is also **no universal boundary** between them. Different companies may use the same job title for somewhat different responsibilities.

For now, the easiest way to understand them is by looking at their **main focus**.

```mermaid
flowchart LR
    D[Data Science] --> M[Machine Learning]
    M --> E[ML Engineering]
    E --> A[AI Engineering]
```

This diagram is only a simple mental model. In real companies, these areas often overlap.

## Data Science

**Data Science** focuses mainly on understanding data and using it to answer questions or support decisions.

A data scientist might ask:

> "What is happening in our data, and what can we learn from it?"

For example, they might analyze customer behavior and discover which customers are likely to leave a service.

Typical work can include:

```text
Data
 ↓
Analysis
 ↓
Statistics
 ↓
Visualization
 ↓
Insights / Predictions
```

## Machine Learning Engineering

**Machine Learning Engineering** focuses more on building and operating machine-learning models.

A machine-learning engineer might take a model developed through experimentation and turn it into something that can reliably run in a production system.

```text
Data
 ↓
Training
 ↓
Model
 ↓
Evaluation
 ↓
Deployment
 ↓
Monitoring
```

They often care about things such as training pipelines, model performance, data pipelines, deployment, and scaling.

## AI Engineering

**AI Engineering** is a broader and newer term that often focuses on **building applications using modern AI models**.

For example, an AI engineer might build a document-question-answering application using an existing language model.

```text
User
 ↓
AI Application
 ↓
Retrieve Information
 ↓
AI Model
 ↓
Response
 ↓
User
```

The engineer may not have created the underlying language model. Instead, they integrate the model into a useful software system.

## Simple Comparison

|Role|Main Focus|
|---|---|
|**Data Scientist**|Understand data and find insights|
|**ML Engineer**|Build, train, deploy, and operate ML models|
|**AI Engineer**|Build applications and systems using AI models|

There is significant overlap between these roles. A company may have one person doing work from all three areas, especially in a small team.

> [!important] Remember  
> **Data Science → focuses on data and insights.**
> 
> **ML Engineering → focuses on machine-learning models and their lifecycle.**
> 
> **AI Engineering → focuses on building useful software systems around AI capabilities.**

For this wiki, our main focus will be **AI Engineering**, while learning enough machine learning, deep learning, and computer systems to understand what is happening underneath.

Next: [[AI System — Big Picture]].