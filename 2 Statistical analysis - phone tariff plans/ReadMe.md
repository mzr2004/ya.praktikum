# Statistical analysis - phone tariff plans

In this project we as analyst of telekom company have to understand what tariff plan out of two brings company more money.
During the project we also use statistical hypothetis to assess if the difference is statistically significant.

## Task debrief
1. Clients are offered with two tariff plans: ultra and smart;
1. In order to correct future spendings company has to understand what tariff brings more revenue;
1. We perform preliminary statistical analysis to portray tipical tariff user:
- who is he/she;
- what region from;
- how do they consume pack offer provided by tariff
- etc.

## Project flow
_Preprocessing:_
1. asigning right data format (to numeric, to datetime);
1. unused features without valuable information deleted;

_Preliminary calculations:_
1. calculating revenue per consumer, given they use pack offers (minutes, internet traffic, sms included by default);
1. calculating how number of customers per tariff changes with time

_Statistical analysis_:
1. Duration of being a client with different tariffs is the same or not? Testing hypothesis.
1. Revenue per two groups of clients is the same or not? Testing hypothesis.
1. Average revenue per Moscow client is the same as in region? Testing hypothesis.

## Some results
1. Total revenue per smart tariff is higher, though per client revenue is higher for ultra tariff.
1. Smart tariff users more often get out of by default pack and have to buy additional minutes, gigabytes.
1. Main result is that we recommend focusing on ultra tariff based on profits/losses and future opportunity to grow business.
1. etc.
