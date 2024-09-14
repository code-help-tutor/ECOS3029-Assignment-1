# ECOS3029: Assignment 1

**1) [9 marks] National Accounts Exercise**
Suppose that the value of national account aggregates in China for a year are:
Exports of goods and services: ¥250;
Imports of goods and services: ¥160;
Private consumption expenditure: ¥300;
Government consumption expenditure: ¥100;
Government tax revenues: ¥150;
Investment: ¥200;
Income received from foreign investments: ¥50;
Income paid to foreign investors: ¥50.

a) [3 marks] If the above list of transactions is complete, what is the Trade Balance for China as a % of Chinese Gross National Income (GNI), correct to at least 1 decimal place?
The trade balance is exports minus imports. So, trade balance = ¥250 - ¥160 = ¥90.
Gross National Income (GNI) = Private consumption expenditure + Government consumption expenditure + Investment + (Exports - Imports) + Income received from foreign investments - Income paid to foreign investors.
GNI = ¥300 + ¥100 + ¥200 + ¥90 + ¥50 - ¥50 = ¥690.
Trade balance as a percentage of GNI = (¥90 / ¥690) * 100 ≈ 13.0%.

b) [3 marks] What is the Current Account Balance for China as a % of Chinese GNI, correct to at least 1 decimal place?
Current account balance = Trade balance + Net income from abroad.
Net income from abroad = Income received from foreign investments - Income paid to foreign investors = ¥50 - ¥50 = 0.
So, current account balance = ¥90 + 0 = ¥90.
Current account balance as a percentage of GNI = (¥90 / ¥690) * 100 ≈ 13.0%.

c) [3 marks] What is the value of total savings in the economy?
Total savings = GNI - Private consumption expenditure - Government consumption expenditure.
Total savings = ¥690 - ¥300 - ¥100 = ¥290.

**2） [25 marks] Intertemporal Model**
Assume that a small open economy runs for 2 periods and has production, investment, and a representative consumer with:
• Lifetime utility function: \(U = ln(c_1) + ln(c_2)\)
• Production function: \(y = k^{0.7}\) where the initial capital stock is \(k_1 = 200\)
• Capital Stock in Period 2: \(k_2 = k_1 + i_1\), where \(i_1\) is period-1 investment
• Access to international credit markets at an interest rate \(r = 0.15\).
• \((1 + r) = 1\).
• Initial Net International Investment Position: \(NIIP_1 = 0\).

a. [3 marks] Write down the maximization problem for the representative consumer.
The maximization problem is to maximize lifetime utility \(U = ln(c_1) + ln(c_2)\) subject to the budget constraints.

b. [8 marks] Solve for the optimal investment level \(i_1\) for the economy in period 1.
The budget constraint for period 1 is \(c_1 + i_1 = y_1\).
Substituting the production function \(y_1 = k_1^{0.7}\) with \(k_1 = 200\), we get \(y_1 = 200^{0.7}\).
Let's call \(y_1 = Y\).
The budget constraint for period 2 is \(c_2 = y_2 - (1 + r)(k_1 + i_1 - k_2)\).
Substituting \(y_2 = k_2^{0.7}\) and \(k_2 = k_1 + i_1\), we get \(c_2 = (k_1 + i_1)^{0.7} - (1 + r)i_1\).
Maximizing \(U = ln(c_1) + ln(c_2)\) subject to \(c_1 + i_1 = Y\) and \(c_2 = (k_1 + i_1)^{0.7} - (1 + r)i_1\) using Lagrange multipliers.
Form the Lagrangian function \(L = ln(c_1) + ln(c_2) + \lambda(Y - c_1 - i_1)\).
Taking partial derivatives and setting them equal to zero gives a system of equations that can be solved to find the optimal \(i_1\).

c. [2 marks] What is the optimal investment level \(i_2\) for the economy in period 2?
Since \(k_2 = k_1 + i_1\) and there is no specific optimization problem for period 2 investment directly given, we assume \(i_2 = 0\) for simplicity (unless further constraints are provided).

d. [9 marks] Solve for optimal consumption levels for the economy in both periods.
Using the solutions for \(i_1\) from part b and the budget constraints \(c_1 + i_1 = y_1\) and \(c_2 = (k_1 + i_1)^{0.7} - (1 + r)i_1\), we can find the optimal consumption levels \(c_1\) and \(c_2\).

