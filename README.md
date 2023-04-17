# Introduction: *Volatility, Complexity*
Over the past century, the stock market has witnessed a series of dramatic events, such as market crashes like the Great Depression and the 2008 Financial Crisis, market booms like the Roaring 20s and the tech stocks of the 1990s, and unique occurrences like the 1987 stock crash due to automated trading and the 2000 Dot-Com Bubble.

In recent years, particularly since the onset of the COVID pandemic, the stock market has become increasingly volatile. Approximately 80% of traders fail to profit from the market. Consequently, it is crucial to acquire a solid understanding of finance fundamentals, encompassing financial terminologies, models, and patterns in the stock market, in order to best seize opportunities and mitigate risks present in the market.

Simultaneously, the financial tutorials available online often prove to be either confusing or overly complex for beginners to comprehend. These resources are not typically tailored to the needs of middle school, high school, or even college students who are not majoring in finance. As most financial terminology and concepts are interconnected, it emphasizes the importance of learning them in a logical sequence.

# Overview
**Aspect is a website that gamifies finance learning by creating a virtual stock market, allowing users to familiarize themselves with terminology and models, analyze stocks, simulate trades, and engage in competition.** The game is scenario- and event-driven, offering users a platform to explore trading strategies that suit them and optimally help them capitalize on market opportunities while avoiding market risks.

Unlike existing market simulators, Aspect's stock market is virtual and independent of the current real-world stock market. Indeed, the Aspect stock market features intense events, implying frequent and significant price fluctuations. This grants users the opportunity to experience trading during special market events, such as major stock crashes or booms, within a matter of weeks.

Users can also develop financial literacy while participating in the market game. The website offers around 100 comprehensive articles on financial concepts and terminology, divided into seven sections: Accounting, Valuation, Trading, Portfolio Management, De-Fi, ESG, and others. The terminologies are vital to the game, as users will be consistently reminded of the terms as the game progresses. A thorough understanding of these terms and concepts is essential for achieving high returns in the Aspect stock market by the end of each season. Additionally, learning this terminology prepares users to conduct financial analyses independently and apply the models to assist in real-world stock market trading.

# Mission
Aspect's mission is to reduce the barriers to entry into the finance world for young investors interested in the field. We aim to create an interactive environment where players can learn the fundamentals of finance, engage in discussions with peers, and experiment with the dynamic stock market.

# Vision
Aspect strives to create a virtual stock market featuring engaging companies and market events that mirror the real world. By doing so, we aim to simulate the experience of trading during extraordinary market events, thereby preparing users for individual trading in the stock market.

# Terminologies and Theories: *Complex Concepts, Simple Explanations*
The website features approximately 100 terms, divided into seven categories: Accounting, Valuation, Trading, Portfolio Management, De-Fi, ESG, and others. These terms will provide users with a basic understanding of fundamental analysis, technical analysis, risk management, types of financial securities, and trading strategies that will assist with future investments in the real- world market.

All terminology is presented in simple and straightforward language, accompanied by numerous examples, graphics, and visualizations. The goal is to streamline the finance learning process through more logical and accessible materials.

An overview is provided for each of the seven sections within the terminology, indicating the recommended learning paths. Most sections commence with definitions of core terms and conclude with tutorials on applications, such as creating models related to the topic. Users can also utilize the search feature to locate specific terms. Under all terms, users can share their opinions and engage in discussions with each other in the comment section.

In the Aspect market game, the terms are linked to market events. Each week, several selected terms will be showcased to aid players in their trades for the following week.
# Aspect Market Overview: *Analysis Information, Make Decisions*
The game operates on a seasonal cycle, with each season featuring one or two central macroeconomic events. Additionally, individual companies continually experience various market and company-related events. While some events may result in a straightforward impact on the market price, other events may have influences that appear counterintuitive to users new to finance. However, every market phenomenon has a rationale behind it. The website provides numerous news articles, graphs, and statistics. By gathering sufficient market information and forming investment decisions based on their analysis, users will learn to seize market opportunities and manage sudden market risks. At the end of each season, the Aspect Development Team will release detailed explanations and analyses for all companies, elucidating the market trends, major events, and trading behaviors that transpired during the season.

## News
News is provided to keep users informed about events occurring in the market or within companies. Many news articles contain hints about future stock growth, while some present strong opinions. Users should discern valuable information concealed within each article and use it to form investment decisions.

