# Bid, ask, spread, liquidity and slippage

**Covers:** bid, ask, spread, liquidity, slippage

## Every stock has two prices at once {#overview}
A stock does not have a single price. At any moment, there is a price at which people are ready to buy and a higher price at which people are ready to sell. The gap between them, and how deep the crowd is on each side, decides what a trade really costs you.

## Bid {#bid}
The bid is the highest price a buyer is currently willing to pay for the stock. If you want to sell right now with a market order, the bid is roughly what you will receive.

## Ask {#ask}
The ask is the lowest price a seller is currently willing to accept. If you want to buy right now with a market order, the ask is roughly what you will pay. It is also called the offer.

## Spread {#spread}
The spread is the gap between the bid and the ask. If the bid is 49.98 and the ask is 50.02, the spread is 0.04. It is a cost that you pay for immediacy: buying at the ask and selling at the bid straight away loses the spread. A narrow spread is cheap. A wide spread is expensive.

## Liquidity {#liquidity}
Liquidity is how easily a stock can be bought or sold quickly without moving its price much, because many buyers and sellers are present. A liquid stock has a narrow spread and plenty of shares waiting at each price. An illiquid stock has few participants, a wider spread, and prices that jump on small orders. Day traders favor liquid stocks, because they must be able to leave fast.

## Slippage {#slippage}
Slippage is what you lose to a fill that is worse than the price you saw when you decided to trade. It happens when the market moves between your decision and the fill, or when your order is larger than the shares waiting at the best price, so it must take the next price levels too. Slippage is usually unfavorable, and it is a hidden cost.

## A worked example {#example}
Two stocks are quoted at the same time.

| | Stock A (liquid) | Stock B (illiquid) |
|---|---|---|
| Bid | 50.00 | 20.00 |
| Ask | 50.01 | 20.30 |
| Spread | 0.01 | 0.30 |
| Spread as % of price | 0.02% | 1.5% |

Buy 200 shares and sell them back immediately, with no price change.

- Stock A: you pay 50.01 and receive 50.00, a loss of 0.01 × 200 = 2 dollars.
- Stock B: you pay 20.30 and receive 20.00, a loss of 0.30 × 200 = 60 dollars. Stock B cost 30 times more to enter and leave, on a position worth about 4,000 dollars.

To profit on stock B, the price would have to rise by 1.5% just to break even. For a day trade, that is a large hurdle. This is why day traders prefer liquid stocks.

Now slippage. The ask book for stock A looks like this:

| Ask price | Shares waiting |
|---|---|
| 50.01 | 100 |
| 50.02 | 300 |
| 50.03 | 500 |

You send a market order for 400 shares. It buys 100 at 50.01, then 300 at 50.02. The average price is (100 × 50.01 + 300 × 50.02) / 400 = 50.0175. You expected 50.01 (the best ask), so the slippage is 0.0075 per share, or 3 dollars in total. That is small. For a thin stock where the next price level is 0.20 higher, the same size would cost much more.

Ways to reduce slippage: trade liquid stocks, avoid the first minutes after the open, when prices jump, use limit orders to cap the price, and keep the order size small compared with what is available.

## A common mistake {#mistake}
Looking only at the last traded price and ignoring the spread. The last price is a past event. What you can actually do now is buy at the ask or sell at the bid. Another mistake is trading low-priced, thinly traded stocks because they "look cheap", and then discovering that the spread eats the profit.

## Key points {#key-points}
- Buyers see the ask, sellers see the bid. The spread is the gap, and it is a cost.
- Liquidity means a narrow spread and many shares waiting, so trades run fast and cheap.
- Slippage is the gap between the expected and the actual fill price.
- Compare the spread with your expected profit before every trade.
