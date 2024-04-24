# Stocks Dashboard with R flexdashboard

## Summary of Project
- Main aim of this dashboard is to develop a useful dashboard that allows investors and traders to sort through the many individual securities to find those that fit their own methodologies.
- Cleaned sets of data were already provided which we just had to merge and filter to get the relevant figures.
- This was a pair work which both of us contributed to all parts of the dashboard. The parts which I mainly contributed to were the Excess Returns, Industries and Company Comparison pages.

## Project Details
### Dashboard Pages
There are six pages in the dashboard:
1. Stock Screener
2. Capital Structure
3. Excess Returns**
4. Industries**
5. Risk Premium
6. Company Comparison**

** The pages which are created my me. I have also helped out in the ideation and implementation of the rest of the pages.

## Diving into each Page
The creation of charts comprises the use of the ggplot2 and highcharter library. Highcharter being one of my favourite visualisation libraries as it creates highly interactive, web-based visualizations.

### 1.Stock Screener
The first page serve as a starting point for investors who have little clue what stocks they want to invest in. The user can easily filter for stocks based on the factor which are most important to them and browse other of the stocks' relevant information.
  <img width="1459" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/4167d388-6f53-427e-8b1e-403f6fb3e495">


For users who are looking for a safe bet, they can find out the current top companies in our next three pages based on capital structure, excess return and the industry the company is in.

### 2. Capital Structure
It shows the top 10 companies based on capital structure. Capital structure plays a crucial role in investments and stocks in the numerous ways. It determines the company's financial risk and cost of capital, signals the company's growth prospects and management's confidence, impacts the company's ability to pay dividends, and etc.
Users can use the the dropdown selection to input filter criteria and the search result will be displayed in the table.
   <img width="1452" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/42fe9d8c-7fc1-4228-bad3-6110f30e08b5">

### 4. Excess Return
This page shows the top 10 companies based on excess return. In short, excess returns measure the value added by active investment strategies over a benchmark. Investors usually seek companies/portfolios that generate positive excess returns, as it helps distinguish skillful investments from those merely following market trends.

Users can easily filter for top companies based on the performance indicator which are is important to them and further drill down by industry and number of companies they want to see.
   <img width="1463" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/6bd0c62f-e0f8-460e-94d6-119d80b891e4">

### 5. Industries
Investor sentiment towards a particular industry can drive demand and stock prices for companies in that industry. Diversification across different industries helps mitigate industry-specific risks in a portfolio. Users looking to "put eggs in different baskets" may find this page useful.

Users can easily filter for top companies based on the performance indicator which are is important to them and select the number of top companies they want to see.
   <img width="1462" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/2f749f48-3d46-4942-ad4b-ea19a86ed569">
   
### 6. Risk Premium
Risk premium is the additional return an investor expects to receive for taking on higher risk investments compared to risk-free assets like government bonds. The chart serves to complement the previous three pages in helping investors determine if the potential return historically justifies the risk taken for a particular investment.
   <img width="1460" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/741184d6-eb37-461a-9945-da152a300e29">

### 7. Company Comparison
For users who might already or not be investing this page would serve useful to compare how each stock fare against another. It narrows down the stocks to those which the investor is keen to or already purchased and compare them by the various performance indicators to make an informed decision or compare their performance.

Besides the chart which provides a visual representation, the table below provides a side by side comprehensive detail of the selected stocks for ease of comparison.
   <img width="1462" alt="image" src="https://github.com/tltxyyy/Stocks-Dashboard/assets/69724535/f9a1d1e4-9360-473a-931e-8d01c6590411">


