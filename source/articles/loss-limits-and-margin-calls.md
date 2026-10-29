# Loss limits, drawdown, margin calls and overleveraging

**Covers:** daily loss limit, drawdown, margin call, overleveraging

## Surviving the bad days {#overview}
Every trader has losing days, so a loss is not what separates those who last from those who do not. The difference is whether a bad day stays a bad day or becomes the end of the account. Four ideas explain how losses grow and how to stop them.

## Daily loss limit {#daily-loss-limit}
A daily loss limit is an amount, in dollars, that you decide on in advance and write down. When your losses for the day reach it, you stop trading until tomorrow, whatever the market is doing. Why decide beforehand? After a big loss, judgment is usually worse than before, so the rule works like a circuit breaker and takes the decision out of your hands.

## Drawdown {#drawdown}
Drawdown is the fall in your account from its recent peak to its current, lower value, in dollars or as a percentage. If the account peaked at 20,000 and now stands at 17,000, the drawdown is 3,000 dollars, or 15%. It tells you how deep the hole is. It does not tell you how often you lost.

## Margin call {#margin-call}
A margin call is a demand from your broker to deposit more money right away. It happens when losses on borrowed trades have eaten into the equity the broker requires you to keep. If you cannot add funds, the broker may sell your positions at whatever price the market gives, without asking you first.

## Overleveraging {#overleveraging}
Overleveraging means borrowing, or sizing a position, so heavily compared with your account that even a small move against you wipes out a large part of your equity. It is the most common way that accounts are lost quickly.

## A worked example {#example}
A trader has a 20,000 dollar account and sets a daily loss limit of 400 dollars, which is 2%.

1. Trade 1 loses 150.
2. Trade 2 loses 130, so the total is 280.
3. Trade 3 loses 125, so the total is 405, above the limit of 400.
4. The trader closes the platform and stops for the day. Without the rule, the thought "one more trade to win it back" would probably have produced a fourth loss.

Next, why deep losses are so costly. Suppose a trader had no limit and lost 1,500 on a bad day. The drawdown from the 20,000 peak is 1,500 / 20,000 = 7.5%. To return from 18,500 to 20,000, the trader needs a gain of 1,500 / 18,500 = 8.1%. A recovery always needs a bit more than the loss, and the gap grows quickly:

| Drawdown | Gain needed to recover |
|---|---|
| 10% | 11.1% |
| 25% | 33.3% |
| 50% | 100% |
| 75% | 300% |

Now a leveraged case. A trader has 10,000 dollars of her own cash, borrows another 10,000 and buys 20,000 dollars of stock. Say the broker requires equity of at least 25% of the position's value. The stock falls 40%:

- Position value: 20,000 × 0.60 = 12,000.
- The loan is still 10,000, so equity = 12,000 − 10,000 = 2,000.
- Required equity: 25% of 12,000 = 3,000.
- Equity of 2,000 is below 3,000, so she gets a margin call for at least 1,000 dollars.

If she cannot pay, the broker sells shares until the account meets the rules. She has lost 8,000 of her original 10,000, which is 80%, from a 40% fall in the stock. Without borrowing, the same fall would have cost 4,000, or 40%. Borrowing doubled the percentage loss and forced the sale at a low price.

In fact, the call arrives earlier than that. With a requirement of 25%, trouble starts when equity drops below 0.25 × the position value. Let d be the fall in the price. The condition is 20,000 × (1 − d) − 10,000 < 0.25 × 20,000 × (1 − d). That gives 15,000 × (1 − d) < 10,000, so d > 33.3%. A fall of a third is enough to trigger the call.

Some practical limits people use: a daily loss limit of 1% to 3% of equity, a rule to stop for the week after a certain drawdown, and a position size that would not cause a margin call even in a bad gap.

## A common mistake {#mistake}
A common slip is to set a loss limit and then raise it in the middle of a bad day. A rule you can change under stress is not a rule. Another slip is to think of drawdown in percentages that sound small. A 50% loss needs a 100% gain to recover, and that is a very different thing.

## Key points {#key-points}
- A daily loss limit is a fixed amount after which you stop trading for the day.
- Drawdown measures the fall from a peak. Deeper drawdowns need much larger gains to recover.
- A margin call demands more money when borrowed trades lose, and it can lead to forced selling.
- Overleveraging turns a normal loss into a disaster.
