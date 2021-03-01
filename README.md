# covid_disclosures

## COVID-19 Financial Statement Disclosures

*Using Natural Language Processing, including Topic Modeling and Sentiment Analysis techniques, created [Tableau Dashboard](https://public.tableau.com/profile/jason.dunleavy#!/vizhome/covid_disclosures/COVID-19FinancialStatementDisclosures?publish=yes) of COVID-19 Financial Statement Disclosures to identify and analyze trends*

---
### Motivation
In March 2020, the unfolding global coronavirus pandemic shut down the majority of the US economy. Business operations abruptly changed, leading to material business and accounting implications for firms. On June 23, 2020, the SEC released [CF Disclosure Guidance: Topic No. 9A](https://www.sec.gov/corpfin/covid-19-disclosure-considerations), highlighting the need to disclose material COVID-19 impacts.

For this project, financial statements (quarterly and annual) from all S&P 500 companies were web scraped. Paragraphs containing references to COVID-19 were inputted into the model. Topic modeling and sentiment analysis were performed to identify and analyze trends.

---
### Process
1. Obtain links to financial statements - [sec_urls.ipynb](https://github.com/dunleavyjason/covid_disclosures/blob/main/sec_urls.ipynb)
2. Web scrape financial statements - [web_scrape.ipynb](https://github.com/dunleavyjason/covid_disclosures/blob/main/web_scrape.ipynb)
3. Clean text - [clean_text.ipynb](https://github.com/dunleavyjason/covid_disclosures/blob/main/clean_text.ipynb)
4. Topic model and sentiment analysis - [topic_modeling_sentiment.ipynb](https://github.com/dunleavyjason/covid_disclosures/blob/main/topic_modeling_sentiment.ipynb)
5. Visualize data - [Tableau Dashboard](https://public.tableau.com/profile/jason.dunleavy#!/vizhome/covid_disclosures/COVID-19FinancialStatementDisclosures?publish=yes)

---

### Data Used
S&P 500 Info:
https://datahub.io/core/s-and-p-500-companies

Company CIKs/Tickers:
https://www.sec.gov/include/ticker.txt

Financial Statements (various):
https://www.sec.gov/edgar/searchedgar/companysearch.html


---

### Tools and Packages
1. Python
2. BeautifulSoup
3. Pandas
4. NumPy
5. matplotlip
6. seaborn
7. scikit-learn
8. [SEC API](https://sec-api.io/)
9. Tableau Public

