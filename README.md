# Price Reversal Scanner

A self-resolving prediction market that identifies **price reversals and trend changes**.

## Distinctive Features

- **Reversal Detection**: Identifies tops, bottoms, and whipsaw patterns
- **Three Reversal Types**: Top, Bottom, and Whipsaw
- **Price Movement Analysis**: Tracks price direction changes
- **Threshold-Based Detection**: Configurable reversal thresholds

## How Reversal Detection Works

1. Each contract tracks price movements over time
2. Reversal strength is calculated from price direction changes
3. Top: strength > threshold, Bottom: strength > threshold, Whipsaw: strength > threshold
4. Contracts settle based on the detected reversal

## Contracts

- ETH - Top Reversal > 0.04
- BTC - Bottom Reversal > 0.03
- SOL - Whipsaw Reversal > 0.5

## Installation

npm install
npm start

## License

MIT
