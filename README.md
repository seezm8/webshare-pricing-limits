# webshare review: real per‑GB prices, plan limits, and when a $1/GB pool makes more sense

Search "webshare review" and you'll land on a lot of pages that say the same two things: it's the cheapest proxy provider around, and it has over 80 million residential IPs. Both of those statements show up in Webshare's own marketing, and both are roughly true. What those pages usually skip is the part that decides your actual invoice — which product line you're buying, whether your bandwidth survives the month, and what the crossed‑out price on the pricing page is really doing.

That's what this review is for. Below: what Webshare sells, what each tier costs per the most recent published price tables, what independent reviewers found in 2026, and the specific workloads where a different pricing model wins.

## The three questions hiding behind "is Webshare good?"

People searching for a Webshare review are almost never asking about the company. They're asking one of these:

1. Can I actually pay $3.50 for a gigabyte of residential traffic, or is there a catch?
2. Will a $2.99 proxy server plan survive contact with real targets?
3. If I buy 50 GB and only use 12 GB this month, what happens to the rest?

The short answers: yes with a caveat, sometimes, and it's gone. Details below.

## What Webshare actually sells

Webshare runs four product lines rather than one. That structure matters more than any single price, because the cheapest headline number and the product most people need are not the same thing.

- **Free tier** — 10 datacenter proxies with 1 GB of bandwidth per month, no credit card required. It's a real product, not a 3‑day trial.
- **Proxy Server (datacenter)** — shared or dedicated datacenter IPs, priced per proxy plus a bandwidth allowance. This is where the "$2.99" number comes from: 100 proxies, monthly.
- **Static Residential / ISP** — residential‑class IPs from networks like Comcast and AT&T, priced per IP per month with unlimited bandwidth, aimed at account management and long sessions.
- **Rotating Residential** — the 80M+ IP pool across 195 countries, priced per gigabyte.

One gap is worth flagging early: there's no mobile proxy product. CNET's 2026 review notes that directly, along with thinner third‑party integrations than the bigger enterprise providers [1]. If your targets require 4G/5G carrier IPs, Webshare simply isn't in that market.

HTTP and SOCKS5 are supported across the board, and authentication works either by username/password or IP whitelisting.

## Webshare pricing, line by line

Here's the published structure as of the most recent third‑party price snapshots from September 2026.

| Product | Billing unit | Entry point | Scaling | Notes |
| --- | --- | --- | --- | --- |
| Free | — | $0, 10 proxies | — | 1 GB/month bandwidth, no card required |
| Proxy Server (datacenter) | Per proxy + bandwidth | ~$2.99/month for 100 proxies | Falls to ~$0.0179 per proxy at 60,000 proxies | Shared and dedicated variants; volume discounts up to ~40% |
| Static Residential / ISP | Per IP / month | From ~$6/month (60,000+ IP pool) | ~$0.30 per IP at 20 IPs, ~$0.24 on yearly billing; ~$0.225 at 10,000 IPs | Unlimited bandwidth; private/dedicated IPs cost more |
| Rotating Residential | Per GB | $3.50/GB at 1 GB | Down to $1.40/GB at 3,000 GB | 80M+ IPs, 195 countries |

The rotating residential ladder is the one most readers care about, so here it is in full [1]:

| Plan | Residential price (per GB) |
| --- | --- |
| 1 GB | $3.50 |
| 10 GB | $2.75 |
| 25 GB | $2.60 |
| 50 GB | $2.45 |
| 100 GB | $2.25 |
| 250 GB | $2.00 |
| 500 GB | $1.75 |
| 1,000 GB | $1.50 |
| 3,000 GB | $1.40 |

Nine tiers, and the per‑GB rate roughly halves from bottom to top. For an agency burning 100 GB a month, that's $225 — a rate that's hard to beat on a like‑for‑like residential pool.

> The advertised $1.40/GB is the 3,000 GB row. Reaching it costs $4,200 a month. Published comparisons have noted that Webshare's ladder is among the most transparent in the industry, but the headline number is a floor nobody small actually pays [3].

## The $7 that nobody pays

Open the rotating residential tab and every tier has a struck‑through $7.00/GB sitting next to it. The 1 GB plan shows a "SAVE 50%" badge. Since every row carries a discount badge, the $7 anchor isn't a former price anyone was ever charged — it's a reference number that makes $3.50 feel like a win before you've compared it to anything [4].

The yearly toggle has a separate quirk. On rotating residential, "save 30%" checks out exactly: $3.50 monthly becomes $2.45 yearly, $2.25 becomes $1.58. On the per‑proxy products, a September 2026 analysis found the yearly per‑proxy figure and the yearly monthly total don't agree with each other, and the reviewer couldn't determine which one the invoice uses [4]. Practical takeaway: if you're buying a yearly per‑proxy plan, confirm the number at checkout before committing. Not a reason to avoid Webshare — a reason to read the receipt.

