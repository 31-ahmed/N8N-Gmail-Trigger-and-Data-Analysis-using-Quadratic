# Data Analysis with N8N Workflows and Quadratic AI

This repository provides a solution for automating data extraction, storage, and analysis using **N8N workflows** and **Quadratic AI**. The main goal is to efficiently extract data from Gmail, process it, and perform AI-based analysis using a streamlined, automated pipeline.

## Project Overview

The system is built using **N8N workflows** for automating data extraction from Gmail and integrating with **Postgres** for storage. The final part of the pipeline uses **Quadratic AI** for prompt-based analysis of the extracted data.

## Workflow

The workflow in this project consists of the following steps:

1. **Gmail Trigger**:  
   - The workflow starts by triggering events from a Gmail account, such as receiving specific emails or alerts.
   
2. **Data Extraction**:  
   - Data is extracted from the triggered emails in **JSON format** to standardize the data for further processing.

3. **Data Ingestion into Postgres**:  
   - The extracted data is ingested into a **Postgres database** for storage and further manipulation.

4. **Ingestion into Quadratic AI**:  
   - Once the data is in Postgres, it's ingested into **Quadratic AI** for advanced analysis.
   
5. **Prompt-Based Analysis**:  
   - Using Quadratic AI, the data undergoes **prompt-based analysis**, where insights and predictions are made based on the data.

## Technologies Used

- **N8N**: For building automated workflows to trigger Gmail actions and data flow.
- **Gmail API**: For email data extraction.
- **Postgres**: For database management and storage.
- **Quadratic AI**: For prompt-based machine learning analysis.

## Getting Started

### Prerequisites

1. **N8N**: Ensure N8N is set up on your system for creating workflows.
2. **Postgres**: Install Postgres and set up the database.
3. **Quadratic AI**: Access to Quadratic AI API or setup for prompt-based analysis.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/repository-name.git
   cd repository-name
