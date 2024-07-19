# Machine Learning Model for Nubank Data Analysis

## Project Overview

This project involves a brief analysis of Nubank, data exploration, and the creation of machine learning models. One model is based on a fictitious or encrypted dataset, and another model is based on the bank's stock value since its IPO. 
The models and analyses are contained within Jupyter Notebooks and are also presented in a Streamlit app for enhanced visualization.

Feel free to explore more on [Streamlit](https://nubank.streamlit.app/).

## About Nubank

Nubank is a Brazilian neobank headquartered in São Paulo, Brazil. Founded in 2013, it is considered the largest digital bank in the world outside of Asia and one of the largest fintech companies in Latin America. In 2019, it was recognized as one of the most innovative companies in the world by the American magazine Fast Company.

In just six years, Nubank became the sixth-largest bank in Brazil, ranking among the top five credit card issuers and reaching 20 million customers by early 2020. Between mid-2018 and the end of 2019 (according to a study by Apptopia), its app was downloaded more times than the top three neobanks in Europe combined.

## Project Structure

- **data**: Contains the dataset used for analysis.
  - Financial information is available on the bank's website for its investors.
  - The information contained in the dataset is fictitious and/or encrypted.
- **models**:
  - Python Machine Learning Model: Exported in PKL format for loading and use on the page.
  - Azure Machine Learning Model: Loaded via API. May not function in all interactions due to paid traffic and potential deactivation.
  - Time Series Model: Utilizes historical daily closing prices of the bank's stock to forecast the next three business days.
- **streamlit_app**: Houses the Streamlit application for interactive analysis.
- **notebooks**: Jupyter notebooks for exploratory data analysis and model development.


