# Bitcoin-Risk-Analysis
# Bitcoin Market Performance & Volatility Analysis (2011–2020)

## Project Overview

An exploratory data analysis (EDA) project examining Bitcoin's historical market performance between 2011 and 2020. The analysis investigates long-term price growth, annual price movements, daily market volatility and the relationship between trading volume and Bitcoin prices.

The project uses Python to transform raw historical market data into meaningful insights that support a better understanding of cryptocurrency market behaviour.

## Business Problem

Bitcoin is characterised by significant price fluctuations, periods of rapid appreciation and market corrections. Understanding these movements is important for investors, financial analysts and market researchers assessing cryptocurrency performance and risk.

This project explores historical market data to identify significant trends, examine volatility and investigate the relationship between trading activity and price movements.

## Stakeholder Analysis & Investment Decision-Making
The findings can provide different forms of historical market intelligence depending on the stakeholder's investment objectives, risk tolerance and financial responsibilities.
**Banks and Financial Institutions Primary interests** - Financial stability, counterparty exposure, liquidity and risk management.
**Pension Funds and Institutional Asset Managers Primary interest** - Long-term capital preservation, diversification and risk-adjusted returns.
**Active Traders and Short-Term Investors Primary interest**: Short-term price movements, market activity and trading opportunities.
**Long-Term Investors Primary interest**: Capital appreciation and long-term wealth accumulation.

## Business Objectives

- Evaluate Bitcoin's historical price performance over the 2011–2020 period.
- Identify years with the highest and lowest recorded prices.
- Examine daily price volatility and annual market fluctuations.
- Calculate Bitcoin's Compound Annual Growth Rate (CAGR).
- Investigate the relationship between average trading volume and average price.
- Identify historical patterns in trading activity and price movements.

## Key Business Questions

1. How did Bitcoin's price evolve between 2011 and 2020?
2. Which years recorded the highest and lowest annual prices?
3. Which periods experienced the greatest daily price volatility?
4. What was Bitcoin's CAGR over the nine-year analysis period?
5. Is there a measurable correlation between average annual trading volume and average Bitcoin price?
6. Do periods of increased trading activity coincide with significant price movements?

## Tools;

 **Python, Pandas, Matplotlib, Seaborn and Jupyter Notebook.**

## Analytical Methodology

1. **Data Preparation:** Imported historical Bitcoin data, inspected data quality, checked duplicates and missing values, and converted data types.
2. **Feature Engineering:** Extracted year and month features from transaction dates.
3. **Price Analysis:** Aggregated annual minimum and maximum prices and examined historical price movements.
4. **Growth Analysis:** Calculated the Compound Annual Growth Rate (CAGR).
5. **Volatility Analysis:** Examined daily percentage price changes across the analysis period.
6. **Volume Analysis:** Compared annual average trading volume against average Bitcoin prices.
7. **Correlation Analysis:** Evaluated the statistical relationship between trading volume and price.

## KEY FINDINGS-


## 1. Long-Term Price Growth (CAGR)

<img width="849" height="568" alt="bitcoin 3" src="https://github.com/user-attachments/assets/8e9b4d72-b06b-4943-86ea-cfb179785dcf" />


Bitcoin demonstrated substantial long-term price appreciation:

| Year | Annual Minimum Price |
|---|---:|
| 2011 | $0.30 |
| 2014 | $111.60 |
| 2017 | $785.40 |
| 2020 | $4,826.00 |

The minimum recorded price increased 372x between 2011 and 2014, 7x between 2014 and 2017, and 6x between 2017 and 2020.

**Business implication:** Historical performance suggests that investors who tolerated short-term volatility and maintained a 3–5-year investment horizon benefited from substantial long-term price appreciation. 

**Stakeholder recommendations:**
- **Long-term investors:** Consider Bitcoin only where they can tolerate substantial losses and maintain a long investment horizon.
- **Banks:** Treat Bitcoin as a high-risk asset; any exposure should be subject to strict capital, liquidity and risk controls.
- **Pension funds:** Avoid treating Bitcoin as a core holding because of its volatility and lack of predictable income. Prioritise diversified assets aligned with pension obligations.
- **Short-term traders:** Exercise caution because extreme price fluctuations create significant short-term loss exposure.

### 2. Market Volatility

In 2014, Bitcoin recorded a maximum daily increase of **+336%** and a maximum daily decline of **-57%**. This demonstrates substantial price volatility, with extreme upward and downward movements.

**Business implication:** Bitcoin presents considerable market risk. Investors should assess their risk tolerance, potential losses and investment horizon before taking exposure.

### 3. Trading Volume vs Price

The **correlation** between average annual trading volume and average annual Bitcoin price was **0.95**, indicating a very strong positive relationship. As average trading volume increased, average Bitcoin prices also tended to increase.

<img width="699" height="568" alt="bitcoin 2" src="https://github.com/user-attachments/assets/d6e0660f-e355-4451-aee6-965ec2afa6e8" />


**Business implication:** Trading activity provides useful information about historical market behaviour and price movements. 

## . Conclusion AND Recommendation

The analysis identifies Bitcoin as a historically high-growth but highly volatile asset between 2011 and 2020.
Its historical price appreciation may interest long-term investors, while its volatility, lack of predictable income and potential for substantial losses create challenges for banks and pension funds.

** Investment decisions should therefore consider risk tolerance, liquidity requirements, portfolio diversification and investment objectives rather than historical returns alone.

## Business Value

The analysis provides a historical perspective on cryptocurrency market performance, highlighting growth patterns, price volatility and trading activity.
It demonstrates how data analytics can transform raw financial market data into structured insights that support financial research, market evaluation and evidence-based decision-making.

## Project Scope & Limitations

- Analysis covers historical Bitcoin data from 2011 to 2020.
- CAGR represents historical growth and does not imply consistent annual returns.
- Correlation does not establish causation.
- Findings are descriptive and exploratory, not predictive.
- The analysis does not constitute investment advice.
