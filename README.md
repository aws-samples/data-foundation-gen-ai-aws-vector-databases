
# Data foundation for Gen AI - AWS Vector databases (AWS workshop)

This repository contains code examples and notebooks for building Retrieval Augmented Generative (RAG) AI applications using various AWS vector database options. The notebooks demonstrate how to leverage the power of AWS vector databases to build efficient and scalable data foundations for RAG models, enabling the generation of accurate, contextual, and knowledge-grounded outputs.

## Overview

Retrieval Augmented Generative AI combines the generative capabilities of large language models with the ability to retrieve and incorporate relevant information from external knowledge sources. This approach enhances the factual accuracy and domain awareness of the generated content by augmenting the generative model with retrieved knowledge.

AWS offers a diverse range of vector database options, each with its unique features and capabilities, allowing developers to choose the solution that best fits their specific needs and existing skills. This repository provides examples and code for the following AWS vector database options:

- **OpenSearch**
- **PostgreSQL with pg_vector**
- **SQL Server**
- **Amazon DocumentDB (MongoDB-compatible)**
- **Amazon MemoryDB (Redis-compatible)**

## Repository Structure

The repository is structured as follows:

```
data-foundation-gen-ai-aws-vector-stores/
├── lab1-rag/
│   ├── opensearch/
│   ├── pg_vector/
│   ├── sql_server/
│   ├── documentdb/
│   └── memorydb/
├── cfn/
│   └── ... (cloudformation templates)
├── data/
│   └── ... (sample data files)
├── utils/
│   └── ... (utility scripts and functions)
├── requirements.txt
└── README.md
```

- The `lab1-rag/` directory contains Jupyter Notebooks for building RAG use case using you choice of AWS vector database, demonstrating how to set up, configure, and use the vector database for the use case.
- The `cfn/` directory holds the cloudformation template that can be deployed to provision resources for this workshop. Please note that this will incur cost. Please study the cloudformation resources in the template and understand their associated cost before deploying in your account.
- The `data/` directory holds sample data files used in the notebooks for demonstration purposes.
- The `utils/` directory contains utility scripts and functions shared across the notebooks.
- The `requirements.txt` file lists the Python dependencies required to run the notebooks.

## Getting Started

To get started with this repository, follow these steps:

1. Clone the repository to your local machine or AWS Cloud9 environment.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Launch an Amazon SageMaker notebook instance or use your existing instance.
4. Open the relevant notebook from the `lab1-rag/` directory based on the AWS vector database option you want to explore.
5. Follow the instructions and code examples in the notebook to set up the vector database, ingest and preprocess data, and build and evaluate a RAG model.

## Usage

Each notebook in the `lab1-rag/` directory provides a step-by-step guide and code examples for building a RAG use case using the respective AWS vector database. The notebooks cover the following aspects:

- Setting up and configuring the vector database
- Ingesting and preprocessing data
- Creating vector embeddings
- Indexing and storing vector data in the vector database
- Implementing similarity search and nearest neighbor queries
- Building and evaluating a RAG model
- Integrating with other AWS services (e.g., AWS Bedrock, Amazon SageMaker)

Feel free to modify the code and data to suit your specific use case or experiment with different configurations and settings.

## Contributing

Contributions to this repository are welcome! If you have improvements, bug fixes, or additional examples to share, please submit a pull request. For major changes, it's recommended to open an issue first for discussion.

## License

This repository is licensed under the [Amazon License](https://aws.amazon.com/asl/).

## Resources

- [AWS Vector Stores for Retrieval Augmented Generative AI (Workshop Documentation)](link-to-workshop-docs)
- [AWS Documentation on Vector Stores](link-to-aws-docs)


This README provides an overview of the repository, instructions for getting started, and guidance on how to use the provided notebooks and code examples. It also includes information on contributing, licensing, and additional resources related to AWS vector databases and Retrieval Augmented Generative AI.