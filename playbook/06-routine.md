# 6/8 5-min routine (1 action per tick)

- Order: Position(n)/Open Orders(n) (Current pair OFF=all, ON=SOXL) -> recompute 0.66 -> sub-wave (Minute a-e/Sub-min 1-5) -> keep/move limits (filled rung refills one step down) -> verify TPs -> one-line reason.
- Use kline high/close only. Max 1 action/5min, 3s gaps. Row-exact Cancel only, never Cancel All. Recount per symbol.
- Chart Order panel to visualize limit+TP lines, then close it.
