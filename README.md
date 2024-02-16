# Stock Price Reference Values and Sorting

# Idea:
A program that utilizes existing information and data sources on stocks and calculates reference values for their prices. These reference values can be used to analyze whether a stock is overvalued or undervalued.

# Background:
Predicting the development of stock values involves an uncertain amount of uncertainty factors. The most significant factors are the company's profitability and dividend policy, in addition to the future prospects of the company and its industry. In addition, the general economic situation, employment, inflation and interest rates have a strong impact on the entire market. Prices move according to future expectations. However, predicting future prices is difficult, and therefore market participants have built highly sophisticated systems to analyze and predict market developments. Market prices are formed on the basis of decisions made by people and systems created by people. Therefore, the volatility of the market is so high that it does not always have a real-world basis. The majority of changes in market values are explained by people's emotional behavior.
If investing in stocks is viewed purely analytically, then one could imagine that information about the value of a stock stripped of emotion and speculation could be useful in seeking optimal returns.
Another more important motive for this thesis topic is to practice building an AI application with my own hands.

# Data and AI Techniques:
Input data is retrieved from various sources such as trading systems of stock exchanges and brokers. The data is either entered manually or programmatically as input data and the industry and data elements to be processed can be selected. The linear regression coefficients are calculated from the training data based on daily prices, and the variance is adjusted to be reasonable on the test data. The reference prices of the desired set of securities are printed out and used for analysis.

# Intended Use:
The tool to be developed is intended to be a tool for making investment decisions. Instead of relying on the recommendation of "professionals" on undervaluation or overvaluation, the program calculates a reference value. In addition, the input parameters used can be changed to obtain different views. Similarly, stocks from a specific industry or stock exchange can be used as training material.
I plan to use the tool myself to analyze stock prices.

# Challenges:
The tool's data is based on existing information and is therefore not able to predict future developments. The tool is basically just a calculation tool and does not take into account market dynamics. Often, the price of an undervalued stock tends to continue to fall, and the price of an overvalued stock often only rises. The tool is not suitable for making investment decisions, although it does provide indications of the value of a stock.
The Building AI course did not provide enough information to build a functional user interface.

# Development Ideas:
Reading input data and selecting the data to be used from different sources could be made more automatic and the user interface smoother. The output could be made clearer. Some kind of game-like system would probably be ideal.
Neural networks could be used to compare previous and new results, which would allow simple trends to be predicted. Deep neural networks could even identify certain typical behavioral patterns such as the emergence of a turning point in the price and the reversal of the price.

# Acknowledgments:
In the prototype of the first version, I used Python commands that I had learned on the course, which were previously unknown to me.

