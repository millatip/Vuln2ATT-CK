# vuln2att&ck

## Project Overview

The main objective of this project is to create a graph of attack sequences between CVEs using MITRE techniques and mapping type connections.

## Steps

1. **Train the Model**
    - Train the BERT (or Llama with LoRa or other suitable models) on 827 labeled CVEs.

2. **Collect AWS Related CVEs**
    - Collect AWS related CVEs using the AWS unique resource types list compared to CVE descriptions.

3. **Predict MITRE Techniques**
    - Use the trained model to predict MITRE techniques for AWS related, unlabeled CVEs.

4. **Train GNN Model**
    - Use the expanded dataset to train a GNN model to map CVE nodes to MITRE techniques nodes using the mapping type as the edge.

5. **Validate the Results**
    - Validate the results using a small portion of the dataset.

6. **Visualize the Results**
    - Visualize the results of the mapping and predictions.

7. **Refine the Model**
    - Use active learning to refine the model for better accuracy.

## Objective

The main objective is to create a graph of attack sequences between the CVEs using MITRE techniques and mapping type connections.
