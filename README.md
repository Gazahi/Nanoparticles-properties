# Nanocomposite Properties Classification Database

## Description
This database contains the properties of various nanocomposites and aims to facilitate their classification based on physical and chemical characteristics. 
It was developed as part of a study focused on enhancing nanocomposite classification using nanoparticles as discriminative variables. This database is designed for use with machine learning or deep learning models.

## Background
The database was utilized in the scientific article “Improving the Classification of a Nanocomposite Using Nanoparticles Based on a Meta-Analysis Study, Recurrent Neural Network, and Recurrent Neural Network Monte Carlo Algorithms.” 
This article explores how advanced models, such as recurrent neural networks, can improve the accuracy of nanocomposite classification by leveraging a set of key physical and chemical properties.

## Database Structure
Each entry in the database represents a nanocomposite with its measured properties. The input variables (or *features*) include:

- **P1: Electrical Conductivity (EC)** 
- **P2: Elastic Modulus (M)** 
- **P3: Tensile Strength (T)** 
- **P4: Concentration (CO)** 
- **P5: Molecular Weight (W)** 
- **P6: Temperature (TM)**
- **P7: Nanomaterial Size (S)** 
- **P8: Flexural Strength (F)**

The **output variables** are predefined classes **A, B, C, D**, and **E**, which categorize each nanocomposite based on its property values. 
These classes enable qualitative classification based on the measured values.

### Data Normalization
This database has been normalized. 
Each property was adjusted based on mean and standard deviation calculations, optimizing it for machine learning models by reducing scale variation and facilitating convergence during training.

## Objective
The primary objective is to provide an organized dataset for training and evaluating nanocomposite classification models, thereby offering insights into the impact of nanoparticles on material properties.

## Usage
Users can download this database to experiment with various classification algorithms.
