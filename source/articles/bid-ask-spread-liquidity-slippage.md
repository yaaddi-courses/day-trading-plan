# Bid, ask, spread, liquidity and slippage

**Covers:** bid, ask, spread, liquidity, slippage

## Why a stock has two prices {#overview}
When you look up a stock, you usually see one number. It is natural to think that this number is the price, and that you can buy or sell at it. In practice, the market keeps two prices at the same moment, and the gap between them is part of what every trade costs you. Let's look at where the two prices come from, and then at how to measure that cost.

## Bid {#bid}
Think of the people who want to buy the stock right now. Each one names a price they will pay, and the best of those offers, the highest one, is the bid. It matters to you when you are the one selling: if you sell immediately with a market order, the bid is roughly the price you receive.

## Ask {#ask}
Now think of the people who want to sell. Each names a price they will accept, and the lowest of those is the ask, which some platforms call the offer. If you are buying immediately with a market order, the ask is roughly what you pay. So the buyer meets the ask, and the seller meets the bid.

## Spread {#spread}
The ask is always a little higher than the bid, because no seller will accept less than the best buyer is offering. The distance between the two is the spread. With a bid of 49.98 and an ask of 50.02, the spread is 50.02 − 49.98 = 0.04.

You pay the spread whenever you want to trade at once. If you buy at the ask and sell straight back at the bid, with no movement in between, you lose exactly the spread. A narrow spread makes that cheap, and a wide spread makes it expensive.

## Liquidity {#liquidity}
Liquidity answers a different question: how easily can you get in or out without pushing the price around? A stock with many active buyers and sellers is liquid. It usually has a narrow spread, and a lot of shares are waiting at every price. A stock with few participants is illiquid. Its spread is wider, and even a modest order can make the price jump.

This matters more to a day trader than to someone who holds for years, because a day trader has to leave a position within hours. If you can enter but cannot leave quickly at a fair price, the trade can turn on you.

## Slippage {#slippage}
Slippage is the difference between the price you expected and the price you actually got. It has two usual causes. The market can move between the moment you decide and the moment your order is filled. Or your order can be bigger than the number of shares waiting at the best price, so it has to take shares from the next price too. Slippage is usually against you, and it never appears as a line on your statement, which is why it is easy to overlook.

## A worked example {#example}
We have two stocks quoted at the same moment.

| | Stock A (liquid) | Stock B (illiquid) |
|---|---|---|
| Bid | 50.00 | 20.00 |
| Ask | 50.01 | 20.30 |
| Spread | 0.01 | 0.30 |
| Spread as % of price | 0.02% | 1.5% |

Suppose you buy 200 shares and sell them back at once, and the price does not move.

- Stock A: you pay 50.01 and receive 50.00, so you lose 0.01 × 200 = 2 dollars.
- Stock B: you pay 20.30 and receive 20.00, so you lose 0.30 × 200 = 60 dollars on a position of about 4,000 dollars.

Stock B cost 30 times as much to enter and leave. It also needs the price to rise 1.5% before you break even, and for a day trade that is a high bar.

Now slippage. The sellers of stock A are lined up like this:

| Ask price | Shares waiting |
|---|---|
| 50.01 | 100 |
| 50.02 | 300 |
| 50.03 | 500 |

You send a market order to buy 400 shares. The first 100 shares come at 50.01. The next 300 come at 50.02, because the cheapest level is used up. The average price is (100 × 50.01 + 300 × 50.02) / 400 = 20,007 / 400 = 50.0175. You expected 50.01, the best ask, so the slippage is 0.0075 per share, which is 3 dollars on 400 shares. That is small. In a thin stock where the next level sits 0.20 higher, the same order would cost far more.

You can reduce slippage in four ways. Trade liquid stocks. Stay away from the first minutes after the open, when prices jump. Use a limit order, which sets the worst price you accept. And keep your order small compared with what is waiting at the best price.

## A common mistake {#mistake}
A common slip is to look only at the last traded price. That price is something that already happened. What you can do right now is buy at the ask or sell at the bid, and the two may be some distance from the last price. A second slip is picking a stock because its low price "looks cheap" and then finding that it trades so thinly that the spread eats the profit.

## Key points {#key-points}
- Buyers meet the ask and sellers meet the bid. The spread is the gap, and it is a cost.
- Liquidity means a narrow spread and many shares waiting, so trades are quick and cheap.
- Slippage is the gap between the fill you expected and the fill you got.
- Before each trade, compare the spread with the profit you hope to make.
