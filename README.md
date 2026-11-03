### Andrea Tonelli

Physician (MBChB) and final-year PhD candidate in cardiovascular biomaterials at the University of Cape Town.
I build research software and run production systems by directing AI coding agents: I decide what gets
built, set the controls and verify the result; the agents write the code.

**Research: evidence → code**

| Question | Published evidence | Code |
|---|---|---|
| Which scaffold pore networks let blood vessels grow in? | *Materials Today Bio* 2026;39:103377 ([doi](https://doi.org/10.1016/j.mtbio.2026.103377)) | [growth-tunnel-analysis](https://github.com/andtoni/growth-tunnel-analysis): pore-network extraction from micro-CT (Python, PoreSpy, OpenPNM); MIT, archived on Zenodo ([doi](https://doi.org/10.5281/zenodo.20308262)) |
| Can a fast, low-resolution micro-CT scan stand in for a slow, high-resolution one? | Manuscript in preparation | [microct-superresolution](https://github.com/andtoni/microct-superresolution): deep-learning super-resolution and segmentation (PyTorch, nnU-Net, Snakemake) |

**Systems I run**

- [briefing](https://github.com/andtoni/briefing): a twice-daily newspaper that Claude edits from my feeds
  and newsletters, delivered as HTML, PDF and a Kindle EPUB.
- [finance-sync-core](https://github.com/andtoni/finance-sync-core): reconciles bank and brokerage data from six
  US and South African institutions into a household ledger, with a receipt for every write (TypeScript, PostgreSQL).
- [wealthfolio-fork](https://github.com/andtoni/wealthfolio-fork): my fork of an open-source portfolio app,
  with bank-fed spending, budgets and category suggestions (Rust, React).
- A self-hosted GPU server defined entirely as code, including local document AI that reads and files
  scanned records without a cloud service (private).

**How I work.** 1,546 merged pull requests since July 2026, each through a required CI job, security scans
and an AI code review that must post before merge. The method, the controls and what went wrong:
[agentic-engineering](https://github.com/andtoni/agentic-engineering).

Repositories marked *public mirror* are sanitised copies of private repositories: secrets, personal data and
infrastructure details are removed, and every update passes a leak check before it is published.

[ORCID 0000-0002-1601-4103](https://orcid.org/0000-0002-1601-4103)
