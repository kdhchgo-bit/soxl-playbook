# SOXL 4-Box Pyramid — position sizing change (2026-11-24)

## Rule (current)
- **1 box = 4-grid pyramid = 6% of seed (minimum) as margin.**
- 4 boxes = 16 grids = **24% of seed total**.
- Inside each box: rungs descend from the top, size 10% / 20% / 30% / 40% (smallest on top, largest at the bottom).
- Example (seed 1,174.22, box notional 493.17): 49.31 / 98.63 / 147.95 / 197.28.
- No separate scout tranche; total must stay at 24%.
- Box spacing 5.5% (top × 0.945). First box top = high − 0.66 × (high − low).

## Risk
- All 16 grids filled → average 35.04 (current levels) → 7x liquidation ≈ 30.21, below the last rung 31.08, so every grid fills before liquidation.
- Loss at liquidation = full margin = **-24% of account**.

## Superseded
- 1.5% per box (6% total) and the 0.5–1.5% scout tranche are retired as of this change.
