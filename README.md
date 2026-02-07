# Jersey-Patch-Valuation-Analysis

This project estimates the market value of sponsor logo placement on sports jerseys using a data-driven exposure and brand-visibility model.

Rather than relying on negotiated deal values alone, this project attempts to predict fair sponsorship pricing using observable signals such as:

- Media exposure
- Team popularity
- Market size
- Digital engagement
- Financial disclosures
- Comparable sponsorship deals

The goal is to build a replicable valuation framework that can estimate the expected dollar value of a jersey patch sponsorship across leagues, teams, and markets.

> Sponsorship Value ≈ Exposure × Audience Quality × Brand Visibility × Market Strength

## Potential Data Sources

### Media Exposure
These sources estimate **how often a jersey logo is seen.**
- Nielsen TV ratings data (game viewership)
- National broadcast schedules
- Playoff appearances
- Minutes played in nationally televised games

### Digital Attention
These sources estimate **fan engagement and brand visibility.**
- Google Trends search interest
- Team social media follower counts
- Engagement metrics (likes, shares, comments)
- Wikipedia page views (optional)

### Market & Demographic Data
These sources estimate **sponsor market reach.**
- Metropolitan Statistical Area (MSA) population
- DMA (Designated Market Area) size
- Census population data
- Regional income statistics

### Financial Disclosures
These sources estimate **organizational scale and sponsorship economics.**
- IRS Form 990 (Nonprofit Organizations)
    - IRS Section 501(c)(3) nonprofit organizations
- Schedule 14A (Proxy Statements)
- USA Today Database
- Sports Business Journal (SBJ) sponsorship databases