## Performance: what independent testing says

This is where the "cheapest proxy" narrative gets more textured.

CNET's 2026 review, drawing on Proxyway's annual benchmark data, describes Webshare's performance as middling overall: web scraping and data aggregation workloads are more likely to get flagged than with Oxylabs or Decodo, and you may burn more data to complete the same job. Response time and success rate were described as perfectly adequate for most use cases — not class‑leading [1]. CNET still recommended paying the small premium over the nearest budget competitor for the better pool and success rate on popular targets [1].

On the reliability side, 99.97% uptime and a 100+ Gbps network are Webshare's own published claims, not independently audited numbers. Treat them accordingly.

Customer sentiment is decent but not flawless. Webshare sits around 4.3–4.4 out of 5 on Trustpilot across roughly 500 reviews. PCMag's analysis notes praise for support quality and service reliability, with the bulk of complaints involving account suspensions and refunds — and that the company responds to negative reviews rather than ignoring them [2].

If you're deciding partly on reputation, that's a middle‑of‑the‑pack profile: above the fly‑by‑night tier, below providers with years of enterprise track record.

## The limits that hit your wallet harder than the price

Four restrictions matter more than any per‑GB figure.

**Bandwidth expires monthly.** Webshare's residential plans are subscription‑based, and unused gigabytes don't roll over. If your scraping volume swings — a big crawl one month, a light patch the next — you're paying for capacity you don't use. This is the single biggest structural difference between Webshare and pay‑as‑you‑go competitors [5].

**No free trial on paid plans.** The free tier is a genuine free product, but it's 10 datacenter proxies and 1 GB. You cannot test the residential pool on a trial basis; the only exit is the refund path [3].

**The refund window is narrow.** Webshare offers refunds but only within specific conditions: cancel within roughly 48 hours, use under 1 GB of data, and stay under 1,000 proxies [2][3]. Read that before you test aggressively.

**Datacenter IPs get blocked.** This applies to every provider, not just Webshare, but it's worth saying because the $2.99 plan is the one people buy first. Datacenter IPs are easy for sites to detect. If your target runs serious bot defense, no per‑proxy discount saves you.

None of these are dealbreakers. They're the reasons the sticker price and the real cost diverge.

## Where a pay‑as‑you‑go pool fits better

There's one billing model Webshare doesn't offer at all, and it solves the expired‑bandwidth problem outright: pay‑as‑you‑go traffic that doesn't expire.

DataImpulse is the provider CNET singles out as the only one coming close to Webshare on price, quoting $1 per GB [1]. It works differently. Residential traffic starts at $1/GB with no subscription and no monthly reset — buy 50 GB, use 12 GB this month, the other 38 GB is still there next quarter. Datacenter runs $0.50/GB, mobile $2/GB, and premium residential $5/GB, all drawn from a pool the company advertises at 90M+ ethically sourced IPs across 195 countries.

A few operational details worth knowing before you sign up:

- Country‑level targeting is included at the base rate; city, state, ZIP, and ASN filters are billed at roughly 2× on standard residential plans. Datacenter product pages list the finer targeting as included, so confirm with support if you're budgeting on it [6].
- Rotating connections run on port 823 (HTTP/HTTPS) and 824 (SOCKS5). Sticky sessions are configurable in the 1–120 minute range, defaulting to 30 minutes when no interval is set [6].
- Traffic is billed on volume, not IP count, and there's no free trial — ProxyLook's editorial review flags the absence of a trial alongside thinner pool depth in Tier‑3 geographies and no SOC 2/ISO 27001 certification yet [7].
- Third‑party sources disagree on the refund policy; one lists a 7‑day refund window for new users [6], another states there's no refund window at all [7]. If a refund matters to your decision, get it in writing from support first.

G2 rates it 4.8/5, the company publishes a 99.51% success rate, and ProxyLook's benchmark summary puts Google SERP success around 99.74% and Cloudflare‑fronted targets near 93.1% — solid for retail and SEO work, a step behind the premium social‑platform specialists [7].

The honest counterpoint: CNET, having compared both, still recommends paying a little more for Webshare's residential pool and success rate on popular targets [1]. DataImpulse wins on billing structure and entry price, not on having the strongest pool.

## Full DataImpulse plan lineup

Every plan currently shown across its four proxy types, with entry pricing and volume tiers:

