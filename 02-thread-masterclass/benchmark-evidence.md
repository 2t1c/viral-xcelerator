# Benchmark Evidence

Hard numbers behind the coaching. Every claim in this file is computed from an internal database of 2,905 verified multi-tweet threads, each with roughly 1M+ views, published April 2023 to June 2026, with full per-tweet view data.

This is a database of winners. The benchmarks below describe what viral threads look like, not what average threads look like, so treat them as the bar to clear rather than the norm.

## Definitions

- **Views.** Impressions on the hook tweet.
- **Hook conversion (CTR).** Views of tweet 2 divided by views of tweet 1. What share of hook viewers opened the thread. This is not link CTR.
- **End-to-end retention.** Views of the weakest tweet in the thread divided by hook views. How much of the original audience the worst tweet kept.
- **Engagement rate.** Likes + retweets + replies + quotes + bookmarks, divided by views.
- **Bookmark rate.** Bookmarks divided by views. The save signal.

## The benchmark table

Percentiles across all 2,905 threads. Read p75 as "top quartile starts here" and p90 as "top decile starts here."

| Metric | p25 | Median | p75 | p90 |
|---|---|---|---|---|
| Views | 1.3M | 2.0M | 3.9M | 9.1M |
| Hook conversion (CTR) | 3.9% | 5.2% | 6.8% | 8.8% |
| End-to-end retention | 1.1% | 1.9% | 3.4% | 18.0% |
| Engagement rate | 0.44% | 0.74% | 1.13% | 1.56% |
| Bookmark rate | | 0.26% | | 0.71% |

How to grade yourself:

- **CTR 5% = median viral thread.** A 5% hook is not exceptional, it is table stakes among winners. 6.8%+ puts you in the top quartile, 8.8%+ in the top decile.
- **Even viral threads lose almost everyone.** The median winner keeps only 1.9% of hook viewers through its weakest tweet. Spread over a typical 14-tweet thread, that works out to roughly 74% of readers surviving each tweet transition. The top quartile holds about 77% per step, the bottom quartile about 71%. Small per-tweet leaks compound brutally.
- **Engagement above 1.1% is top-quartile.** Above 1.6% is elite.

## CTR does not predict reach

The most counterintuitive finding in the data. Split all 2,905 threads into hook-conversion quartiles and the view counts barely move:

| CTR quartile | CTR range | Median views |
|---|---|---|
| Q1 (lowest) | 0 to 3.9% | 2.04M |
| Q2 | 3.9 to 5.2% | 2.06M |
| Q3 | 5.2 to 6.8% | 2.04M |
| Q4 (highest) | 6.8%+ | 1.94M |

The top decile of threads by views confirms it. Only 36% of them have above-median CTR, and their average CTR (4.7%) is below the dataset average.

What this means: the hook wins the feed on its own, as a standalone tweet that earns likes and retweets from people who never open the thread. The body serves the roughly 1-in-20 who click through.

So optimize in two separate passes:

- **Hook = distribution.** Write it to be engaged with by scrollers, not just opened.
- **Body = depth.** Write it for the small audience that clicked, because they are the ones who follow, bookmark, and buy.

One caveat. Everything in this dataset already went viral, so this says CTR stops mattering for reach once the hook is good enough to win the feed. A weak hook still kills a thread before it ever gets here.

## Thread length

The median viral thread is 14 tweets. Length distribution and performance:

| Length | Threads | Median views | Mean CTR | Mean retention |
|---|---|---|---|---|
| 2 to 4 tweets | 346 | 1.70M | 3.6% | 3.4% |
| 5 to 7 | 61 | 1.79M | 6.3% | 5.7% |
| 8 to 10 | 242 | 1.71M | 6.8% | 7.6% |
| 11 to 15 | 1,183 | 2.06M | 5.9% | 6.5% |
| 16+ | 1,066 | 2.18M | 5.4% | 5.9% |

Readings:

- **Long threads dominate the sample.** 77% of viral threads run 11+ tweets. Going long does not hurt reach, the 16+ bucket has the highest median views.
- **Retention peaks at 8 to 10 tweets.** That is the depth where the body holds the most of its audience. Past 15 tweets, retention slips as fatigue sets in.
- **Very short threads underperform on conversion.** The 2-to-4 bucket has the worst CTR (3.6%). A 3-tweet thread rarely promises enough to be worth opening.

Practical default: 10 to 15 tweets. Enough depth to deliver, before the fatigue tax.

## Hook length: kill the short-hook myth

The median viral hook is 37 words and 219 characters. It nearly fills the 280-character limit.

