# 4/8 Stop loss (ratchet up only)

- Close-price basis (daily ET 16:00; 5m needs 2 closes). Ignore wicks.
- Stop = structure break (e.g. 29.82 close break), never a fixed % from average. Move only to prior swing low after T1/breakout (e.g. 52.5 break -> under 46.0). Never move down.
- Isolated 7x liq ~= avg*0.862. Keep stop above liq. One setup caps at 25-30% margin.
