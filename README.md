# Distributed Data Processing Activity

## Parallel and Distributed Computing (PDC) - Final Assignment

## 📌 Project Overview

### This project demonstrates the application of Distributed Computing concepts using Apache Spark within a cloud-based environment (Google Colab). The activity focuses on processing large datasets efficiently by leveraging Spark's distributed architecture, transformations, and actions.


## 🛠️ Tools & Technologies
### - Language: Python

### - Framework: PySpark (Apache Spark 4.0.2)

### - Environment: Google Colab (PaaS)

### - Dataset: California Housing Dataset (Distributed CSV)

### - Ai: ChatCPT and Gemini Ai (Assistance)

## 🚀 Implementation Details

## Part I: Setup
### The environment was initialized by installing pyspark and creating a SparkSession. The system was configured to use all available CPU cores, as indicated by the local[*] master configuration.

## Part II: Big Data Processing
### The activity involved loading a distributed CSV file and performing the following operations:

### Data Loading: Reading the dataset with schema inference.

### Filtering: Isolating specific rows based on housing value criteria.

### Aggregation: Grouping data by housing age to calculate average values.

### Sorting: Ordering the results to identify trends in the dataset.

## 📊 Performance & Scalability Analysis

### Data Partitioning
- Spark divides data into manageable chunks known as Partitions. This allows the Driver to distribute specific pieces of work to multiple worker cores simultaneously, enabling Distributed Processing.

### Scalability
- As dataset sizes increase, Spark handles the load through Horizontal Scaling. By adding more worker nodes or increasing partitions, Spark maintains performance and avoids the memory crashes typical of sequential Python processing.

### Cloud Integration
- Using Google Colab represents a Platform as a Service (PaaS) model. This cloud infrastructure provides the Elasticity required for distributed systems, allowing for high-performance analytics without local hardware limitations.


## 📂 Repository Structure

### distributed_data_activity_lipata.ipynb: The primary notebook containing all code, outputs, and analysis.

### README.md: Project documentation.
