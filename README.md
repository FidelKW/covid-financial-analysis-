# Impact of COVID-19 on U.S. Financial Markets

## Project Overview

This project aims to conduct a comparative analysis of various asset metrics due to the impacts of the COVID-19 pandemic on the performance of the US financial markets. The analysis considers three distinct periods: Pre-COVID, During-COVID, and Post-COVID.

## Asset Classes Analyzed

- Equities (S&P 500)
- Commodities (Crude oil and Gold)
- Currencies (USD/EUR)
- Cryptocurrencies (Bitcoin)
- Bonds (US Treasury yield - 10-year)

## Objectives

1. **Data Extraction:** Fetch historical price data for the selected assets.
2. **Data Preprocessing:** Clean and prepare the data for analysis.
3. **Exploratory Data Analysis (EDA):** Visualize trends and derive insights.
4. **Hypothesis Testing:** Test for statistical significance of observed differences in returns, volatility, and correlations.
5. **Predictive Modeling and Volatility Assessment:** Use ARIMA and GARCH models.
6. **Portfolio Strategy Development:** Propose strategies for mitigating systemic risk.
7. **Findings and Recommendations:** Summarize key findings and provide recommendations.

## Files

- `covid_financial_analysis.ipynb`: Jupyter Notebook containing the analysis code.

## Getting Started

1. Clone this repository: `git clone <https://github.com/FidelKW/covid-financial-analysis->`
2. Install necessary libraries: `pip install -r requirements.txt`
3. Open and run the `covid_financial_analysis.ipynb` notebook in Google Colab or Jupyter.

## Results and Insights

## Impact of COVID-19 on U.S. Financial Markets: A Statistical and Predictive Analysis

### Key Findings:

**Market Volatility:**

- The COVID-19 pandemic induced a significant surge in market volatility across most asset classes, with crude oil experiencing a particularly sharp spike. While volatility has subsided post-pandemic, it remains elevated compared to pre-pandemic levels.

**Return Distributions:**

- While short-term returns exhibited heightened fluctuations during the pandemic, long-term mean returns remained relatively stable. Notably, equities (S&P 500) and crude oil showed wider return dispersions during the pandemic period.

**Cross-Asset Correlations:**

- The pandemic led to shifts in cross-asset correlations. Bitcoin and equities (S&P 500) demonstrated an increased positive correlation, while gold and US Treasury yields maintained a negative correlation, albeit with fluctuations in strength.

**Portfolio Risk:**

- Portfolio risk, measured by variance, spiked sharply during the pandemic's initial phase. While it has since decreased, it hasn't reverted to pre-pandemic levels, suggesting potential structural changes in market dynamics.

**Statistical Significance:**

- Hypothesis testing confirmed significant differences in volatility across periods for all assets. Notably, the correlations between certain asset pairs, such as equities (S&P 500) and Bitcoin, and equities and US Treasury yields, experienced significant shifts.


### Conclusion:

The COVID-19 pandemic had a profound impact on US financial markets, triggering heightened volatility, altering correlation dynamics, and impacting portfolio risk. While markets have shown signs of stabilization post-pandemic, some changes may be enduring, requiring investors to adapt strategies for risk mitigation and portfolio optimization.

### Additional Information:

The analysis covered equities, commodities, currencies, cryptocurrencies, and bonds.
Statistical tests, including ANOVA, Levene's test, and Fisher's Z-test, were employed to assess the significance of observed changes.

![image](https://github.com/user-attachments/assets/047e9b8d-6a2f-4769-959a-9d334aa6c499)

![image](https://github.com/user-attachments/assets/81740b3c-0200-482c-a44e-cb691148ff80)

![image](https://github.com/user-attachments/assets/653227b4-dbe5-44dd-8b3d-54933ab9fd19)

![image](https://github.com/user-attachments/assets/6ca0fd60-9d81-4bc1-8436-8d0c3f1237bd)

![image](https://github.com/user-attachments/assets/0a70d92a-28ad-406e-b84e-dd4393a06174)

## Future Work

### 1. Alternative Econometric and Machine Learning Models

ARIMA and GARCH models are widely used in financial time-series forecasting but have limitations in capturing nonlinear patterns. Future studies could:

**1. Explore Hybrid Models:** Combine ARIMA-GARCH with deep learning models (e.g., LSTMs, transformers) to improve prediction accuracy.

**2. Regime-Switching Models:** Apply Markov Switching Models to identify changes in asset behavior across different economic phases.

**3. Causal Inference Techniques:** Use Difference-in-Differences (DiD) or Structural Vector Autoregression (SVAR) to assess causality rather than just correlation.

### 2. Alternative Data Sources for Market Analysis

Traditional financial analysis relies on asset prices, but incorporating alternative data could enhance insights. Future research could:

**1. Sentiment Analysis from News and Social Media:** Examine how investor sentiment influenced asset performance.

**2. High-Frequency Data Analysis:** Use intraday market data to detect short-term volatility spikes during crisis periods.

**3. Google Search Trends and Mobility Data:** Explore how real-world behavioral shifts impacted financial markets.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

BSD 3-Clause License

Copyright (c) 2025, Fidel Wafula

All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

* Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Contact

Name: Fidel Wafula

E-mail: fdlwafula12@gmail.com
