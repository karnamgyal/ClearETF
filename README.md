# ClearETF

### ETF Transparency with Machine Learning and NLP

ClearETF explores how NLP through Transformer models can help make ETF data clearer and more interpretable.
The project focuses on analyzing company descriptions within ETFs to identify broader investment themes such as AI, healthcare, or energy.
It combines ONNX optimization, AWS deployment, and SQL-backed analytics to help investors better understand fund composition.

## Project Overview

- ClearETF reads ETF holdings, retrieves company information, and uses NLP to classify each company’s description into a theme.
- A fine-tuned Transformer model predicts these themes from financial text.
- Results are visualized through a Streamlit interface and logged in a Postgres database for analysis.

## Technologies

- NLP and Transformers (PyTorch) for theme classification

- ONNX Runtime for optimized model inference

- Streamlit for the web interface

- AWS ECS, ECR, and RDS (Postgres) for deployment and data storage

- SQL for analytics and caching

- GitHub Actions for CI/CD automation

## Project Status

- ClearETF is in early development.
- Data retrieval and initial setup are complete.
- Model fine-tuning, ONNX export, and AWS deployment are in progress.