## Graphs
Price graphs are offered in 3-minute, adjusted, and daily dimensions to depict the trend and movement of price changes. Visual representations of each company's core business, stock valuation, and fundamental strengths and weaknesses are also included. These dynamic graphics will aid users in evaluating stocks.

## Statistics
Statistics primarily focus on a company's financials across five dimensions: valuation, income, balance sheet, cash flow, and dividend. Online spreadsheet templates are available on Aspect to help users work with fundamental and statistical models when conducting financial, risk, and portfolio analyses.

# Aspect Price Architecture: *Pattern and Trends From Stochasticity*
The equilibrium price for the market and all individual companies at a given time is determined by supply and demand. The latest transaction price becomes the new equilibrium price at the next tick.

To teach users how to manage market opportunities and risks during exceptional events, the website features a price engine to control price fluctuations in Aspect. If no transactions occur at a given time, the equilibrium price will follow the price engine's output. There will always be shares available for purchase and sale at the price engine's output.

The price engine can generate groups of stock prices for virtual companies that adhere to fundamental financial patterns while reflecting reality. The Aspect Stock Price Simulator Engine categorizes factors that could affect stock prices into macroeconomic and unknown factors. Both elements change frequently throughout the time interval. The engine links the two factors by applying two distinct stochastic differential equations: the Ornstein–Uhlenbeck Process and the Geometric Brownian Motion. All price changes share the same distribution and are independent of one another.

The engine regards the abstraction of stock prices as different waves and modifies the waves based on their amplitude, period, and frequency. The daily price wave is combined with the mid-term price and then expanded to a per-second dimension.

Parameters used in the stochastic processes are derived from major historical financial events. The Aspect Development Team conducts research and analyses before selecting reference events. These events are related to the central themes during each season. The Aspect Stock Price Simulator Engine establishes a trading environment for users to test their investment strategies in a market characterized by intense and frequent events, thereby preparing them to handle stock booms and crashes in the real-world market in the future.
# Auction House Structure: *All Decisions Influence Market Trend*
Aspect stock market. By placing ask and bid orders in the auction house, users' demands and supplies alter the equilibrium price. When a user's pending order completes a transaction, the order's price becomes the new equilibrium price at the next tick.

In addition to users, trading bots coded with investment strategies are continually buying and selling in the market. Each instance of a trading bot employs a unique strategy that either mimics a specific type of investor or implements a statistical learning model for decision-making.

When a user places an order at a price that is neither the current equilibrium price nor the price engine's output, the order enters a pending state. As part of the auction house rules, users cannot accept each other's pending orders to prevent malicious actions such as cash transfers or cheating. However, they can accept orders placed by different bots. The bots in the market will also evaluate and accept users' pending orders.

Thus, user decisions modify the fluctuations of company prices, enhancing the interaction in the Aspect market game.
# Aspect Trading Bots: *Artificial Intelligence Bots Performance in Trading*
In the Aspect Stock Market, two types of trading bots are programmed. The core functions of these trading bots are: 1. Continuously placing ask and bid orders in the market to diversify price movement. 2. Evaluating orders placed by users and accepting the orders if requirements are met.

Bot Type One consists of instances of bots that adhere to economic gaming strategies, decision-making models, or commonly used technical trading strategies. Most strategies in Bot Type One are simple and straightforward, aiming to represent various aspects of investors present in the market.

Bot Type Two comprises AI bots with more advanced strategy models, primarily focusing on regression or classification-based statistical learning models. These strategies are more complex compared to Bot Type One and are commonly employed in high-frequency trading (HFT) and algorithmic trading. These bots aim to experiment with the performance of more complex statistical models in a stock market characterized by exceptional events, such as an economic crisis or a stock boom.

By processing market information, including historical prices, current prices, stock volumes, news, and financial statistics, the bots evaluate the situation based on their individual strategies and decide whether an order should be placed or accepted.

The bots serve to increase diversity and ensure fairness in the game.

# About The Production Team
Aspect was founded and developed by Avril Cui. The core production team comprises high school students from the United States, the United Kingdom, and China, who work on marketing and product management.

We would like to extend special acknowledgment to Xuduo Wang, who contributed to the brainstorming and structuring of the terminology and news sections, and Daniel Yelamos, who provided valuable guidance on the product development process.
