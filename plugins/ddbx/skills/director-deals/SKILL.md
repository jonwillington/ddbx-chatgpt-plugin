---
name: director-deals
description: Find, verify, and summarize public director dealings, insider trades, and management share transactions for a company, ticker, market, sector, or time period. Use when the user asks about director buys or sells, insider trading disclosures, PDMR dealings, Form 4 transactions, or executive share activity.
---

# DDBX Director Deals

Research public, lawfully disclosed director and insider share transactions. This skill provides research and context, not investment advice or a trading recommendation.

## Research workflow

1. Resolve the entity before searching. Confirm the legal issuer, exchange, country, ticker, and requested date window. Ask a short clarification only if the company name is ambiguous.
2. Search the appropriate primary disclosure source first:
   - US issuers: SEC EDGAR Form 3, 4, and 5 filings.
   - UK and many European issuers: exchange regulatory-news feeds and issuer announcements marked director/PDMR dealings.
   - Canadian issuers: SEDI filings.
   - Australian issuers: ASX Appendix 3Y notices.
   - Other markets: the local exchange, regulator, or issuer investor-relations announcement.
3. Supplement the filing with reputable financial-news coverage only when it adds useful context. Never let a secondary source override the primary disclosure.
4. Extract the transaction details exactly as reported: filing date, transaction date, person and role, security, code/type, buy or sell direction, quantity, price or price range, total value when reported or safely calculable, and holdings after the transaction when available.
5. Check for footnotes, 10b5-1 plans, option exercises, tax-withholding sales, gifts, indirect ownership, and multiple linked transactions. These can materially change the meaning of a headline number.

## Response format

Start with a direct answer, including whether qualifying deals were found in the requested period. Then present a compact table:

| Transaction date | Director / role | Direction | Security | Shares | Price | Reported or calculated value | Primary source |
| --- | --- | --- | --- | ---: | ---: | ---: | --- |

After the table, add a brief **Context** note that identifies relevant filing caveats and whether the activity is purchases, discretionary sales, plan sales, options-related activity, or another category.

## Evidence rules

- Link every material transaction to the primary filing or announcement. Include a secondary link only as supplemental context.
- State the date range and source searched when reporting no results.
- Use the disclosure's currency. Do not convert currencies unless asked; label any conversion with its rate date and source.
- If price is a range, preserve the range rather than inventing a single price.
- If calculating value, label it as an estimate and show the arithmetic. Do not calculate when the filing makes the inputs uncertain.
- Never describe a transaction as illegal "insider trading" merely because it is an insider transaction. Use "director dealing" or "insider transaction" unless wrongdoing has been established by an authoritative source.
- Separate facts from interpretation. Do not infer future price performance or make a buy/sell recommendation.
