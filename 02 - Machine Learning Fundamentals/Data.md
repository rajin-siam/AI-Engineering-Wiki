
> [!abstract] Definition  
> **Data** is the information that a machine-learning system uses to learn patterns and make predictions.

A machine-learning model cannot learn from nothing. It needs examples. These examples are called **data**.

For example, if we want to build a model that predicts house prices, our data might contain information about many houses:

```text
House → Size → Bedrooms → Location → Price
```

A collection of many such examples becomes our **dataset**.

## Simple Example

Suppose we have this dataset:

|Size|Bedrooms|Price|
|---|--:|--:|
|800 sq ft|2|$100,000|
|1200 sq ft|3|$150,000|
|1800 sq ft|4|$220,000|

The model can study these examples and learn patterns between the information about a house and its price.

```mermaid
flowchart LR
    D[House Data] --> M[Machine Learning Model]
    M --> P[Learned Patterns]
```

Later, we can give the model a new house and ask it to predict the price.

## Types of Data

Data can come in many forms. In AI, common types include:

- **Text** — documents, messages, articles
    
- **Images** — photographs, medical images, diagrams
    
- **Audio** — speech, music, sounds
    
- **Video** — movies, recordings, camera footage
    
- **Numbers** — prices, temperatures, measurements
    
- **Structured data** — information stored in tables
    

For example, an AI system that recognizes cats might learn from **images**, while a chatbot learns from large amounts of **text**.

## Data and Machine Learning

The basic relationship is:

```text
Data
 ↓
Machine Learning
 ↓
Model learns patterns
 ↓
New Data
 ↓
Prediction
```

The quality of the data matters a lot. If the data is incomplete, incorrect, or poorly prepared, the model may learn bad patterns.

You will learn about data quality and preparation later. For now, the important thing is simply that **data is the raw material from which a machine-learning model learns**.

> [!important] Remember  
> **Data is the information and examples used by a machine-learning system to learn patterns and make predictions.**

