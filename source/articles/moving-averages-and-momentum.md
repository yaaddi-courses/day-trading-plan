# Moving averages and momentum indicators

**Covers:** moving average, SMA, EMA, moving average crossover, RSI, overbought, oversold, MACD

## Smoothing the noise {#overview}
Look at a raw price chart and you will see the price jump up and down all the time. It is hard to tell which way it is really heading. Indicators are calculations on the price that make one aspect easier to see. Two kinds are used the most: averages that smooth the price, and momentum indicators that measure how fast it is moving. Let's start with the averages.

## Moving average {#moving-average}
A moving average is a line that smooths a stock's price by averaging it over a fixed number of recent periods, such as the last 50 days. Each new period, the oldest price drops out and the newest comes in, which is why the line "moves". It is a lagging indicator, because it follows the price and never leads it. A longer average is smoother and slower.

## SMA {#sma}
SMA stands for simple moving average. Every price in the lookback period gets the same weight. A 5-day SMA adds the last five closing prices and divides by five, so the oldest day counts as much as the newest.

## EMA {#ema}
EMA stands for exponential moving average. It gives more weight to recent prices, so it reacts to new moves faster than an SMA of the same length. It follows the price more closely, and it also reacts more to noise.

## Moving average crossover {#moving-average-crossover}
A crossover happens when a faster average crosses a slower one. Say a 10-period line moves above a 50-period line. Traders often read that as a shift toward an uptrend, and a cross below as a shift down. Keep in mind that both lines lag, so the signal comes late.

## RSI {#rsi}
RSI, the Relative Strength Index, is a number between 0 and 100 that measures how fast and how far the price has moved recently. The usual setting looks back 14 periods. Readings above 70 are traditionally seen as high, and readings below 30 as low.

## Overbought {#overbought}
A stock is called overbought when it has risen so far and so fast that people expect a pullback, often shown by a high RSI. Treat it as a warning, not as an instruction to sell. In a strong trend, a stock can stay overbought for a long time.

## Oversold {#oversold}
Oversold is the mirror image. The price has fallen so far and so fast that people expect a bounce, often shown by a low RSI. Here too, a falling stock can stay oversold while it keeps falling.

## MACD {#macd}
MACD stands for Moving Average Convergence Divergence. It compares two moving averages to show changes in momentum and trend direction. It subtracts a slower EMA from a faster one, then draws a signal line, which is an average of that result. When the MACD line crosses above its signal line, momentum is turning up. When it crosses below, momentum is turning down.

## A worked example {#example}
The last five closing prices are 10, 11, 12, 13 and 14.

**SMA of 5.** (10 + 11 + 12 + 13 + 14) / 5 = 60 / 5 = 12. The price is 14 and the SMA is 12. The average lags two units behind, because it still includes the older, lower prices.

**EMA of 5.** The weight of each new price is 2 / (5 + 1) = 1/3. Suppose the previous EMA was 11.5. With a new close of 14, the new EMA is 14 × 1/3 + 11.5 × 2/3 = 4.667 + 7.667 = 12.33. That is a little closer to the price than the SMA of 12, so the EMA reacts faster.

**Crossover.** Suppose a trader follows a 10-day and a 30-day average. For weeks the 10-day sat below the 30-day. This morning the 10-day average is 51.2 and the 30-day is 51.0, so the faster line has crossed above. It hints at an uptrend, but it arrived after the price had already risen from 48. The signal is late by design.

**RSI.** Suppose that over 14 days the average gain on up days is 0.80 and the average loss on down days is 0.20. Relative strength is 0.80 / 0.20 = 4. Then RSI = 100 − 100 / (1 + 4) = 100 − 20 = 80. That is above 70, so the stock reads as overbought. Some traders wait for a pullback before buying in that situation, and others tighten the exit on a position they already hold.

| Indicator | Measures | Weakness |
|---|---|---|
| SMA | Average direction | Slow |
| EMA | Average direction, recent emphasis | Noisier |
| RSI | Speed of the move | Can stay extreme in a strong trend |
| MACD | Change in momentum | Lags, many false signals in ranges |

No indicator predicts the future. Each one describes the past in a convenient way. Use a few, learn them well, and combine them with price levels and volume.

## A common mistake {#mistake}
A common slip is to sell the moment RSI passes 70, or to buy the moment it drops below 30, while the trend is strong. Strong trends keep the reading extreme for a long time. Another slip is piling many indicators onto one chart. They give conflicting signals and slow down your decision.

## Key points {#key-points}
- A moving average smooths the price. The SMA treats all periods equally, and the EMA favors recent ones.
- A crossover of a fast and a slow average hints at a change of trend, and it comes late.
- RSI above 70 is overbought and below 30 is oversold. MACD tracks changes in momentum.
- Indicators describe the past and do not predict.