e. [3 marks] What is the current account balance of the economy in Period 1? What are total savings in the economy in Period 1?
Current account balance in period 1 is equal to savings in period 1. Savings in period 1 is \(y_1 - c_1 - i_1\). Total savings is also the same value.

**3) [18 marks] Sudden Stops and Current Account Reversals**
Consider the data for a country in the table below. All parts to this question are worth 3 marks each.
| Year | Current Account Balance (% of GDP) | Investment (% of GDP) | Productivity Index (2009=100) | Imports (% of GDP) | Exports (% of GDP) | Exchange Rate (local currency units per USD) |
| ---- | ---------------------------------- | -------------------- | -------------------------- | ----------------- | ----------------- | ------------------------------------------- |
| 2009 | -16.2 | 37.2 | 100.0 | 122 | 107 | 2.44 |
| 2010 | -14.0 | 34.7 | 108.6 | 127 | 118 | 2.44 |
| 2011 | -15.6 | 37.5 | 113.3 | 164 | 149 | 2.44 |
| 2012 | -13.4 | 34.9 | 116.1 | 146 | 137 | 2.44 |
| 2013 | -12.0 | 35.0 | 123.1 | 159 | 149 | 2.44 |
| 2014 | -10.5 | 33.2 | 129.7 | 169 | 163 | 2.44 |
| 2015 | -9.0 | 34.6 | 138.1 | 170 | 165 | 2.44 |
| 2016 | -10.9 | 35.6 | 149.4 | 190 | 185 | 2.44 |
| 2017 | -13.1 | 39.5 | 162.4 | 209 | 202 | 2.44 |
| 2018 | -11.1 | 42.1 | 171.5 | 203 | 198 | 2.44 |
| 2019 | -8.9 | 45.8 | 175.8 | 187 | 185 | 2.44 |

a. Do you think it is optimal for this country to be running current account deficits (briefly explain your answer)?
Running current account deficits may not be optimal in the long run. It indicates that the country is spending more on imports and investment than it is earning from exports and other sources. This can lead to a build-up of debt and make the country vulnerable to external shocks. However, in the short term, it may be acceptable if the investment is expected to generate future growth and the deficits are financed in a sustainable way.

b. What features of this data suggest that there is an increased likelihood of this country experiencing a “sudden stop” of capital inflows and a current account reversal (briefly explain your answer)?
High investment levels relative to GDP and persistent current account deficits suggest an increased likelihood of a sudden stop. If the country is relying on capital inflows to finance its investment and deficits, a sudden stop in these inflows could lead to a significant adjustment in the economy.

c. What features of this data suggest a low likelihood of a “sudden stop” of capital inflows and a current account reversal (briefly explain your answer)?
Steady growth in productivity index may suggest a low likelihood. If productivity is increasing, it may lead to increased exports and reduced dependence on capital inflows, making the economy less vulnerable to a sudden stop.

d. If the country were to experience a current account reversal, do any features of the data suggest that the economic growth impact would be less substantial than normally occurs during such a reversal (briefly explain your answer)?
If the productivity index continues to grow, it may mitigate the negative impact of a current account reversal on economic growth. Higher productivity can lead to increased output and exports, which could help offset the reduction in imports due to the reversal.

e. If the country were to experience a current account reversal, do any features of the data suggest that the economic growth impact would be more substantial than normally occurs during such a reversal (briefly explain your answer)?
If the country has a high level of investment and a large share of imports in GDP, a current account reversal could have a more substantial impact on economic growth. Reduced imports could lead to a significant decline in investment and production, especially if the country is highly dependent on imported inputs.

f. Is there any other data you would like to observe to be able to better assess the likelihood of a sudden stop of capital inflows and a current account reversal (briefly explain your answer)?
Data on external debt levels, terms of trade, and the composition of capital inflows would be useful. High external debt levels increase the risk of a sudden stop. Changes in terms of trade can affect exports and imports. The composition of capital inflows (e.g., short-term vs. long-term) can also determine the vulnerability of the economy to a sudden stop.

**4) [19 marks] Exchange Rates**
Report answers correct to at least 3 decimal places.

