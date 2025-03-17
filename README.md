This project uses Monte Carlo Simulations to simulate daily returns of an investment portfolio. An optimal portfolio of two different stocks from a list of five stocks('DIS','HPQ','USO','DVN','LMT') is found by calculating the minimum risk weights and returns of the possible pairs. 
`getsymbols` function of the `quantmod` library is used to get the stock values. The daily return values of each stocks are found using diff()/lag() of the closing prices. Further, the mean and standard deviations of these daily returns is used for finding the simulated returns using Monte Carlo Simulation.

