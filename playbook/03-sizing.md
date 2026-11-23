# 3/8 Sizing (1.5% x4)

- Base = wallet ex position margin; reset to full wallet after flat.
- Per-order margin = base*0.015, notional = base*0.015*7, USDT input, 1c floor.
- Max 4 concurrent, spacing 0.40-0.50. After full fill, recompute 0.66 next tick and lay fresh 4.
