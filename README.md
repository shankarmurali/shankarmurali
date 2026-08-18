# Hi, I'm Shankar 👋

I work in the security space — I lead a team at Google that defends Cloud, Gemini, and Workspace against payment fraud, account hijacking, and billing-surface abuse. My career has run the full arc of platform defense: payments risk in Google's early India days, payments licensing across the US and UK, ads policy enforcement in the first ML-classifier era, counterfeit operations, account security — and now back to payments, where the attackers have AI agents and so do we.

These projects are the open-source side of that work: built on public sources, free infrastructure, and the belief that defenders get better when the patterns are shared.

## 🛰️ What I'm building

### [Signal Desk](https://shankarmurali.github.io/signal-desk-v2/) — read today's issue
A daily AI security & fraud newsletter that publishes itself. Every morning, GitHub Actions gathers from keyless public sources — researcher feeds, Hacker News, arXiv, and my incident tracker below — ranks stories with a transparent signal-strength score, and ships a new issue to a versioned web archive with an [RSS feed](https://shankarmurali.github.io/signal-desk-v2/feed.xml). No servers, no API keys, no cost. [Code here](https://github.com/shankarmurali/signal-desk-v2) (successor to [signal-desk v1](https://github.com/shankarmurali/signal-desk)); PRs that add sources are welcome.

### [deep-research-kit](https://github.com/shankarmurali/deep-research-kit)
A model-agnostic deep research agent with a keyless corpus engine. It gathers evidence from six free public APIs (OpenAlex, arXiv, GDELT news, and more), then runs a full research loop — decompose into sub-questions, read primary sources, synthesize a cited report — against **any** AI: local Ollama by default, any OpenAI-compatible endpoint by env var, or Claude Code via a bundled skill. Every report ends with an automated citation audit that flags anything the model cited but never actually read. `python3 start.py` is the whole onboarding.

### [ai-agent-incidents](https://shankarmurali.github.io/ai-agent-incidents/)
A structured, community-maintained database of real-world AI agent failures — destructive actions, prompt-injection exploits, agentic supply-chain compromises. Each entry records what access the agent had, what technically failed, and how far it spread, with sources. Defenders need the pattern, not the anecdote. PRs welcome; no exploit code, ever.

### [awesome-ai-trust-and-safety](https://github.com/shankarmurali/awesome-ai-trust-and-safety)
Curated resources for practitioners: frameworks, red-team tools, abuse data feeds, foundational research, and the communities where this field lives.

*These four compose: the incident tracker feeds the newsletter, the newsletter's archive feeds the research agent, and the awesome list maps the territory.*

## 🔭 What I'm thinking about

AI access abuse — the payments and identity layer of AI platforms: stolen-card-funded compute, free-tier abuse economics, account takeover for resale, and what agentic AI does to all three. If you work on any of this, my DMs are open.

## 🎵 Beyond security

I compose and produce original music — devotional and Carnatic-fusion works across Tamil, Telugu, Hindi, Kannada, and Sanskrit, built in a home studio around a piano and an ever-growing set of production craft rules. Different discipline, same habit: diagnose the failure mode, fix the root cause, ship.

---

📍 Bay Area · 💼 [LinkedIn](https://www.linkedin.com/in/shankarmurali)
