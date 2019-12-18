[👉 Link to Presententation slides](https://docs.google.com/presentation/d/109jzeLPztlVUxcaFIfiLQABuF6tHNojmpO3DbngiKeE/edit?usp=sharing)

## My Design draft

#### Question/need: 
As a tabletop game developer, what can I do to raise the maximum amount of money for my next tabletop game project with a crowdfunding campaign on Kickstarter?

#### Description of my sample data:
I scraped data about projects in the Tabletop Games category from Kickstarter search results, as well as corresponding project, rewards, and creator pages.

#### Techniques applied
This is an exploration of regression, regularization, and web scraping:
 - Scraping with Selenium and BeautifulSoup 
 - Linear regression with polynomial features, LASSO and Ridge regularization, and k-fold cross validation
 - metrics, such as R^2, mean absolute error and mean squared error
 - visualization techniques such as pairplots, residual plots

#### Future Work
- explore other regresssion models
- try time series forecasting using Wayback Machine data
- I pulled descriptive data about the games from BoardGameGeek's search API by using the Kickstarter game name as a query. Looking into whether this can be mined for features...
