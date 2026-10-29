# Moving averages and momentum indicators

**Covers:** moving average, SMA, EMA, moving average crossover, RSI, overbought, oversold, MACD

## Smoothing the noise {#overview}
Raw prices jump up and down, and it is hard to see the direction behind the jumps. Indicators are calculations on the price that make one aspect easier to see. Two families are used the most: averages that smooth the price, and momentum indicators that measure how fast it is moving.

## Moving average {#moving-average}
A moving average is a line that smooths a stock's price by averaging it over a set number of recent periods, such as the last 50 days. Each new period, the oldest price drops out and the newest enters, so the line "moves". It is a lagging indicator: it follows the price, and never leads it. A longer average is smoother but slower.

## SMA {#sma}
SMA, the simple moving average, gives every price in its lookback period the same weight. A 5-day SMA adds the last five closing prices and divides by five. Every day counts equally, and the oldest day matters as much as the newest.

## EMA {#ema}
EMA, the exponential moving average, gives more weight to recent prices, so it reacts to new moves faster than an SMA of the same length. It follows the price more closely and also reacts more to noise.

## Moving average crossover {#moving-average-crossover}
A moving average crossover is a signal that traders watch for when a faster average crosses above or below a slower one. A faster average, such as a 10-period line, crossing above a slower one, such as a 50-period line, is often read as a shift toward an uptrend. Crossing below is read as a shift down. It is a late signal, since both lines lag.

## RSI {#rsi}
RSI, the Relative Strength Index, is an indicator from 0 to 100 that measures how fast and how far the price has recently moved. The usual setting looks back 14 periods. Readings above 70 are traditionally treated as high, and readings below 30 as low.

## Overbought {#overbought}
Overbought describes a stock whose price has risen so far and so fast that it is considered due for a pullback, often flagged by a high RSI reading. It is a warning, not a sell signal. In strong trends, a stock can stay overbought for a long time.

## Oversold {#oversold}
Oversold is the opposite: the price has fallen so far and so fast that it is considered due for a bounce, flagged by a low RSI reading. Again, a falling stock can stay oversold while it keeps falling.

## MACD {#macd}
MACD, Moving Average Convergence Divergence, compares two moving averages to show shifts in momentum and trend direction. It subtracts a slower EMA from a faster one, and draws a signal line, an average of that result. When the MACD line crosses above its signal line, momentum is turning up. When it crosses below, momentum is turning down.

## A worked example {#example}
The last five closing prices are 10, 11, 12, 13, 14.

**SMA of 5:** (10 + 11 + 12 + 13 + 14) / 5 = 60 / 5 = 12.

The price is 14, and the SMA is 12. The average lags two units behind, because it includes the lower older prices.

**EMA of 5:** The weight of each new price is 2 / (5 + 1) = 1/3. Suppose the previous EMA was 11.5. With a new close of 14, the new EMA = 14 × 1/3 + 11.5 × 2/3 = 4.667 + 7.667 = 12.33. It is a bit closer to the price than the SMA of 12. The EMA reacts faster.

**Crossover.** A trader tracks a 10-day and a 30-day average. For weeks, the 10-day was below the 30-day. This morning, the 10-day average is 51.2 and the 30-day is 51.0. The faster line has crossed above. It is a hint of an uptrend, but it came after the price had already risen from 48. The signal is late by design.

**RSI.** Suppose that over 14 days, the average gain on up days is 0.80, and the average loss on down days is 0.20. Relative strength is 0.80 / 0.20 = 4. RSI = 100 − 100 / (1 + 4) = 100 − 20 = 80. That is above 70, so the stock is overbought. A trader might wait for the pullback before buying, or tighten an exit on a position already open.

| Indicator | Measures | Weakness |
|---|---|---|
| SMA | Average direction | Slow |
| EMA | Average direction, recent emphasis | Noisier |
| RSI | Speed of the move | Can stay extreme in a strong trend |
| MACD | Change in momentum | Lags, many false signals in ranges |

No indicator predicts the future. They are descriptions of the past, shown in a useful way. Use few, learn them well, and combine them with levels and volume.

## A common mistake {#mistake}
Selling the moment RSI is above 70, or buying the moment it is below 30, in a strong trend. Strong trends keep the reading extreme. Another mistake is piling many indicators on one chart, which gives conflicting signals and slows the decision.

## Key points {#key-points}
- A moving average smooths the price. The SMA treats all periods equally, and the EMA favors recent ones.
- A crossover of a fast and a slow average hints at a shift in trend, late.
- RSI above 70 is overbought, below 30 is oversold. MACD tracks changes in momentum.
- Indicators describe, and do not predict.
