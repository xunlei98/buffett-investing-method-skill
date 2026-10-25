# Buffett owner earnings and intrinsic value

## Main idea

How Buffett defines what a business is worth and which earnings figure he uses to value it.

## Why it matters

Part of Buffett's stated method for analysing a company; see [Buffett investing method](00-overview.md). This records what he says he does, not evidence that following it produces returns.

## Explanation or example

See the exact source passages below; the interpretation section restates them in plain English.

## Source claims and exact locations

Buffett's own words, quoted exactly. Locators: ¶N is the Nth paragraph of the converted Markdown text of that letter (see sources.md); use the section heading to find it in the original.

- “Intrinsic value can be defined simply: It is the discounted value of the cash that can be taken out of a business during its remaining life.” — An Owner's Manual (Owner-Related Business Principles) (Buffett Owners Manual), Intrinsic Value section, ¶50, PDF page 5.
- “The calculation of intrinsic value, though, is not so simple.” — An Owner's Manual (Owner-Related Business Principles) (Buffett Owners Manual), Intrinsic Value section, ¶51, PDF page 5.
- “the average annual amount of capitalized expenditures for plant and equipment, etc. that the business requires to fully maintain its long-term competitive position and its unit volume.” — Chairman's Letter to Shareholders, 1986 (with Appendix: Purchase-Price Accounting Adjustments and the "Cash Flow" Fallacy) (Buffett letter 1986), Appendix, ¶174.
- “we consider the owner earnings figure, not the GAAP figure, to be the relevant item for valuation purposes” — Chairman's Letter to Shareholders, 1986 (with Appendix: Purchase-Price Accounting Adjustments and the "Cash Flow" Fallacy) (Buffett letter 1986), Appendix, ¶175.
- “"I would rather be vaguely right than precisely wrong."” — Chairman's Letter to Shareholders, 1986 (with Appendix: Purchase-Price Accounting Adjustments and the "Cash Flow" Fallacy) (Buffett letter 1986), Appendix, ¶175.
- “businesses logically are worth far more than net tangible assets when they can be expected to produce earnings on such assets considerably in excess of market rates of return.” — Chairman's Letter to Shareholders, 1983 (with Appendix: Goodwill and its Amortization) (Buffett letter 1983), Appendix: Goodwill and its Amortization, ¶141.
- “Growth is always a component in the calculation of value” — Chairman's Letter to Shareholders, 1992 (Buffett letter 1992), Common Stock Investments, ¶73.

## Interpretation and uncertainty

(Interpretation, not Buffett's words.) Owner earnings, as defined in the 1986 appendix, are reported earnings plus depreciation and other non-cash charges, minus the average capital spending needed just to keep the business's competitive position and unit volume (plus any extra working capital it needs). Intrinsic value is the present value of the cash a business can hand over across its life. Growth is part of that calculation, not a separate style. Earning well above market rates on tangible assets is what creates economic goodwill.

These are Buffett's stated principles in Berkshire Hathaway's own publications. They describe his intent and reasoning, not a tested rule set. Verification: every quotation above was checked word for word against the original Berkshire text on 12 October 2026. That confirms the quotations are faithful; it does not prove the principles work.

## Operating model used with this method

(Our implementation, not Buffett's words; choose your own and write it down.)

- OE = operating cash flow - all capex - 10-year average acquisitions (outflows only, same-period revenue).
- Discount rate = 20-day average 10-year Treasury + 4% (quality tier) or +5% (standard). The premium compensates risk; it is not the margin of safety.
- 10-year forecast: years 1-3 growth at or below the company's own 10-year median OE growth (a signed-contract rate may be used only if lower); years 4-10 converge linearly to g.
- g = 20-day average 10-year breakeven inflation + 0.5%, rounded to 0.1pp, below the Treasury yield.
- No separate margin-of-safety multiplier.
- Quarterly recompute on 20-day averages, not spot rates.
- If one capex assumption swings the answer, publish both scenarios and take the lower value as the buy line.

## Related ideas

- [Buffett return on equity and capital allocation](04-roe-and-capital-allocation.md)
- [Buffett margin of safety and Mr. Market](07-margin-of-safety-and-mr-market.md)
- [Buffett investing method](00-overview.md)