| Proxy type | Package price | Traffic included | Effective rate | Purchase |
| --- | --- | --- | --- | --- |
| Residential — intro | $5 | 5 GB | $1.00/GB | [Get the 5 GB residential plan](https://bit.ly/dataimPulse) |
| Residential — advanced | $800 | 1 TB | $0.80/GB | [Get the 1 TB residential tier](https://bit.ly/dataimPulse) |
| Datacenter — intro | $5 | 10 GB | $0.50/GB | [Get the 10 GB datacenter plan](https://bit.ly/dataimPulse) |
| Datacenter — 100 GB | $50 | 100 GB | $0.50/GB | [Get the 100 GB datacenter plan](https://bit.ly/dataimPulse) |
| Datacenter — 1 TB | $450 | 1 TB | $0.45/GB | [Get the 1 TB datacenter tier](https://bit.ly/dataimPulse) |
| Datacenter — 5 TB+ | From $2,250 | 5 TB+ | Custom | [Request custom datacenter pricing](https://bit.ly/dataimPulse) |
| Mobile — intro | $5 | 2.5 GB | $2.00/GB | [Get the 2.5 GB mobile plan](https://bit.ly/dataimPulse) |
| Mobile — 25 GB | $50 | 25 GB | $2.00/GB | [Get the 25 GB mobile plan](https://bit.ly/dataimPulse) |
| Mobile — 1 TB | $1,600 | 1 TB | $1.60/GB | [Get the 1 TB mobile tier](https://bit.ly/dataimPulse) |
| Mobile — 5 TB+ | From $8,000 | 5 TB+ | Custom | [Request custom mobile pricing](https://bit.ly/dataimPulse) |
| Premium residential — intro | $5 | 1 GB | $5.00/GB | [Get the premium residential trial pack](https://bit.ly/dataimPulse) |
| Premium residential — 10 GB | $50 | 10 GB | $5.00/GB | [Get the 10 GB premium residential plan](https://bit.ly/dataimPulse) |
| Premium residential — 5 TB+ | From $20,000 | 5 TB+ | Custom | [Request custom premium pricing](https://bit.ly/dataimPulse) |

No verified public promo code was found for either provider during research, so any "DataImpulse coupon" page promising a working code should be treated with suspicion. The $5 intro packages are the advertised entry offer.

## Which one should you actually buy

Skip the brand loyalty and match the plan to the workload. Four common cases:

**SERP rank tracking at high volume.** Datacenter IPs, small payloads. Webshare's $2.99‑for‑100‑proxies plan is the value pick here, and residential is overkill unless your target fights back.

**Variable or spiky residential usage.** If you can't predict monthly volume, expiring bandwidth is the expensive part of Webshare. A non‑expiring $1/GB balance means you buy once and draw it down. 👉 [Compare DataImpulse's pay-as-you-go rates against a fixed monthly quota](https://bit.ly/dataimPulse)

**Mobile targets.** Webshare has no mobile product. This isn't a close call.

**Same IP per account, heavy bandwidth per IP.** Static residential, where Webshare's per‑IP model is built for exactly this. Predictable, and cheaper than metered traffic once each IP pushes real volume.

**Hardened targets with aggressive bot defense.** Neither is the specialist pick. Both land mid‑tier on Cloudflare‑fronted and social targets, and the premium providers charge accordingly.

## FAQ

**Is Webshare's free plan actually free?**
Yes — 10 proxies and 1 GB of monthly bandwidth with no credit card. It's a datacenter product, so it's a testing sandbox, not a residential trial.

**Does Webshare offer a free trial on paid plans?**
No. The free tier and the refund window are the only pre‑commitment options, and the refund requires cancelling within about 48 hours, under 1 GB used, and under 1,000 proxies.

**Do DataImpulse credits expire?**
No. Purchased traffic stays in the account until you use it, which is the main structural difference from Webshare's monthly residential subscription.

**Can Webshare handle mobile proxies?**
No mobile product exists. DataImpulse covers 4G/5G traffic from $2/GB.

**Which is cheaper per gigabyte?**
At very high commit, Webshare's 3,000 GB tier at $1.40/GB undercuts DataImpulse's $0.80/GB‑at‑1‑TB only if you're not reaching DataImpulse's volume tier — at 1 TB the two land in the same neighborhood, with DataImpulse at $0.80. Below 100 GB, DataImpulse's flat $1/GB beats Webshare's $2.25–$3.50/GB range, and the non‑expiry clause is worth more than the rate difference for most small teams.

## Bottom line

Webshare is a legitimate, cheap, genuinely self‑serve proxy provider with a real free tier, a transparent price ladder, and a decent support reputation. It's a good fit for datacenter scraping at volume, per‑IP static residential work, and anyone who wants to test a proxy project for $0 before paying.

It's a weaker fit for unpredictable monthly usage, mobile targets, and buyers who want to trial the residential pool before committing. That's the gap a $1/GB, non‑expiring, no‑subscription model fills — and it's why CNET keeps naming DataImpulse as the closest competitor on price while still preferring Webshare's pool on the hardest popular targets [1]. Buy for your workload, not for the crossed‑out number.
