
# NLP to SQL Query Converter

## Description

This project demonstrates how to convert natural language queries into SQL queries using OpenAI's GPT- model. It allows users to interactively ask questions about a dataset and receive SQL queries as responses.

This project is aimed at data analysts, software developers, educators, business users, and anyone in need of querying databases. By converting natural language queries into SQL queries, it streamlines data analysis, facilitates application development, supports SQL education, empowers non-technical users to access data, and accelerates prototyping processes.

## Usage

1. **Clone the Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Install the required dependencies by running: `conda env create -f requirements.yml` and `pipenv install -r requirements.yml`.
3. **Set Up OpenAI API Key**: Obtain an API key from OpenAI and set it as an environment variable `OPENAI_API_KEY`.
4. **Run the Script**: Execute `main.py` to start the program. Follow the prompts to interactively ask questions about the dataset.

## Example Use Cases

- **Data Analysis**: Quickly generate SQL queries to analyze large datasets without needing to write SQL code manually.
- **Prototype Development**: Rapidly prototype applications that require querying databases based on natural language input.
- **Educational Purposes**: Teach SQL concepts by allowing users to experiment with natural language queries and observe the generated SQL.

## Dataset Information

The dataset used in this project is based on [Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data) from Kaggle. It contains information about sales transactions, including order number, quantity ordered, price each, order date, product line, customer details, and more.
