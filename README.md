# Buffett investing method skill

An agent skill that analyzes a public company the way Warren Buffett describes in his own writing: the Berkshire Hathaway Owner's Manual and nine shareholder letters (1977–2014). It walks an agent through eight steps, from circle of competence to a red-flags check, and produces a one-page verdict memo with a confidence level.

## Contents

- `SKILL.md`: the skill itself, with YAML frontmatter, the step-by-step procedure, the memo template and guardrails.
- `references/00-overview.md` to `references/08-lessons-from-mistakes.md`: one file per concept, with Buffett's exact quotes and locators (letter, section, paragraph).
- `references/sources.md`: the ten Berkshire sources, their official berkshirehathaway.com URLs, and what each contributes.

## How to use it

- **Skill-folder agents (Claude, Codex, Cursor and similar):** copy this folder into the agent's skills directory (for example `.claude/skills/buffett-investing-method/` or your tool's equivalent). The agent reads the `description` in `SKILL.md` and loads the skill when asked to analyze a company, judge a moat or value a business Buffett-style.
- **Any other agent or chat model:** paste the body of `SKILL.md` into the system prompt, and attach or paste the relevant `references/` files when you need the supporting quotes.
- Give the agent access to company filings and a way to run calculations (code or a spreadsheet); the skill tells it never to invent or hand-calculate figures.

## Recommended reading order

1. Circle of competence
2. Business-quality checklist (the four-part test)
3. Moats and durable competitive advantage
4. Return on equity and capital allocation
5. Management quality
6. Owner earnings and intrinsic value
7. Margin of safety and Mr. Market
8. Lessons from mistakes

Start with `references/00-overview.md`; the reference files are numbered in this order.

## Disclaimer

This skill records Warren Buffett's stated investing method as he describes it in Berkshire Hathaway publications. It is not a validated or back-tested trading strategy, not investment advice, and not affiliated with or endorsed by Warren Buffett or Berkshire Hathaway. Quotations are short and attributed; the full letters are © Warren E. Buffett / Berkshire Hathaway Inc. and are available free at <https://www.berkshirehathaway.com/>.
