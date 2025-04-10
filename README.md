# Whale_MarketMaker_Arbitrage
Whale and MarketMaker Arbitrage using Nansen's wallet labeling and Glassnode's on-chain metrics on Binance and BitMEX

Integrate Nansen's wallet labeling and Glassnode's on-chain metrics to identify whales and market makers. 

This is a Python implementation for arbitrage trading on Binance and BitMEX using above mentioned Whale and Market Maker datasets.

Key Features:
Nansen Integration: Uses Nansen's API to fetch whale and market maker wallets.

Glassnode Integration: Utilizes Glassnode for liquidity metrics of these wallets.

Dynamic Position Sizing: Adjusts position size based on wallet liquidity.

Risk Management: Maintains a stop-loss and limits exposure to 10% of capital.

Setup Instructions:
Replace YOUR_API_KEY, YOUR_SECRET, NANSEN_API_KEY, and GLASSNODE_API_KEY with actual credentials.

Adjust risk_params according to risk tolerance.

Monitor execution logs for trade confirmations.

This code leverages on-chain data to identify whales and market makers with significant liquidity, executing arbitrage trades only when these conditions are met.
