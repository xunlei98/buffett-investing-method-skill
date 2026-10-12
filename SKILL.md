---
name: buffett-investing-method
description: Analyze a public company the way Warren Buffett describes in his Berkshire Hathaway letters. Use when asked to judge a company's business quality, durable competitive advantage (moat), return on equity and capital allocation, management, owner earnings and intrinsic value, or margin of safety "Buffett-style", or to write a Buffett-style verdict memo on a stock.
---

# Buffett investing method

Analyze a company as if buying the whole business, following Buffett's stated method in eight steps. Work through them in order: a failure at Step 1 ends the analysis. Quotes are Buffett's own words with letter year and section; details and more quotes are in `references/`, and source URLs in `references/sources.md`.

## Before you start

- Get the company's last 10 years of annual reports or filings (10-K/20-F or equivalent): income statement, balance sheet, cash-flow statement, segment data, share count, and the shareholder letters or MD&A.
- Get the current share price, shares outstanding, net debt and market capitalisation, with the date.
- Do every calculation with code or a spreadsheet, never by mental arithmetic, and show the inputs. If a figure is not in the data you have, write "not available"; never estimate it silently.

## Step 1. Circle of competence

> "You only have to be able to evaluate companies within your circle of competence. The size of that circle is not very important; knowing its boundaries, however, is vital." (1996, Common Stock Investments)

Ask:
1. Can I explain in two or three sentences how this company makes money, who pays it and why?
2. Can I name the main drivers of its revenue and costs?
3. Can I say with reasonable confidence what this business will look like in ten years?

Data: business description, segment revenue and profit, main products and customers.

Pass: clear answers to all three. Fail: any answer is vague, depends on unpredictable technology or regulation, or relies on a story you cannot check. If it fails, stop and report **"Outside circle of competence"** with the reason. Do not continue to valuation.

## Step 2. The four-part quality test

> "We want the business to be (1) one that we can understand, (2) with favorable long-term prospects, (3) operated by honest and competent people, and (4) available at a very attractive price." (1977, Insurance Investments)

Use this as the scorecard for the memo. Item (1) is Step 1; item (2) is Steps 3, 4 and 6; item (3) is Step 5; item (4) is Steps 6 and 7. Also apply the 1996 goal:

> "...purchase, at a rational price, a part interest in an easily-understandable business whose earnings are virtually certain to be materially higher five, ten and twenty years from now." (1996, Common Stock Investments)

Ask: are earnings very likely to be materially higher in five, ten and twenty years? Pass: yes, for reasons you can state. Fail: earnings are cyclical, shrinking or unpredictable.

## Step 3. Moat and durable competitive advantage

> "A truly great business must have an enduring “moat” that protects excellent returns on invested capital." (2007, Businesses – The Great, the Good and the Gruesome)
> "Severe change and exceptional returns usually don't mix." (1987, Sources of Reported Earnings)

Ask:
1. What protects this business from competitors: low-cost production, a powerful brand, or something else you can name? Buffett's 2007 examples are low-cost producers (GEICO, Costco) and world-wide brands (Coca-Cola, Gillette, American Express).
2. Has the business done much the same thing for five to ten years, in a stable industry?
3. Is it a "great", "good" or "gruesome" business in the 2007 sense? The gruesome kind "grows rapidly, requires significant capital to engender the growth, and then earns little or no money." (2007)

Data: 10 years of operating margin, return on invested capital, market share where available, pricing history, capital spending against growth.

Pass: a named, specific barrier, plus high and stable returns on capital over 10 years. Fail: no identifiable barrier, returns that fall to the cost of capital, or growth that consumes capital without earning on it.

## Step 4. Return on equity and capital allocation

