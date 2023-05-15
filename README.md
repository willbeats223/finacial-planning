# finacial-planning
Module 5 homework
1. Create two variables called `my_btc` and `my_eth`. Set them equal to `1.2` and `5.3`, respectively.

2. Use the `requests` library to fetch the current price in US dollars (`USD`) of bitcoin (`BTC`) and ethereum (`ETH`)

3. Parse the API JSON response to select only the crypto prices and store each price in a variable.


4. Compute the portfolio value of cryptocurrencies and print the results.

6. Create two variables named `my_agg` and `my_spy` and set them equal to `200` and `50`, respectively.

8. Set the Alpaca API key and secret key variables, then create the Alpaca API object using the `tradeapi.REST` function from the Alpaca SDK.

10. Format the current date as ISO format. You may change the date set in the starter code to the current date.

12. Get the current closing prices for `SPY` and `AGG` using Alpaca's `get_bars()` function. Transform the function's response to a Pandas DataFrame and preview the data.

14. Pick the `SPY` and `AGG` close prices from the Alpaca's `get_bars()` DataFrame response and store them as Python variables. Print the closing values for validation.

16. Compute the value in dollars of the current amount of shares and print the results.

18. Create a variable called `monthly_income` and set its value to `12000`.

20. create a DataFrame called `df_savings` with two rows. Store the total value in dollars of the crypto assets in the first row and the total value of the shares in the second row.
22. Use the `df_savings` DataFrame to plot a pie chart to visualize the composition of personal savings.
23. Use `if` conditional statements to validate if the current savings are enough for an emergency fund. An ideal emergency fund should be equal to three times your monthly income.
24. Use the Alpaca API to fetch five years historical closing prices for a traditional `40/60` portfolio using the `SPY` and `AGG` tickers to represent the `60%` stocks (`SPY`) and `40%` bonds (`AGG`) composition of the portfolio. Make sure to convert the API output to a DataFrame and preview the output.
25. Configure and execute a Monte Carlo Simulation of `500` runs and `30` years for the `40/60` portfolio.
26. Plot the simulation results and the probability distribution/confidence intervals.
27. 1. Fetch the summary statistics from the Monte Carlo simulation results.
28. Given an initial investment of `$20,000`, calculate the expected portfolio return in dollars at the `95%` lower and upper confidence intervals.
29. Calculate the expected portfolio return at the `95%` lower and upper confidence intervals based on a `50%` increase in the initial investment.
