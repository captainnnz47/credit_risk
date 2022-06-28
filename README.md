# credit_risk
This is a SAS project in credit risk based on data from Canadian banks.
"Credit Data Structure and Realized LGD Calculation"
Achieve two goals:
  1. Calculate the realized LGD based on the three tables, assuming an annual discount rate of 10%.
  2. Find the differences in realized LGD among facilities with various collateral type, and with/without guarantee.
----------------------------------------------------------------------------
Credit Risk Management

1. Trading Book vs. Banking Book
  The trading book is an accounting term that refers to assets held by a bank that are regularly traded. The trading book is required to be marked to market daily (mainly subject to Market Risk)
  The banking book is also an accounting term that refers to assets on a bank's balance sheet that are expected to be held to maturity. Banks are not required to mark these to market (mainly subject to Credit Risk)
  
2. Credit risk is quantified at both the individual obligor and portfolio levels to manage expected credit losses(ECL) and minimize unexpected losses in order to limit earnings volatility and ensure we are adequately capitalized.

3. The wholesale portfolio is comprised of businesses, sovereigns, public sector entities, banks and other financial institutions, as well as certain individuals and small businesses. The retail portfolio is comprised of residential mortgages, personal loans, credit cards, and small business loans.

----------------------------------------------------------------------------
Credit Risk Parameters

1. Probability of default(PD): An estimated percentage that represents the likelihood of default within a given time period of an obligor for a specific rating grade or for a particular pool of exposure.

2. Exposure at default(EAD): An amount expected to be owed by an obligor at the time of default.

3. Loss given default(LGD): An estimated percentage of EAD that is not expected to be recovered during the collections and recovery process.

4. IFRS9: Allowance for Credit Loss(ACL) - an unbiased estimate of expected credit losses on our financial assets as at the balance sheet date
    Stage 1 - no significant increase in credit risk since initial recognition. A loss allowance is recognized using 12 months PD following the reporting date
    Stage 2 - significant increase in credit risk since initial recognition. A loss allowance is recognized using lifetime PD
    Stage 3 - When a financial asset is considered to be credit-impaired. A loss allowance is recognized using PD = 1

----------------------------------------------------------------------------
Measurement of Credit Risk

Financial and regulatory distinctions. Two different sets of Credit Risk Parameters (PD/LGD/EAD) are used for regulatory capital(Basel) and accounting(IFRS 9) purposes.
    Basel PDs are based on long-run averages over an entire economic cycle. IFRS 9 PDs are based on current conditions, adjusted for estimates of future conditions that will impact PD under macroeconomic scenarios.
    Basel PDs consider the probability of default over the next 12 months. IFRS 9 PDs consider the probability of default over the next 12 months and lifetime PDs.
    Basel LGD/EADs reflect plausible downturn economic conditions. IFRS 9 LGDs are based on current conditions, adjusted for estimate of future conditions that will impact LGD/EAD under macroeconomic scenarios.