> "...we believe a more appropriate measure of managerial economic performance to be return on equity capital." (1977, Opening)
> "We test the wisdom of retaining earnings by assessing whether retention, over time, delivers shareholders at least $1 of market value for each $1 retained." (Owner's Manual, Principle 9)

Calculate (deterministically):
- Return on equity each year for 10 years (net income ÷ average shareholders' equity). Note whether leverage, buybacks or unusual accounting distort it, as Buffett's 1977 caveat about unusual debt-equity ratios warns.
- Return on invested capital as a cross-check.
- The $1 test: increase in market value over 5 to 10 years compared with cumulative retained earnings (net income minus dividends) over the same period.
- How cash was used: reinvestment, acquisitions, dividends, buybacks, debt reduction.

Pass: consistently high returns on equity without heavy debt, and at least $1 of market value per $1 retained. Fail: per-share earnings rise only because equity grows, returns are low or falling, or retained earnings created less than $1 of value per $1.

Remember: "the best business to own is one that over an extended period can employ large amounts of incremental capital at very high rates of return." (1992, Common Stock Investments)

## Step 5. Management

> "Good jockeys will do well on good horses, but not on broken-down nags." (1989, Mistakes of the First Twenty-five Years)

Ask:
1. Are the managers honest? Do they report candidly, including mistakes? Is pay reasonable relative to results?
2. Are they competent at running the business and allocating capital (see Step 4)?
3. Do they resist "the institutional imperative" (1989): imitating peers, empire-building, deals for their own sake?

Data: shareholder letters over several years, proxy statement pay, insider ownership, acquisition history and results, restatements.

Pass: candid, owner-minded, with a sound capital-allocation record. Fail: promotional or evasive reporting, poor deals, pay unrelated to performance. Good managers do not rescue bad economics: when they meet, "it is the reputation of the business that remains intact." (1989)

## Step 6. Owner earnings and intrinsic value

> "Intrinsic value can be defined simply: It is the discounted value of the cash that can be taken out of a business during its remaining life." (Owner's Manual, Intrinsic Value)

Calculate owner earnings (1986, Appendix): reported earnings + depreciation, depletion, amortization and other non-cash charges − the average annual capital spending needed "to fully maintain its long-term competitive position and its unit volume" (plus any extra working capital needed for that). Maintenance capital spending is an estimate: state your assumption and a range. Buffett: "I would rather be vaguely right than precisely wrong." (1986)

Then estimate intrinsic value: discount future owner earnings with explicit growth and discount-rate assumptions, in conservative, base and optimistic cases. Growth belongs inside the calculation: "Growth is always a component in the calculation of value" (1992).

Pass: a value range you can defend line by line. Fail: the range is so wide, or so assumption-driven, that it says nothing; treat that as a circle-of-competence warning.

## Step 7. Margin of safety and Mr. Market

> "...we insist on a margin of safety in our purchase price." (1992, Common Stock Investments)
> "Mr. Market is there to serve you, not to guide you." (1987, Marketable Securities - Permanent Holdings)

Calculate: margin of safety = (intrinsic value − price) ÷ intrinsic value, using the conservative and base cases.

Pass: price is well below your conservative value. Buffett says he is not interested if value is "only slightly higher than its price" (1992); he gives no fixed percentage, so state the threshold you use and why. Fail: price at or above value, or a margin that exists only in the optimistic case.

Ignore price momentum, forecasts and market mood when judging value. A falling price for a business that still passes Steps 1 to 6 is a better opportunity, not a warning.

## Step 8. Mistakes and red-flags check

> "It's far better to buy a wonderful company at a fair price than a fair company at a wonderful price." (1989, Mistakes of the First Twenty-five Years)

Check each and record yes or no:
- Is this a cigar butt: cheap, but with poor economics? (1989; 2014, Charlie Straightens Me Out)
- Is the case mainly that the stock is cheap rather than that the business is excellent?
- Is it a capital-hungry, low-return "gruesome" business? (2007)
- Is the thesis relying on a turnaround of a business with bad economics? (1989)
- Would you be willing to hold it for ten years? "If you aren't willing to own a stock for ten years, don't even think about owning it for ten minutes." (1996)
- Any accounting oddities, heavy debt, or management behaviour flagged in Step 5?

Any "yes" lowers confidence; a cigar butt or gruesome business is a fail regardless of price.

## Output: one-page verdict memo

```
# [Company] (ticker): Buffett-method verdict
Date / price used / data sources:

Verdict: [Pass – would consider buying | Watch – good business, price too high | Fail | Outside circle of competence]
Confidence: [High | Medium | Low] – one sentence on why

1. Circle of competence: pass/fail – how it makes money in 2 sentences
2. Four-part test: understandable / long-term prospects / people / price – each pass/fail
3. Moat: [named barrier] – evidence (10-yr ROIC, margins) – great/good/gruesome
4. ROE & capital allocation: 10-yr ROE range; $1 test result; how cash was used
5. Management: honest? competent? institutional-imperative risk?
6. Owner earnings & intrinsic value: owner earnings [figure, formula, maintenance capex assumption]; value range (conservative/base/optimistic) with key assumptions
7. Margin of safety: price vs value; margin % in each case; threshold used
8. Red flags: list, or "none found"

Key Buffett quotes applied: 2–4 short quotes with year and section
What would change the verdict:
Data gaps:
```

## Guardrails

- This is Buffett's **stated** method from his own writing. It is not a validated or back-tested strategy, and the verdict is not investment advice.
- Never invent figures. Use only data you retrieved and cite where each number came from; mark missing data "not available".
- Do every calculation deterministically (code or spreadsheet) and show the inputs and formula.
- Keep Buffett's words (quoted, with year and section) separate from your own interpretation.
- Say "Outside circle of competence" and stop when Step 1 fails, rather than forcing an answer.
- Do not quote long passages from the letters; link to the official URLs in `references/sources.md`.
