# Canadian Tire Bank (canadian-tire-bank)

Canadian Tire Bank (operating as Canadian Tire Financial Services) is a federally regulated Schedule I bank, wholly owned by Canadian Tire Corporation, Limited and federally chartered in 2003. It is the financial-services arm of one of Canada's best-known retailers, issuing the Triangle Mastercard family of cards and offering high-interest savings accounts and GICs tied to the Triangle Rewards loyalty program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/canadian-tire-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/canadian-tire-bank/refs/heads/main/apis.yml)

## Open Finance Posture

Canadian Tire Bank exposes **no first-party public developer API or banking API portal**. Its posture reflects the honest reality of Canadian open finance today:

- **No first-party developer portal for the bank.** The `developer.cantire.com` portal is operated by the retail parent **Canadian Tire Corporation, Limited** (confirmed via its TLS certificate), not by the bank. It is gated behind sign-in and its certificate expired on 20 February 2026, indicating a dormant/neglected surface. It is a distinct retail entity and is not attributed to the bank here.
- **Consumer-Driven Banking (CDB) not yet live.** Canada's federal Consumer-Driven Banking framework (Budget 2024 and the Fall Economic Statement 2024, overseen by the Financial Consumer Agency of Canada / FCAC) is legislated but not operational, so access remains voluntary and fragmented.
- **Aggregator-based data access.** Canadian Tire Bank card and account data is reached through third-party aggregators — Finicity (by Mastercard), Flinks and Plaid — rather than a first-party API.
- **No documented FDX participation** and, being a Canadian institution, no US Section 1033 posture applies.

## Tags

- Financial Services
- Banking
- Canada
- Schedule I Bank
- Credit Cards
- Mastercard
- Consumer-Driven Banking
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public first-party APIs are documented by Canadian Tire Bank. Consumer data access is available only via third-party aggregators (Finicity, Flinks, Plaid).

## Common Properties

- [Website](https://www.ctfs.com)
- [About](https://www.ctfs.com/content/ctfs/en/about-us.html)
- [Terms Of Service / Legal](https://www.ctfs.com/content/ctfs3/en/legal.html)
- [LinkedIn](https://ca.linkedin.com/company/canadian-tire-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
