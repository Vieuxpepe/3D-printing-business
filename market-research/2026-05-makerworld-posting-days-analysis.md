# MakerWorld Posting Days Analysis

## Executive summary

This note turns the MakerWorld stats screenshots from 2026-05-03 into a repo-ready posting strategy.

The strongest current recommendation is:

| Use case | Recommended day | Why |
|---|---|---|
| Best overall drop day | Sunday | Strong recent user activity and solid historical performance |
| Best routine weekly posting day | Friday | Good recent activity, less distorted by boost than Monday |
| Best conversion day | Thursday | Best view-to-save and view-to-download efficiency |
| Best boosted major release day | Monday | Historically strongest raw performance, but heavily boost-influenced |
| Day to avoid for major releases | Tuesday | Weakest performance across volume and conversion |

Simple schedule:

| Posting cadence | Recommended schedule |
|---|---|
| 1 model per week | Sunday |
| 2 models per week | Thursday + Sunday |
| 3 models per week | Thursday + Friday + Sunday |

Main takeaway: **Sunday should be the default day for important releases right now. Friday is the safest routine day. Thursday is best when the model is highly printable and you want saves/downloads. Monday is still useful, but mainly for major models that can receive boost early.**

## Data source

Source material:

- Four screenshots of the MakerWorld model list, covering 38 published models.
- One screenshot of the recent user activity chart, covering roughly one month.
- Metrics visible in the screenshots: points, boost, views, likes, saves, downloads, impressions, model title, and publication date.

Important limitation:

- The model list data was reconstructed from screenshots, not from a raw export.
- The recent user activity chart was estimated visually from bar heights.
- The results are strong enough for planning, but should be treated as a working strategy rather than a perfect statistical export.

## Key metrics used

The analysis focuses on both volume and quality of traffic.

| Metric | Meaning |
|---|---|
| Points | Overall MakerWorld reward/performance signal |
| Views | Reach and visibility |
| Saves / views | How many viewers want to keep the model for later |
| Downloads / views | How many viewers convert into users/printers |
| Engagement / views | Likes + saves + downloads divided by views |
| Boost average | Helps detect when a day looks strong because of boosted exposure |
| Recent activity index | Approximate daily audience activity from the chart |

Engagement formula:

```text
engagement_rate = (likes + saves + downloads) / views
```

## Day-by-day performance

| Day | Posts | Avg points | Avg views | Weighted engagement | Saves / views | Downloads / views | Avg boost | Recent activity index |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Monday | 9 | 850.3 | 8,442 | 23.7% | 12.3% | 7.5% | 7.0 | 97.1 |
| Tuesday | 3 | 156.0 | 2,316 | 9.6% | 5.0% | 2.6% | 2.3 | 91.2 |
| Wednesday | 7 | 275.5 | 2,431 | 21.1% | 10.5% | 6.7% | 0.9 | 81.0 |
| Thursday | 4 | 346.0 | 2,012 | 28.6% | 15.5% | 9.1% | 2.2 | 90.4 |
| Friday | 6 | 358.2 | 3,476 | 20.8% | 11.3% | 5.9% | 2.3 | 109.5 |
| Saturday | 2 | 185.6 | 1,798 | 21.7% | 12.6% | 5.0% | 0.0 | 117.9 |
| Sunday | 7 | 436.2 | 3,586 | 22.5% | 11.9% | 7.0% | 2.9 | 124.7 |

## Interpretation

### Monday: strongest raw performance, but boost-heavy

Monday has the highest average points and views. It also contains most of the highest-performing historical models.

However, Monday also has the highest average boost by a large margin:

```text
Monday avg boost: 7.0
Friday avg boost: 2.3
Thursday avg boost: 2.2
Wednesday avg boost: 0.9
```

Because boost and points are strongly related in the sample, Monday should not automatically become the default posting day. It should be treated as a strong day for **major releases that can get early boost support**.

Best use:

- flagship knight releases
- major fantasy miniatures
- models with strong thumbnail appeal
- models you expect followers to boost quickly

### Sunday: best current overall bet

Sunday has the strongest recent activity index and a good historical baseline. It is not as extreme as Monday in raw points, but it is less dependent on boost and better aligned with the current audience activity pattern.

Best use:

- important releases
- new fantasy miniatures
- collection starters
- models that should get weekend browsing traffic

### Friday: safest routine publishing day

Friday has strong recent activity and decent historical performance. It sits just before the weekend peak, which makes it useful for regular publishing.

Best use:

- weekly standard releases
- non-flagship fantasy models
- reliable catalog growth
- models that can benefit from weekend discovery after posting

### Thursday: best conversion day

Thursday has the best conversion metrics in the sample:

```text
Weighted engagement: 28.6%
Saves / views: 15.5%
Downloads / views: 9.1%
```

