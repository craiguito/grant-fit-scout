# Grant Fit Scout

Grant Fit Scout is a self-serve Grants.gov lead scoring tool for grant writers, nonprofits, universities, workforce boards, community colleges, and proposal consultants.

The practical use case is not "scrape grants." It is: find the few federal funding opportunities worth reading this week.

It turns broad Grants.gov searches into a ranked triage list with:

- fit score
- deadline urgency
- days to close
- proposal workload estimate
- eligibility notes when available
- award details when available
- grantor contact details when available
- direct Grants.gov source links

## Run It

Paid production actor:

https://apify.com/nimble_flash/grant-fit-scout

Free demo:

https://craiguito-grant-fit-scout-demo.hf.space/?__theme=system

Pricing on Apify:

- $0.10 per qualified grant opportunity
- shown as $100 per 1,000 qualified opportunities
- default run returns up to 25 opportunities
- platform usage is included

## Example Use Cases

- A nonprofit wants to find workforce development grants worth reading this week.
- A grant writer wants a quick Grants.gov shortlist before spending time in NOFOs.
- A community college wants cybersecurity education opportunities with deadline and eligibility clues.
- A proposal consultant wants a repeatable lead watchlist for clients.

## Niche Landing Pages

- [Community college grants](https://craiguito.github.io/grant-fit-scout/community-college-grants.html)
- [Cybersecurity workforce grants](https://craiguito.github.io/grant-fit-scout/cybersecurity-workforce-grants.html)
- [Nonprofit workforce grants](https://craiguito.github.io/grant-fit-scout/nonprofit-workforce-grants.html)

## Sample Output

See:

- [Sample report](docs/sample-output.md)
- [Sample CSV](data/sample-grant-leads.csv)
- [Landing page](docs/index.html)

## What Buyers Get

Each paid run writes a dataset with proposal-facing fields:

- opportunity title
- agency
- status
- close date
- days to close
- urgency label
- fit score
- fit reasons
- matched keywords
- workload label
- eligibility summary
- award summary
- contact summary
- synopsis
- source URL

## Disclaimer

Grant Fit Scout is grant triage software. It does not apply for grants, guarantee eligibility, provide legal advice, or replace human NOFO review.
