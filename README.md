# Extracting and Visualizing Stock and Revenue Data

This project involves the analysis of historical stock price and revenue data for Tesla and GameStop. The data was extracted using the `yfinance` and `requests` libraries, and then visualized using `pandas` and `plotly`. The project provides insights into stock trends and revenue performance through data visualization.

## Project Structure

The project is organized into several Python scripts, each performing a specific task:

1. **Data Collection**: The `yfinance` library is used to collect historical stock price data for Tesla and GameStop. The data is collected up to a specific date ('2021-06-14' for Tesla and '2021-04-30' for GameStop).

2. **Data Extraction**: The `requests` and `BeautifulSoup` libraries are used to extract historical revenue data from a specific webpage. The data is then cleaned and formatted into a pandas DataFrame.

3. **Data Visualization**: The `plotly` library is used to create interactive visualizations of the historical stock price and revenue data. The visualizations are displayed in a Jupyter Notebook and provide insights into the trends and performance of Tesla and GameStop.

## Methodology

The project follows a standard methodology for data analysis:

1. **Data Collection**: The `yfinance` library is used to collect historical stock price data for Tesla and GameStop. The data is collected up to a specific date.

2. **Data Extraction**: The `requests` and `BeautifulSoup` libraries are used to extract historical revenue data from a specific webpage. The data is then cleaned and formatted into a pandas DataFrame.

3. **Data Visualization**: The `plotly` library is used to create interactive visualizations of the historical stock price and revenue data. The visualizations are displayed in a Jupyter Notebook and provide insights into the trends and performance of Tesla and GameStop.

## Results

The project aims to provide insights into the historical stock trends and revenue performance of Tesla and GameStop. The insights are derived from the interactive visualizations of the data.

## How to Use

To run the project, clone the repository and run the Python scripts in the following order:

1. **Data Collection**: Run the script to collect the historical stock price data for Tesla and GameStop.

2. **Data Extraction**: Run the script to extract the historical revenue data from the webpage.

3. **Data Visualization**: Run the script to create the interactive visualizations of the historical stock price and revenue data.

## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue. If you'd like to contribute code, please fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was inspired by the Coursera course "Python Project for Data Analysis". The dataset used in this project was sourced from the Tesla Revenue 2010-2022 | TSLA history table.

## References

- [Coursera: Python Project for Data Science](https://www.coursera.org/learn/python-project-for-data-science)
- [Tesla Revenue 2010-2022 | TSLA](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm) 
- [Yfinance: Download Yahoo Finance data](https://pypi.org/project/yfinance/)
- [Requests: HTTP for Humans](https://docs.python-requests.org/en/latest/)
- [BeautifulSoup: Pull the data out of HTML and XML files](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Plotly: Python Graphing Library](https://plotly.com/python/)
