# Security Automation with AI and GenAI

This repository contains a collection of projects demonstrating the application of Artificial Intelligence (AI) and Generative AI techniques for cybersecurity automation. The projects focus on threat detection, anomaly identification, and network defense using advanced deep learning architectures such as Transformers and Adaptive Attention mechanisms.

## Table of Contents

* [Introduction](#introduction)
* [Repository Structure](#repository-structure)
* [Key Features](#key-features)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
* [Datasets](#datasets)
* [License](#license)

## Introduction

As cyber threats evolve in complexity, traditional signature-based detection methods often fall short. This project explores the use of machine learning and deep learning to automate security operations. By leveraging models like Transformers and Attention-based networks, this repository aims to provide robust solutions for detecting SQL injections, network intrusions, DDoS attacks, web application attacks, and malware in network traffic.

## Repository Structure

The codebase is organized into specific source directories, each targeting a distinct cybersecurity domain:

### Source0: SQL Injection Detection
* **Focus**: Detection of SQL Injection (SQLi) attacks using Transformer models.
* **Content**: Contains notebooks for training SQL Transformers and modified datasets tailored for SQLi analysis.

### Source1: Network Intrusion Detection
* **Focus**: Identification of unauthorized network access and anomalies.
* **Dataset**: UNSW-NB15.
* **Methodology**: Utilizes Transformer-based architectures to classify network traffic patterns as normal or malicious.

### Source3: DDoS Detection
* **Focus**: Detection of Distributed Denial of Service (DDoS) attacks.
* **Methodology**: Implements Adaptive Attention mechanisms to analyze traffic flow and identify DDoS signatures in real-time.

### Source5: Web Application Injection Detection
* **Focus**: Protecting web applications from various injection attacks.
* **Dataset**: CSIC Database (HTTP dataset).
* **Methodology**: Deep learning models designed to parse and classify HTTP requests.

### Source10: Malware Detection
* **Focus**: Identification of malware communication within network traffic.
* **Methodology**: Network traffic analysis using machine learning classifiers to distinguish between benign and malware-infected traffic.

## Key Features

* **Deep Learning Architectures**: Implementation of state-of-the-art models including Transformers and Multi-Head Attention layers.
* **Data Preprocessing**: Comprehensive pipelines for cleaning, tokenizing, and normalizing cybersecurity datasets.
* **Performance Metrics**: Detailed evaluation using accuracy, precision, recall, F1-score, and confusion matrices.
* **Visualizations**: Extensive use of Matplotlib and Seaborn for data distribution and training performance analysis.

## Technologies Used

* **Programming Language**: Python
* **Deep Learning Framework**: TensorFlow, Keras
* **Data Manipulation**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-learn (for preprocessing and metrics)

## Getting Started

### Prerequisites

Ensure you have Python 3.8+ installed. It is recommended to use a virtual environment or Conda environment to manage dependencies.

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/arfazrll/security-automation-ai-genai.git](https://github.com/arfazrll/security-automation-ai-genai.git)
    cd security-automation-ai-genai
    ```

2.  Install the required packages. While a requirements file is not provided, the primary dependencies can be installed via pip:
    ```bash
    pip install tensorflow pandas numpy matplotlib seaborn scikit-learn jupyter
    ```

### Usage

1.  Navigate to the specific source directory you wish to explore (e.g., Source0 for SQL Injection).
2.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3.  Open the `.ipynb` file within the `notebook` subdirectory to view the code, training process, and results.

## Datasets

This repository utilizes various open-source cybersecurity datasets, including but not limited to:
* **UNSW-NB15**: For network intrusion detection.
* **CSIC 2010**: For HTTP protocol traffic and web injection analysis.
* **Modified SQL Dataset**: Custom or aggregated datasets for SQL injection training.

*Note: Please refer to the specific dataset documentation within each source folder for citation and usage rights.*

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