This makes Thursday especially interesting when the model is highly printable, practical, or collection-worthy.

Best use:

- clean support-friendly miniatures
- utility models
- models with clear print value
- models likely to be saved for later printing

### Tuesday: avoid for big releases

Tuesday is weak across the most important signals. It has low points, low views, and low conversion.

Best use:

- small updates
- low-priority tests
- profile edits
- non-critical releases only

## Recommended posting rules

### Rule 1: Put the best model on Sunday

If only one model is ready, post it on Sunday.

Reason:

- strongest current audience activity
- good historical performance
- weekend browsing behavior fits hobby content

### Rule 2: Use Friday for steady growth

If posting every week, Friday is the most stable routine day.

Reason:

- good activity
- less boost distortion than Monday
- gives the model time to gain traction before the weekend peak

### Rule 3: Use Thursday for conversion-focused models

If the model is especially printable, useful, or save-worthy, Thursday is very strong.

Reason:

- best saves per view
- best downloads per view
- best overall engagement efficiency

### Rule 4: Reserve Monday for boosted flagship releases

Monday can still be excellent, but only if the model is strong enough to attract boost early.

Reason:

- historically strongest raw stats
- heavily affected by boost
- should be used selectively instead of automatically

### Rule 5: Do not waste top models on Tuesday

Tuesday should not receive the highest-value releases until new evidence proves otherwise.

Reason:

- weakest average performance
- weakest conversion
- no clear upside in current data

## Suggested 8 to 12 post validation test

To confirm the strategy, test only comparable models. Do not compare a flagship knight against a small utility holder, because that tests product demand more than posting day.

### Test setup

Use the next 8 to 12 comparable models, ideally fantasy miniatures with similar quality and thumbnail strength.

Keep stable:

- title quality
- thumbnail quality
- listing quality
- print profile quality
- category and tags
- model complexity level

Track at:

- 24 hours
- 72 hours
- 7 days

### Metrics to record

| Metric | Why it matters |
|---|---|
| Views at 72h | Measures early reach |
| Saves / views at 72h | Measures interest and future intent |
| Downloads / views at 72h | Measures true conversion |
| Points at 7d | Measures reward outcome |
| Boost at 7d | Helps separate day effect from boost effect |

### Test plan

Round A:

```text
Thursday vs Sunday
```

Goal: compare conversion day against best overall day.

Round B:

```text
Friday vs Monday
```

Goal: compare routine day against historically strong boosted day.

Decision rule:

| Goal | Choose the day that wins on |
|---|---|
| Maximum reach | Views at 72h |
| More saves | Saves / views |
| More actual prints/downloads | Downloads / views |
| More rewards | Points at 7d |
| Best non-boosted signal | Points adjusted mentally against boost count |

## Product-specific recommendation

Based on the current catalog pattern, fantasy miniatures should stay the main posting focus.

Strong signals from the visible model list:

- knights perform extremely well
- dark swordsmen and brutal warriors perform well
- monsters can work, especially when visually strong
- practical holders can get views, but weaker points and conversion than top miniatures
- complex or unclear products are less reliable

Recommended model priority:

| Priority | Model type | Best posting day |
|---|---|---|
| 1 | Knight / paladin / commander miniature | Sunday or boosted Monday |
| 2 | Dark swordsman / barbarian / orc warlord | Sunday or Friday |
| 3 | Printable monster boss | Sunday |
| 4 | Clean support-friendly miniature | Thursday |
| 5 | Practical holder / organizer | Thursday or Friday |
| 6 | Experimental model | Tuesday or Wednesday |

## Practical next actions

- Post the next strongest miniature on Sunday.
- Use Thursday if the model is extremely printable and likely to be saved/downloaded.
- Use Friday for steady weekly publishing.
- Save Monday for a flagship model with strong thumbnail appeal and early boost potential.
- Avoid Tuesday for important releases.
- Start a simple tracking sheet with 24h, 72h, and 7d metrics.

## Confidence level

| Conclusion | Confidence | Reason |
|---|---|---|
| Sunday is the best current overall day | Medium-high | Strong current activity and solid history |
| Friday is best for routine posting | Medium | Good recent activity and decent historical base |
| Thursday is best for conversion | Medium-high | Strongest saves/views and downloads/views |
| Monday is strong but boost-influenced | High | Very high raw stats and very high average boost |
| Tuesday should be avoided for major releases | Medium-high | Weak across volume and conversion |
| Saturday may be promising | Low-medium | Strong recent activity, but only two historical posts |

## Repo note

This file should be updated after the next 8 to 12 comparable releases. The best future improvement would be a raw CSV export or a manually maintained tracker with the following columns:

```text
model_title,date_posted,weekday,category,points_24h,points_72h,points_7d,views_24h,views_72h,views_7d,likes_72h,saves_72h,downloads_72h,boost_7d,notes
```
