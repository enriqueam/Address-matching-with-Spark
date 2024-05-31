# Address-matching with Apache Spark

### Introduction

This repository contains the Bachelor's Thesis titled "Association of Postal Addresses Using Natural Language Processing and Machine Learning Techniques." The objective of this project is to tackle the challenge of associating postal addresses through advanced natural language processing (NLP) and machine learning techniques, with a particular focus on using Apache Spark to handle large volumes of data.

The work is based on a database provided by the Canary Islands Institute of Statistics (ISTAC), which contains over two million detailed records of addresses in the Canary Islands Autonomous Community. To accomplish this project, several fundamental stages have been followed:

1. **Data Cleaning and Preprocessing**: An exhaustive data cleaning and preprocessing process has been performed to ensure data quality and consistency. This includes managing null values, extracting street types, and generating new data to increase the frequency of certain addresses.

2. **Study and Configuration of Apache Spark**: The use of Apache Spark and its Python API, PySpark, has been explored, configuring the environment to optimize memory allocation and distributed processing.

3. **Implementation of Pre-trained Models**: Pre-trained models have been used to calculate vector representations of addresses and search for semantic similarities. Additionally, Chroma DB has been integrated for efficient storage and querying of these vector representations.

Throughout the project, significant challenges related to resource management and computational efficiency have been faced. Various configurations of Apache Spark have been experimented with to optimize system performance and handle large volumes of data without exceeding memory limitations.

Finally, an exhaustive analysis of the obtained results has been conducted, identifying areas for improvement and possible directions for future research.

This repository includes the source code, preprocessing scripts, Apache Spark configurations, and the models used for the processing and analysis of postal addresses. We hope this work contributes to the development of more efficient techniques for the association of postal addresses and the handling of large data volumes in the field of natural language processing.