| Hook length | Threads | Median views | Mean CTR |
|---|---|---|---|
| 1 to 10 words | 102 | 2.11M | 3.6% |
| 11 to 20 | 294 | 1.79M | 5.7% |
| 21 to 30 | 431 | 1.95M | 5.7% |
| 31 to 50 | 1,941 | 2.07M | 5.6% |
| 51+ | 123 | 1.96M | 5.0% |

Two-thirds of all viral hooks are 31 to 50 words. The punchy one-liner hook is the worst performer on conversion (3.6% CTR), because a hook that short cannot set up stakes and open a loop at the same time.

The floor matters more than the ceiling. Anything from 11 words up converts at roughly the same rate, but below 11 words conversion collapses.

## Media on the hook

92% of viral hooks carry no media at all. Text does the work.

| Hook media | Threads | Median views | Mean CTR |
|---|---|---|---|
| None | 2,684 | 2.02M | 5.5% |
| Photo | 148 | 1.67M | 6.2% |
| Video | 72 | 2.72M | 5.1% |

A photo nudges conversion up but correlates with lower reach. Video flips it, higher reach but fewer click-throughs. The samples are small, so treat these as directional.

## Niche performance

All niches with a meaningful sample. Count is shown so you can weigh how much to trust each row.

| Niche | Threads | Median views | Mean CTR | Mean retention | Engagement | Bookmark rate |
|---|---|---|---|---|---|---|
| Health | 1,093 | 1.96M | 5.7% | 6.3% | 0.81% | 0.38% |
| Business | 499 | 1.97M | 5.6% | 7.2% | 0.80% | 0.29% |
| History | 406 | 2.32M | 5.1% | 4.0% | 0.99% | 0.24% |
| Finance | 211 | 1.67M | 5.3% | 4.2% | 0.79% | 0.33% |
| AI | 166 | 2.18M | 5.5% | 5.3% | 0.69% | 0.32% |
| Fitness | 149 | 2.33M | 5.3% | 3.5% | 0.57% | 0.29% |
| Mental Health | 68 | 1.84M | 6.0% | 14.2% | 1.36% | 0.70% |
| Politics | 67 | 3.96M | 6.0% | 6.4% | 1.00% | 0.16% |
| Science | 64 | 2.31M | 6.3% | 6.4% | 1.03% | 0.39% |
| Self Improvement | 45 | 2.05M | 5.2% | 2.1% | 0.73% | 0.29% |
| Psychology | 38 | 1.86M | 6.0% | 14.0% | 0.97% | 0.46% |
| Genius | 34 | 1.82M | 5.0% | 4.0% | 1.18% | 0.36% |
| Art | 20 | 1.54M | 4.2% | 2.0% | 1.21% | 0.26% |

What the table says:

- **Politics buys reach and nothing else.** Highest median views (3.96M) and the lowest bookmark rate in the dataset (0.16%). People watch, nobody keeps it.
- **Mental Health and Psychology own depth.** Retention near 14% (7x the dataset median), the highest engagement, and bookmark rates of 0.46 to 0.70%. Smaller audiences that actually read, save, and follow.
- **History is hit-driven.** Mean views (5.5M) run far above median (2.3M), meaning a few monster outliers carry the niche, and its retention is below average. Great for reach spikes, weak for keeping readers.
- **Science quietly converts best.** Highest CTR of any major niche at 6.3%, with above-average saves.
- **Health is the volume game.** Over a third of the entire dataset, with solid all-around numbers and strong saves.

This is the same reach-versus-saves split documented in [power-words-and-metrics.md](../swipe-files/power-words-and-metrics.md), now visible at niche scale. Decide which metric you are buying before you pick the topic.

## The takeaways

1. Grade your hooks against percentiles, not vibes: 5% CTR is median, 7% is good, 9% is elite.
2. Write the hook to win the feed as a standalone tweet. Most of your views never open the thread.
3. Default to 10 to 15 tweets. Short threads convert worst and long ones gain no extra reach after 16.
4. Write full hooks, 30 to 50 words. Under 11 words, conversion collapses.
5. Skip hook media by default. 92% of winners are text-only.
6. Pick the niche by the metric you want: Politics-style topics for raw reach, psychology and mental health angles for followers and saves.
7. Fix the leakiest tweet, not the average tweet. End-to-end retention is set by your single worst transition.

## Methodology and caveats

- Stats are computed on thread head rows only (the hook tweet carries thread-level data). Single tweets and misattributed quote records were filtered out.
- Blank values were excluded per metric, never by dropping the whole thread. Fewer than 10 rows were blank for any metric.
- Survivorship bias is built in. Every thread here already cleared roughly 1M views, so these are benchmarks of winners.
- Data spans April 2023 to June 2026 with collection ongoing, roughly 60 to 130 new threads per month through the last year.
- Mean and median diverge heavily on views (4.1M vs 2.0M). Outliers up to 67.7M views pull every mean upward, which is why this file leads with medians and percentiles.
