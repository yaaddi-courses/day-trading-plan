# Market data and the costs of trading

**Covers:** real-time data, Level II quotes, commission, payment for order flow

## What you see and what you pay {#overview}
Two things decide how well you can trade before you even have an idea: the quality of the information on your screen, and the costs hidden in each order. Both are easy to overlook, and both are worth understanding before real money is used.

## Real-time data {#real-time-data}
Real-time data is live, up-to-the-second price and quote information. The alternative is delayed data, usually behind by 15 minutes or more, which many free services provide. For a day trader, delayed data is useless: a price that is 15 minutes old describes a market that no longer exists. Some data is free through a broker, and some, from certain exchanges, requires a monthly fee.

## Level II quotes {#level-ii-quotes}
Level II quotes are a data feed that shows every current bid and ask price waiting in line for a stock, not just the single best bid and ask. It displays the depth of the market: how many shares are waiting at each price. Reading it helps you see where large orders sit and how much a trade could move the price.

## Commission {#commission}
A commission is the fee that a broker charges for carrying out a trade. In the past, it was often 5 to 10 dollars per trade. Most US brokers now charge nothing for ordinary stock and ETF trades. Other fees may remain, such as small regulatory fees on sales, or charges for certain data and order types.

## Payment for order flow {#payment-for-order-flow}
Payment for order flow is money that a broker earns by sending your order to a particular market maker to be filled. It is part of how many brokers can offer commission-free trading. The concern is conflict of interest: the broker is paid for where the order goes, which may not be where you would get the best price. Regulators require brokers to report where they route orders and to seek good execution.

## A worked example {#example}
A day trader makes 10 round trips per day, so 20 orders. Compare two brokers over 20 trading days.

| | Broker 1 | Broker 2 |
|---|---|---|
| Commission per order | 1.00 | 0.00 |
| Orders in 20 days | 20 × 20 = 400 | 400 |
| Commission paid | 400 dollars | 0 dollars |

Broker 2 looks 400 dollars cheaper. But consider the fill prices. Say Broker 2 routes orders for payment, and its fills are on average 0.01 dollars per share worse than Broker 1's. With 100 shares per order, the extra cost per order is 0.01 × 100 = 1.00 dollar, the same as the commission. Over 400 orders, that is also 400 dollars. The savings disappear, only they are hidden in the price, not on a bill.

This is only an illustration with invented numbers. Real differences vary by stock, broker and day, and may be much smaller or larger. The lesson: total cost is the commission plus the price quality. To compare, make small trades at both and compare the fill prices with the quotes at the time of the order.

Now the data. A stock shows this on the simple screen: bid 20.00, ask 20.02. Level II shows more:

| Ask price | Shares |
|---|---|
| 20.04 | 5,000 |
| 20.03 | 800 |
| 20.02 | 200 |

Only 200 shares wait at 20.02. If you send a market order for 1,000, the first 200 fill at 20.02, the next 800 at 20.03, and the average is (200 × 20.02 + 800 × 20.03) / 1,000 = 20.028. That is 0.008 above the best ask. The simple screen would not have warned you that your order was five times the size of the best level.

Prices of data differ. If Level II costs 30 dollars a month and the trader makes only 200 dollars a month, the data eats 15% of the income. It should be paid for only if it changes decisions.

## A common mistake {#mistake}
Choosing a broker only for zero commission and ignoring execution quality and data limits. Another mistake is trading on delayed data without noticing the label on the screen. Check that the quotes you see are live.

## Key points {#key-points}
- Day trading needs real-time data. Delayed data is for reading, not trading.
- Level II quotes show the depth of the market behind the best price.
- Zero commission does not mean zero cost, since payment for order flow may affect fill prices.
- Compare brokers by total cost, with real small trades.
