# Order types: market, limit, stop and stop-limit

**Covers:** market order, limit order, stop order, stop-limit order

## An order is a set of instructions {#overview}
When you trade, you do not only say "buy". You send an order, and it states what to buy, how many, and under what conditions. Those conditions decide two things, and no order can guarantee both: whether the trade happens, and at what price. Each order type chooses which of the two it protects. Let's see the four main types with that question in mind.

## Market order {#market-order}
A market order buys or sells right away at the best price available. It guarantees that the trade happens, but not the price. In a calm, busy stock, you get a price close to the one you saw. In a fast or thin stock, it can be quite different.

## Limit order {#limit-order}
A limit order buys or sells only at the price you name, or a better one. A buy limit at 50.00 fills at 50.00 or lower, and never higher. It guarantees the price but not the fill. If the stock never reaches your price, the order waits and may never run.

## Stop order {#stop-order}
A stop order sleeps until the stock reaches a price you choose, called the stop price. At that moment it turns into a market order and is sent. It is mostly used to leave a position when the price moves against you. Because it becomes a market order, it makes sure you get out, but it does not fix the price. If the price gaps past your stop, the fill can be worse than the stop price.

## Stop-limit order {#stop-limit-order}
A stop-limit order also waits for the stop price, but then it becomes a limit order instead of a market order. It has two prices: the stop price that triggers it, and the limit price that caps what you accept. It guarantees the price but not the fill. If the price falls through your limit very quickly, the order may never fill, and you stay in the position.

## A worked example {#example}
Suppose you own 100 shares that trade at 50.00, and you want protection against a fall.

| Order | Instruction | What happens if the price drops to 49.00 quickly |
|---|---|---|
| Stop | Sell if price reaches 49.50 | At 49.50 it becomes a market order. The fill might be 49.20 because the price is moving fast |
| Stop-limit | Stop 49.50, limit 49.40 | At 49.50 it becomes a limit to sell at 49.40 or better. If the price has already fallen to 49.30, it does not fill |

Compare the losses. With the stop order you sold at 49.20, so the loss is (50.00 − 49.20) × 100 = 80 dollars. With the stop-limit that did not fill, you still hold the shares. If the price keeps falling to 48.00, the loss on paper is (50.00 − 48.00) × 100 = 200 dollars. The stop got you out at a worse price than planned, but it got you out. The stop-limit protected the price and failed to protect the exit.

Now an entry. You want to buy at 50.00 or lower, and the stock is at 50.40.

- A market order buys now at about 50.40. You get certainty, and you pay 40 cents more per share than your target, which is 40 dollars for 100 shares.
- A limit order at 50.00 waits. If the stock dips to 50.00, you buy at your price. If it climbs away, you miss the move, and the only thing that costs you is the opportunity.

| Need | Order | You give up |
|---|---|---|
| To be in or out now | Market | Control of the price |
| To control the price | Limit | Certainty of a fill |
| To exit automatically when a price is hit | Stop | Control of the price |
| To exit automatically at a controlled price | Stop-limit | Certainty of the exit |

Many beginners use limit orders for entries, and they think carefully before using any order that turns into a market order in a fast move.

## A common mistake {#mistake}
A common slip is to use a market order in a thin stock, or right after a news release, and then to be surprised by the fill price. Another is placing a stop-limit with the limit price too close to the stop. A quick drop jumps over it, and you are left holding the loss.

## Key points {#key-points}
- A market order guarantees the fill, not the price. A limit order guarantees the price, not the fill.
- A stop order becomes a market order at its trigger. A stop-limit order becomes a limit order.
- Decide which one you can live without: the price or the fill.
