# Loss limits, drawdown, margin calls and overleveraging

**Covers:** daily loss limit, drawdown, margin call, overleveraging

## Surviving the bad days {#overview}
Every trader has losing days. What separates those who last from those who do not is whether a bad day stays a bad day or becomes the end of the account. Four ideas explain how losses grow and how to stop them.

## Daily loss limit {#daily-loss-limit}
A daily loss limit is a dollar figure you set in advance. When your losses for the day reach it, you stop trading until tomorrow, whatever the market is doing. You decide it in advance, in writing. It is a circuit breaker: after a certain loss, judgment is usually worse than before, so the rule takes the decision away.

## Drawdown {#drawdown}
Drawdown measures a fall in the account: the distance between its recent peak and its current, lower value, in dollars or as a percentage. If an account peaked at 20,000 and fell to 17,000, the drawdown is 3,000 dollars, or 15%. It measures how deep the hole is, not how often you lost.

## Margin call {#margin-call}
A margin call is a demand from your broker to deposit more money immediately, because losses on borrowed trades have eaten into your required equity. If you cannot add funds, the broker may sell your positions, at whatever price the market gives, without asking you.

## Overleveraging {#overleveraging}
Overleveraging means borrowing, or sizing a position, so large relative to the account that even a small adverse move wipes out a big share of your equity. It is the most common way that accounts are lost quickly.

## A worked example {#example}
A trader has an account of 20,000 dollars and sets a daily loss limit of 400 dollars (2%).

1. Trade 1 loses 150.
2. Trade 2 loses 130. The total is 280.
3. Trade 3 loses 125. The total is 405, which is above the limit of 400.
4. The trader closes the platform and stops for the day. Without the rule, the "one more trade to win it back" thought would likely have produced a fourth loss.

How the rule protects the month. Suppose a trader allowed himself to lose without limit on bad days, and lost 1,500 on one of them. Drawdown from the 20,000 peak is 7.5%. To return to 20,000 from 18,500, he needs to gain 1,500 / 18,500 = 8.1%. Recoveries are always a bit larger than the losses, and the gap grows quickly:

| Drawdown | Gain needed to recover |
|---|---|
| 10% | 11.1% |
| 25% | 33.3% |
| 50% | 100% |
| 75% | 300% |

Now the leveraged case. A trader has 10,000 dollars of her own cash, borrows another 10,000, and buys 20,000 dollars of stock. Say the broker requires equity of at least 25% of the position's value. The stock falls 40%:

- Position value: 20,000 × 0.60 = 12,000.
- The loan is still 10,000, so equity = 12,000 − 10,000 = 2,000.
- Required equity: 25% of 12,000 = 3,000.
- Equity 2,000 is below 3,000, so she gets a margin call for at least 1,000 dollars.

If she cannot pay, the broker sells shares until the account is within the rules. She has lost 8,000 of her original 10,000 (80%) from a 40% fall in the stock. Without leverage, the same fall would have cost 4,000 (40%). That is overleveraging at work: borrowing doubled the percentage loss and forced the sale at the bottom.

The call usually comes earlier than this, in fact. With 25% required, trouble starts when equity falls below 0.25 × value. Solving for the price drop d: 20,000 × (1 − d) − 10,000 < 0.25 × 20,000 × (1 − d), giving 15,000 × (1 − d) < 10,000, so d > 33.3%. A fall of a third triggers the call.

Practical limits: a daily loss limit of 1% to 3% of equity, a rule to stop for the week after a certain drawdown, and a position size that would not trigger a margin call even in a bad gap.

## A common mistake {#mistake}
Setting a loss limit and then raising it in the middle of a bad day. A rule that you can change under stress is not a rule. Another mistake is thinking about drawdown in percentages that sound small: a 50% loss needs a 100% gain.

## Key points {#key-points}
- A daily loss limit is a fixed amount after which trading stops for the day.
- Drawdown measures the fall from a peak. Deeper drawdowns need much larger gains to recover.
- A margin call demands more money when borrowed trades lose, and may lead to forced selling.
- Overleveraging turns a normal loss into a disaster.
