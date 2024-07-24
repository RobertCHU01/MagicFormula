# MagicFormula
This repository introduces the Magic Formula investment method developed by Joel Greenblatt in "The Little Book That Beats the Market", and provides code to implement this strategy.

## What is Magic Formula
Magic Formula aims to identify high-quality companies trading at attractive valuations by ranking stocks based on two key factors: **Return on Capital (ROC)** & **Earnings Yield**.

### Ideas of Magic Formula
Magic Formula looks for a stock with both a high ROC and a high Earnings Yield. 


In this way, we are buying a "good quality" stock at a "low price". However, the real implementation of Magic Formula is more complex, because we usually want a basket of stocks to reduce risks. This involves selecting the top 30 stocks, selecting from large/small companies, and renewing our formula every month... One thing to keep in mind is Magic Formula only shows its magic in the long term and investment is never short-time gambling, so if your magic formula does not perform well, stick to it!!! and See what happens in 5-6 years.

### Two Indicators in the Magic Formula
To understand the idea of Magic Formula, we first need to learn two financial concepts--**Return on Capital (ROC)** & **Earnings Yield**.

#### Return on Capital (ROC)
ROC measures how efficiently a company generates profits from its capital.


$$ROC\ =\ EBIT\ /\ (Net\ Working\ Capital + Net\ Fixed\ Assets)$$


* EBIT = Earnings Before Interest and Taxes
* Net Working Capital = Current Assets - Current Liabilities
* Net Fixed Assets = Total Fixed Assets – Accumulated Depreciation

Why use ROC instead of other indicators?


EBIT in the numerator:
1. Eliminates distortions from different tax rates and debt levels.
2. Allows for fair comparison of operating earnings across companies


(Net Working Capital + Net Fixed Assets) in the denominator:

1. Focuses on tangible capital employed in the business.
2. Excludes excess cash and goodwill, providing a more accurate picture of capital needed to run the business
3. More representative than total assets (used in ROA) or equity (used in ROE)



#### Earnings Yield
Earnings Yield is a valuation metric that indicates how much a company earns relative to its market value.


$$Earnings\ Yield\ =\ EBIT\ /\ Enterprise Value$$


* Enterprise Value = Market Capitalization + Debt - Cash

Why use Earnings Yield instead of other indicators?

Uses EBIT instead of net income:

1. Eliminates distortions from different tax rates and debt levels


Uses Enterprise Value instead of Market Capitalization:

1. enterprise value takes into account both the principal value of stock owed to purchase a business and the amount of debt a company takes on in order to generate operating income.



By combining these two indicators, the Magic Formula aims to identify companies that are both highly profitable (high ROC) and undervalued (high Earnings Yield).


## Getting Started

### Start with the Financial Statement
Here are some websites to look at large companies' financial statements.

[Apple](https://investor.apple.com/investor-relations/default.aspx)  
[Nike](https://investors.nike.com/investors/news-events-and-reports/investor-news/investor-news-details/2023/NIKE-Inc.-Reports-Fiscal-2024-Second-Quarter-Results/default.aspx)  
[Coco Cola](https://investors.coca-colacompany.com/financial-information/balance-sheet)  
[Thermo Fisher Scientific Inc](https://ir.thermofisher.com/investors/financials/quarterly-results/default.aspx)  


