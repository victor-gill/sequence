# Sequence

An interactive wealth-building web app that walks users through a 10-step capital-stack framework — from daily cash flow to retirement to business acquisition — in plain language, no finance background required.

**Live:** https://sequence-five-henna.vercel.app

## What it does

- **Guided planner** — step-by-step flow covering income, spending, savings tiers, and investing, with progressive disclosure ("Why this step?" expanders) so first-time users never feel lectured
- **Capital-stack visualizer** — a 4-tier stack (daily operations → protection → growth → retirement base) that fills in as users enter their numbers
- **Benchmarking** — net-worth comparison against Federal Reserve Survey of Consumer Finances medians, framed as trajectory-over-rank, plus a "years to median" projection at user-defined savings rates
- **Retirement playground** — interactive scenario modeling
- **Acquisition track** — a second path covering trust/LLC structuring and buying cash-flowing small businesses (SBA 7(a), seller financing)

## Stack

Single self-contained `index.html` — HTML, CSS, and vanilla JavaScript, no build step, no backend, no dependencies. Deployed to Vercel as a static site.

## Notes

- Built mobile-first; the full planner works in a phone browser
- Copy iterated on real user testing feedback (progressive disclosure pass cut UI text ~50% while keeping all educational content one tap away)
- Benchmark data: Federal Reserve 2022 Survey of Consumer Finances (latest published)
