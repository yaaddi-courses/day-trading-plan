# Order types: market, limit, stop and stop-limit

**Covers:** market order, limit order, stop order, stop-limit order

## An order is a set of instructions {#overview}
When you trade, you do not just say "buy". You send an order, which states what to buy, how many, and under what conditions. The conditions decide two things that cannot both be guaranteed: whether the trade happens, and at what price. Each order type chooses which of the two it protects.

## Market order {#market-order}
A market order buys or sells immediately at the best price currently available. It guarantees that the trade happens, but not the price. In a calm, busy stock, the price you get is close to the one you saw. In a fast or thin stock, it can be quite different.

## Limit order {#limit-order}
A limit order buys or sells only at a price you name, or a better one. A buy limit at 50.00 will fill at 50.00 or lower, and never higher. It guarantees the price but not the fill: if the stock never reaches your price, the order waits and may never run.

## Stop order {#stop-order}
A stop order stays inactive until the stock reaches a chosen price, called the stop price. At that moment it turns into a market order and is sent. It is mostly used to exit a position when the price moves against you. Because it becomes a market order, it guarantees that you get out, but not at what price. If the price gaps past your stop, the fill can be worse than the stop price.

## Stop-limit order {#stop-limit-order}
A stop-limit order is a stop order that, once triggered, becomes a limit order instead of a market order. It has two prices: the stop price that triggers it, and the limit price that caps what you accept. It guarantees the price but not the fill. If the price drops through your limit very fast, the order may never fill, and you stay in the position.

## A worked example {#example}
You own 100 shares that trade at 50.00 and you want to protect against a fall.

| Order | Instruction | What happens if the price drops to 49.00 quickly |
|---|---|---|
| Stop | Sell if price reaches 49.50 | At 49.50 it becomes a market order. The fill might be 49.20 because the price is moving fast |
| Stop-limit | Stop 49.50, limit 49.40 | At 49.50 it becomes a limit to sell at 49.40 or better. If the price has already fallen to 49.30, it does not fill |

Compare the losses. With the stop order: you sold at 49.20, so the loss is (50.00 − 49.20) × 100 = 80 dollars. With the stop-limit that did not fill, you still hold the shares, and if the price keeps falling to 48.00, the loss on paper is (50.00 − 48.00) × 100 = 200 dollars. The stop got you out at a worse price than planned, but out. The stop-limit protected the price, but not the exit.

Now entering. You want to buy at 50.00 or lower, with the stock at 50.40.

- A market order buys now at about 50.40 and gives certainty. You pay 40 cents more per share than your target, or 40 dollars for 100 shares.
- A limit order at 50.00 waits. If the stock dips to 50.00, you buy at your price. If it climbs away, you miss the move, and that costs you nothing but the chance.

| Need | Order | You give up |
|---|---|---|
| To be in or out now | Market | Control of the price |
| To control the price | Limit | Certainty of a fill |
| To exit automatically when a price is hit | Stop | Control of the price |
| To exit automatically at a controlled price | Stop-limit | Certainty of the exit |

A practical rule for beginners: use limit orders for entries and consider carefully before using any order that turns into a market order in a fast move.

## A common mistake {#mistake}
Using a market order in a thin stock or just after a news release, then being surprised by the fill price. Another mistake is placing a stop-limit with the limit price too close to the stop, so a quick drop skips over it and leaves you holding the loss.

## Key points {#key-points}
- A market order guarantees the fill, not the price. A limit order guarantees the price, not the fill.
- A stop order becomes a market order at its trigger. A stop-limit order becomes a limit order.
- Decide which you can live without: the price or the fill.
