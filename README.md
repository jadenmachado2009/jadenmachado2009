# Jaden Machado

A2 student at JBCN International, Mumbai. I build tools at the intersection of markets and human behaviour.

Most of what I know about finance came from shipping things rather than reading about them: writing and backtesting strategies, then watching them fail in ways a textbook never warned me about.

---

## Projects

### [NQ Algo Strategy Lab](https://github.com/jadenmachado2009/nq-algo-strategy-lab) · [v4](https://github.com/jadenmachado2009/nq-algo-strategy-lab/releases/tag/v4)
A testing pipeline for futures strategies, built on the assumption that my own ideas are worthless until evidence says otherwise. It has retired one strategy on ~1,500 trades, failed to validate a second, and — the part I'm most pleased with — **rejected its own best search result**: a strategy showing profit factor 1.42 over 1,772 trades, which a null test proved was indistinguishable from searching 450 combinations on pure noise (p = 0.72).

One strategy has survived that test: an opening-range breakout, long only, over 7,063 trades and 7.8 years (p = 0.00 against bootstrapped noise, positive in six of eight years including 2022). Its edge is +0.022R per trade — small, and small is the interesting part. Most of the work became arithmetic about what a small edge is worth: a prop account is a convex payoff, so the binding constraint is risk geometry rather than prediction, and a drawdown that stops trailing once you're far enough ahead is worth more than any entry signal I tested. The honest conclusion is in the numbers: five challenge attempts give a 92% chance of passing one and a 45% chance of ending in profit, because half of funded accounts never pay out. [`MATH.md`](https://github.com/jadenmachado2009/nq-algo-strategy-lab/blob/main/research/MATH.md) has the derivations; [`PROP_PLAYBOOK.md`](https://github.com/jadenmachado2009/nq-algo-strategy-lab/blob/main/research/PROP_PLAYBOOK.md) has the spec and the caveats.

### [Blindspot](https://useblindspot.github.io/)
A behavioural bias intervention tool. It profiles your cognitive biases, then checks you at the *moment* of a decision rather than after it. Trading and everyday modes. Grounded in prospect theory, mental accounting, and narrative economics. Runs entirely in the browser — no data leaves the device.

### [SnapCal](https://snapcal-pi.vercel.app) · [code](https://github.com/jadenmachado2009/snapcal)
A calorie tracker built on one idea: photograph a meal, get calories and macros back. Gemini reads the photo and estimates the portion, barcodes resolve through Open Food Facts, and a weight log projects the date you reach your target. Built with Claude Code on Vercel. The apps that do this well are subscriptions for what is, underneath, a single model call — the hard parts were portion estimates, correcting a wrong result in plain English, and deciding what to leave out.

### [original-pine-strategies](https://github.com/jadenmachado2009/original-pine-strategies)
Pine Script strategies I have written and tested on TradingView.

### [public-strategy-testing-pine](https://github.com/jadenmachado2009/public-strategy-testing-pine)
Public strategies stress-tested on TradingView, with notes on what actually holds up out of sample.

### [learning-python-trading-strategies](https://github.com/jadenmachado2009/learning-python-trading-strategies)
Python-based strategies — working through algorithmic trading from first principles.

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/jaden-machado)
