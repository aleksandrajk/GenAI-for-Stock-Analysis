# GenAI for Stock Portfolio Analysis and Optimization

This project leverages Generative AI (GenAI) to analyze historical stock data and optimize investment portfolios. It integrates financial data retrieval, modern portfolio theory, and advanced optimization techniques to help in constructing efficient stock portfolios.

## Project Explanation
The core idea behind this project is to apply computational methods to traditional stock analysis and portfolio management. Here's a breakdown of what the notebooks achieve:

* **Data Acquisition**: The project utilizes the `yfinance` library to download historical stock data for a diverse set of assets, including major tech companies (Apple, Amazon, Alphabet, Meta, Microsoft, Nvidia, Tesla), Bitcoin, and the S&P 500 index.

* **Portfolio Optimization**: It employs the `PyPortfolioOpt` library, which implements various portfolio optimization techniques. Specifically, the `Final_Optimize_Stocks_with_GenAI.ipynb` notebook demonstrates the use of the Black-Litterman model for portfolio optimization. This model allows for incorporating investor views into the market equilibrium to generate more robust portfolio allocations.

* **Performance Metrics**: After optimization, the project calculates key performance indicators for the proposed portfolio, such as:
    * Expected Annual Return: The anticipated return over a year.
    * Annual Volatility: A measure of the portfolio's risk or price fluctuations.
    * Sharpe Ratio: A metric that indicates the risk-adjusted return of an investment. A higher Sharpe Ratio is generally better, as it means higher returns for the same amount of risk, or the same returns for a lower amount of risk.

* **Generative AI Integration**: While the provided snippets show library installations for `langchain-openai`, suggesting an intent to integrate Generative AI, the direct application within the provided code is for setting up an API key and library installation. The broader scope of "GenAI for StockAnalysis" implies using GenAI for tasks like generating market insights, predicting trends, or enhancing investment strategies based on analyzed data, which would be a further development of this project.

## Project Structure
* `Final_Optimize_Stocks_with_GenAI.ipynb`: This notebook contains the complete implementation, including data fetching, cleaning, portfolio optimization using the Black-Litterman model, and performance evaluation. It shows successful portfolio optimization results.
* `GenAI_for_Stock_Portfolio.ipynb`: This notebook sets up the environment, defines the assets and timeframes for analysis, and prepares for the integration of AI models, possibly as a preliminary or alternative approach to portfolio optimization.
* `GenAI_for_Stock_Portfolio_Starter_File.ipynb`: This appears to be an initial file providing the basic structure or prompt for data downloading, serving as a starting point for the project.

## Technologies Used
* Python
* `yfinance` (for fetching historical stock data)
* `PyPortfolioOpt` (for portfolio optimization, including the Black-Litterman model)
* `langchain-openai` (for integrating Generative AI capabilities)

## Setup and Installation
To run these notebooks, you'll need to install the required Python libraries. You can do this by running the following commands in your environment:

```bash
!pip install langchain-openai yfinance PyPortfolioOpt

