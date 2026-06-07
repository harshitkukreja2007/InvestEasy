# 📈 InvestEasy

> **A learning-first investment readiness system for beginners starting with small capital.**

Most investing apps skip the most important question: *Are you actually ready to invest?*

InvestEasy flips the model — it educates you first, scores your readiness, and only then unlocks investment suggestions and platforms matched to what you actually understand.

🔗 **Live Demo:** https://invest-easy-iota.vercel.app/ 


---



## The Problem

Beginners who jump into investing without knowledge tend to panic-sell, over-risk, or pick platforms that don't suit them. Most apps assume knowledge you don't have yet.

InvestEasy doesn't tell you *where* to invest before checking if you're *ready* to.

---

## How It Works

### Step 1 — Initial Assessment
You start by answering a few questions:

- **Starting Capital** — ₹500 / ₹1000 / ₹2000 / ₹5000
- **Risk Comfort Level** — from Very Low Risk (0–5% downside) to High Risk (20–40% downside)
- **Time Horizon** — Short-term (6m–1yr), Medium-term (1–3yrs), Long-term (3+ yrs)
- **Preferred Mode** — Explorer Mode (learn at your pace) or Builder Mode (structured goals)

> ⚠️ Very High Risk options (Intraday, F&O, Crypto) are excluded from recommendations — InvestEasy is built for beginners, not gamblers.

---

### Step 2 — Learning Roadmap (Staged & Locked)

Based on your profile, InvestEasy assigns you a **personalized learning roadmap** with 3 sequential stages:

| Stage | Name | What You Do |
|-------|------|-------------|
| 1 | **Foundation Learning** | Complete 3-minute learning capsules (+10 pts each) |
| 2 | **Behavioral Simulation** | Run a simulation: Stay Consistent vs Skip Months |
| 3 | **Decision Readiness Check** | Pass an assessment checkpoint |

**Stages are locked** — you can't skip. Each stage unlocks only after completing the previous one.

Stage 1 capsules include:
- *How money grows at small scale*
- *What risk really means*
- *Why discipline beats shortcuts*

---

### Step 3 — Investor Readiness Score

As you progress, InvestEasy calculates your **Readiness Score out of 100**, broken into 4 components:

| Component | Max Points | How You Earn |
|-----------|-----------|--------------|
| Knowledge Foundation | 80 pts | +10 per learning capsule completed |
| Behavioral Testing | 15 pts | Completing the simulation exercise |
| Decision Readiness | 20 pts | Passing the assessment checkpoint |
| Discipline Consistency | 50 pts | +5 per weekly goal achieved |

**Score zones:**
- 🔴 0–39: Critical
- 🟡 40–59: Developing
- 🟢 60–79: Ready
- ✅ 80–100: Excellent

---

### Step 4 — Risk Level Unlocking

Risk levels are **locked by default** and unlock based on your Readiness Score — not just what you claim your tolerance is.

| Risk Level | Downside Range | Typical Returns | Status |
|------------|---------------|-----------------|--------|
| Very Low Risk | 0–5% | 4–7% annually | Always accessible |
| Low Risk | 5–10% | 6–9% annually | Unlocks with progress |
| Moderate Risk | 10–20% | 10–14% annually | Unlocks with higher score |
| High Risk | 20–40% | 15–25% (variable) | Requires high readiness |

A beginner who claims high risk tolerance still starts conservatively — until they prove they understand what that risk means.

---

### Step 5 — Platform Recommendations

Once risk levels unlock, InvestEasy suggests **real Indian platforms** matched to your capital, risk, and time horizon:

| Risk Level | Example Platforms |
|------------|------------------|
| Very Low | Bank RDs, Liquid Funds via Groww, Zerodha Coin, Paytm Money |
| Low | Short-term Debt Funds, Digital Gold via Google Pay, ET Money |
| Moderate | Index Funds (NIFTY 50) via Zerodha, Kuvera, Paytm Money |
| High | Direct Stocks via Zerodha, Upstox, Groww, Angel One |

Each platform card shows:
- Minimum investment amount
- Learning focus (what you'll understand by using it)
- Best for (capital range, risk level, mode)
- Key features

> 📌 *Educational information only. Not financial advice.*

---

### Step 6 — Risk Guide

A dedicated **Risk Guide** explains each risk level in plain language:
- What it means in practice
- System notes on volatility and time horizons
- Who it's suitable for

---


## Key Design Decisions

- **Readiness-gated investing** — score determines access, not self-reported tolerance
- **Sequential stage unlocking** — forces foundational learning before simulation
- **India-first** — all platforms, amounts (₹), and examples are relevant to Indian beginners
- **Behavioral simulation** — teaches discipline over returns, simulating consistent vs inconsistent investing

---

## What We Learned

Building InvestEasy taught us that good product design is about *sequencing* — not just showing information, but deciding when to show it. Designing a gated system around readiness (not just user claims) pushed me to think carefully about user flows, state management, and progressive disclosure.

---


> *Don't just invest. Understand first. InvestEasy.*
