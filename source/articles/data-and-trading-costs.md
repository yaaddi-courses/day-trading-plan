# Market data and the costs of trading

**Covers:** real-time data, Level II quotes, commission, payment for order flow

## What you see and what you pay {#overview}
Before you have a single trading idea, two things already decide how well you can trade: how good the information on your screen is, and what each order quietly costs you. Both are easy to overlook, so let's go through them before any real money is involved.

## Real-time data {#real-time-data}
Real-time data means live prices and quotes, updated as the market moves. The other kind is delayed data, usually 15 minutes behind or more, which many free services provide. Ask yourself what a price from 15 minutes ago is worth to a day trader. It describes a market that no longer exists. Some live data comes free with a broker, and some, from certain exchanges, costs a monthly fee.

## Level II quotes {#level-ii-quotes}
An ordinary quote shows you one bid and one ask. Level II quotes show the whole line of waiting prices on both sides, along with the number of shares waiting at each. That is the depth of the market. Reading it tells you where large orders are sitting and how far your own order could push the price.

## Commission {#commission}
A commission is a fee the broker charges for carrying out a trade. It used to be 5 to 10 dollars per trade. Today most US brokers charge nothing for ordinary stock and ETF trades. Smaller charges can remain, such as regulatory fees on sales, or fees for certain data and order types.

## Payment for order flow {#payment-for-order-flow}
If the broker charges you nothing, how does it earn money? One answer is payment for order flow: a market maker pays the broker for the right to fill your order. That helps explain commission-free trading. It also raises a fair question, because the broker is paid for where your order goes, and that may not be the place with the best price for you. Regulators require brokers to report where they route orders and to seek good execution.

## A worked example {#example}
Suppose a day trader makes 10 round trips a day, which is 20 orders. We compare two brokers over 20 trading days.

| | Broker 1 | Broker 2 |
|---|---|---|
| Commission per order | 1.00 | 0.00 |
| Orders in 20 days | 20 × 20 = 400 | 400 |
| Commission paid | 400 dollars | 0 dollars |

Broker 2 looks 400 dollars cheaper. Now look at the fills. Say Broker 2 routes orders for payment, and its fills are on average 0.01 dollars per share worse than Broker 1's. With 100 shares per order, the extra cost per order is 0.01 × 100 = 1.00 dollar, the same as Broker 1's commission. Over 400 orders it is again 400 dollars. The saving has vanished. It has moved from a bill into the price.

These numbers are invented to illustrate the idea. Real differences change with the stock, the broker and the day, and they can be much smaller or larger. The lesson is that total cost is the commission plus the quality of the price. To compare brokers, place small trades with each and compare your fills with the quotes at the moment you sent the order.

Now the data. A basic screen shows a stock with a bid of 20.00 and an ask of 20.02. Level II shows more:

| Ask price | Shares |
|---|---|
| 20.04 | 5,000 |
| 20.03 | 800 |
| 20.02 | 200 |

Only 200 shares wait at 20.02. If you send a market order for 1,000 shares, the first 200 fill at 20.02 and the next 800 at 20.03. The average is (200 × 20.02 + 800 × 20.03) / 1,000 = 20.028, which is 0.008 above the best ask. The basic screen would not have warned you that your order was five times the size of the best level.

Data has a price too. If Level II costs 30 dollars a month and the trader earns only 200 dollars a month, the data takes 15% of the income. It is worth paying for only if it changes your decisions.

## A common mistake {#mistake}
A common slip is to choose a broker only because the commission is zero, without a look at execution quality or data limits. Another is trading on delayed data without noticing the label on the screen. Before you trade, confirm that the quotes you see are live.

## Key points {#key-points}
- Day trading needs real-time data. Delayed data is for reading, not for trading.
- Level II quotes show the depth of the market behind the best price.
- Zero commission does not mean zero cost, because payment for order flow can affect your fill prices.
- Compare brokers by total cost, using real small trades.
