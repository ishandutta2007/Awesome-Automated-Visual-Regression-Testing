# Awesome-Automated-Visual-Regression-Testing

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **Applitools' pricing is outdated in one source**, **Chromatic's listing is for a different product entirely**, and **several entries have no usable pricing**.

## The data problems

**Applitools' "$99–199/month" is outdated.** The Tencent article citing that figure is from April 2026 , but prior research in this conversation established that the free tier was removed and the lowest tier is **Starter at $667/month annual**. The search results here do not contain Applitools' current pricing page. **Do not cite the $99–199 figure.**

**Chromatic's Vendr listing is for Chromatic Labs (video generation), not Chromatic (Storybook visual testing).** The pricing page describes a credit-based video generation product with plans from $20–$200/month . The Vendr benchmark describes Enterprise contracts at $60K–$180K annually for snapshot-based visual testing . **These are two different companies with the same name.** Do not conflate them.

**BrowserStack's pricing page does not isolate Visual Regression Testing.** The tiers shown are Individual $39/month, Single User $150/month, and Team $249/month for App Live and App Automate . The visual comparison feature is mentioned in the page title but no standalone price is surfaced.

**LambdaTest SmartUI pricing is fragmented.** The search result mentions "visual regression with Smart UI" but provides no dollar figures . A separate page fragment shows "per parallel" and "screenshot testing" but is truncated .

## What the search results actually contain

**SaaS pricing (usable):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Argos** | **Hobby free** (5K screenshots); **Pro from $100/mo** (35K included); overage **$0.004/screenshot** (standard), **$0.0015** (Storybook) | 1-year retention on Pro; 30-day on Hobby  |
| **Happo.io** | **Starter $149/mo** (50K snapshots); **Growth $399/mo** (150K); **Pro $749/mo** (300K); Enterprise custom | Free plan: 5K snapshots/month in Chrome only  |
| **Sauce Labs** | **Virtual Device Cloud** includes **500 visual snapshots/month**; **Real Device Cloud $199/mo annual** or $249 monthly | Visual testing is an add-on, not standalone  |
| **Applitools** | **Not surfaced in these results** | Prior research: Starter $667/mo annual |
| **BrowserStack** | **Not isolated** | Tiers are for App Live/Automate  |
| **LambdaTest SmartUI** | **Not surfaced** |  |

**Open-source projects (usable):**

| Project | Stars | What it actually does |
|---|---|---|
| **reg-suit** | **1,130** | Visual regression testing tool; 68,674 weekly npm downloads  |
| **Visual Regression Tracker** | **629** | Backend and frontend for tracking image comparison differences  |

**Chromatic (Storybook visual testing) has no verified pricing in these results**—the Vendr benchmark  is transaction-derived, and the Chromatic Labs page  is a different product.

## What I recommend

**Split into two honest categories:**

**1. SaaS Visual Regression Platforms** (proprietary):
- **Argos** — Free 5K; Pro $100/mo (35K) 
- **Happo.io** — Starter $149/mo (50K) 
- **Sauce Labs** — Visual testing included with Virtual Device Cloud (500 snapshots) 
- **Applitools, BrowserStack, LambdaTest, Chromatic** — **pricing not surfaced in these results**

**2. Open-Source** (strong section):
- **reg-suit** — 1,130 stars, 68K weekly downloads 
- **Visual Regression Tracker** — 629 stars 

**Do not cite Applitools' $99–199 figure**—it conflicts with verified 2026 pricing. **Do not present Chromatic Labs (video) as Chromatic (visual testing)**—they are different products .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate Applitools or BrowserStack visual testing pricing, conflate Chromatic Labs with Chromatic, or present the Vendr benchmark as vendor-published.