a. [2 marks] If the spot exchange rate \(USD/EUR = 0.15\), then what is the spot exchange rate \(EUR/USD\)?
The reciprocal of \(USD/EUR = 0.15\) is \(EUR/USD = 1/0.15 ≈ 6.667\).

b. [2 marks] If the spot exchange rate \(USD/GBP = 1.05\), and the spot exchange rate \(USD/EUR = 1.25\), what is the spot exchange rate \(GBP/EUR\)?
\(GBP/EUR = (USD/EUR)/(USD/GBP) = 1.25/1.05 ≈ 1.190\).

c. [2 marks] If the spot exchange rate \(USD/AUD = 4.75\), and the spot exchange rate \(USD/CAD = 0.75\), what is the spot exchange rate \(AUD/CAD\)?
\(AUD/CAD = (USD/CAD)/(USD/AUD) = 0.75/4.75 ≈ 0.158\).

d. [4 marks] Assume that you are an investor with 1,000 USD in an account and observe the following spot exchange rates: \(USD/EUR = 0.75\), \(USD/GBP = 0.8583\), \(USD/AUD = 1.1452\). Assuming that there are no transaction costs, what foreign exchange trading/investment strategy would you adopt?
To determine the best trading strategy, we need to calculate the equivalent amounts in different currencies.
1000 USD = 1000/0.75 ≈ 1333.333 EUR.
1000 USD = 1000/0.8583 ≈ 1165.087 GBP.
1000 USD = 1000/1.1452 ≈ 872.242 AUD.
We can then compare these amounts to see which currency offers the most value. Depending on the comparison, we can decide whether to convert to a particular currency and then potentially back to USD at a later time to make a profit.

e. [2 marks] Assume that (i) the one-year forward exchange rate \(EUR/CHF = 1.0505\) (ii) the current spot exchange rate \(EUR/CHF = 1.0859\); and (iii) the one-year interest rate for EUR is \(r^{*} = 9.23\%\). What must one-year CHF interest rates be for Covered Interest Parity (CIP) to hold?
According to CIP, \((1 + r_{EUR})/(1 + r_{CHF}) = F/E\), where \(F\) is the forward exchange rate, \(E\) is the spot exchange rate, \(r_{EUR}\) is the interest rate for EUR, and \(r_{CHF}\) is the interest rate for CHF.
Rearranging the formula gives \(r_{CHF} = [(1 + r_{EUR})E/F] - 1\).
Substituting the given values, \(r_{CHF} = [(1 + 0.0923)*1.0859/1.0505] - 1 ≈ 0.131\) or 13.1%.

f. [3 marks] The current value of the spot exchange rate \(CAD/AUD = 1.05\). If the Canadian (CAD) inflation rate for the coming year will be 4% while the Australian inflation rate will be 2%, what value of the exchange rate \(CAD/AUD\) 1 year from now would maintain Relative PPP?
According to Relative PPP, the expected exchange rate change is equal to the difference in inflation rates.
Expected exchange rate change = (Inflation rate in CAD - Inflation rate in AUD).
Expected exchange rate change = 4% - 2% = 2%.
If the current exchange rate is \(CAD/AUD = 1.05\), then the expected exchange rate after one year would be \(1.05*(1 + 0.02) = 1.071\).

g. [3 marks] Assume that consumers consume only 2 items: Rent; Food. In Germany, rent for 1 year is EUR 15,000 and food for 1 year is EUR 7,500. In Australia, rent for 1 year is AUD 20,000 and food for 1 year is AUD 7,500. If the spot exchange rate is \(AUD/EUR = 1.616\), what is the real exchange rate between Australia and Germany (treat Australia as the domestic country)? At what value of the nominal exchange rate \(AUD/EUR\) would Absolute PPP hold?
The price level in Germany is \(P_{GER} = (15000 + 7500)/2 = 11250\) EUR.
The price level in Australia is \(P_{AUS} = (20000 + 7500)/2 = 13750\) AUD.
The real exchange rate is \(R = E\times(P_{AUS}/P_{GER})\), where \(E\) is the nominal exchange rate.
\(R = 1.616\times(13750/11250) ≈ 2.064\).
For Absolute PPP to hold, the nominal exchange rate would be \(E = P_{GER}/P_{AUS}\).
\(E = 11250/13750 = 0.818\).

# ECOS3029 Assignment 1

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
