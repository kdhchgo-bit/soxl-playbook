# 8/8 Logging

- Tick line: time(KST), price(close), Position, Open Orders(all/symbol), 1.5% math, keep/move reason in one line.
- Keep numbers in STATE/MEMORY, rules in SKILL. Head lines start with `> YYYY-MM-DD` and move with the appended record.
- No full-file replace; line-anchored edits only. Never infer current book from a past cancel incident.
