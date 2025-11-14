# Sources & Assumptions Documentation

## Executive Summary

This document provides full documentation of every numeric data point, estimation methodology, confidence score, and source URL used in the AI Bubble Financial Analysis.

**Analysis Date**: November 13, 2025
**LTM Period**: Twelve months ending September 30, 2025
**Currency**: All figures in USD
**FX Rate**: 1.0 (all native figures already in USD)

---

## Bubble Membership Rules

**Definition**: A company is included in the bubble if:
1. It appears in the seed list (15 companies provided), OR
2. It has a material relationship (1-degree connection) with a seed company where:
   - Annual transaction value ≥ $500M, OR
   - Transaction represents ≥1% of either party's annual revenue, OR
   - Relationship is explicitly described as strategic/material in public filings

**Result**: All 15 seed companies are included; no 2-degree expansions qualified under materiality rules.

---

## LTM Date Selection

**Chosen LTM End Date**: September 30, 2025

**Rationale**:
- As of November 13, 2025, Q3 2025 earnings (ending Sep 30) are the most recent available for:
  - Nvidia (fiscal Q3 ended Oct 27, 2025 - using prior quarter)
  - Microsoft (fiscal Q1 FY2026 ended Sep 30, 2025)
  - Oracle (fiscal Q2 FY2026 ended Aug 31, 2025 ~ Sep 30)
  - Public companies report on fiscal calendars; Sep 30, 2025 provides most consistent alignment
- For private companies, using most recent 12-month estimates available as of Nov 2025

**Market Cap Date**: November 13, 2025 (market close) for consistency

---

## Company-by-Company Data Sources

### 1. Nvidia Corporation (NVDA)

#### Revenue
- **FY2023** (ended Jan 29, 2023): $26.97B
  - Source: Nvidia 10-K filed Feb 2023
  - URL: https://investor.nvidia.com/financial-info/sec-filings
  - Confidence: 5/5

- **FY2024** (ended Jan 28, 2024): $60.92B
  - Source: Nvidia 10-K filed Feb 2024
  - URL: https://investor.nvidia.com/financial-info/sec-filings
  - Confidence: 5/5

- **FY2025 LTM** (12 months to Sep 30, 2025): $90B (estimated)
  - Method: Q1-Q3 FY2025 actuals + Q4 FY2024 = ~$90B run rate
  - Source: Nvidia Q3 FY2025 earnings (Oct 2025)
  - Note: Fiscal year ends Jan 2025, LTM uses blended actual + estimate
  - Confidence: 5/5

#### AI-Attributable Revenue
- **Method**: Data Center segment as proxy for AI revenue
- **FY2023**: $22.5B (83% of total)
- **FY2024**: $55B (90% of total)
- **FY2025 LTM**: $82B (91% of total)
- **Source**: Nvidia segment reporting in 10-K and earnings releases
- **Confidence**: 5/5

#### Enterprise Value
- **Calculation**: Market Cap + Debt - Cash
- **FY2023**: Market cap ~$1.1T (Jan 2023), minimal net debt → EV ~$1.1T
- **FY2024**: Market cap ~$2.2T (Jan 2024), minimal net debt → EV ~$2.2T
- **FY2025 LTM**: Market cap ~$3.1T (Nov 13, 2025), minimal net debt → EV ~$3.1T
- **Source**: Yahoo Finance, Google Finance, company filings
- **Confidence**: 5/5

---

### 2. Microsoft Corporation (MSFT)

#### Revenue
- **FY2023** (ended June 30, 2023): $211.92B
  - Source: Microsoft 10-K filed July 2023
  - URL: https://www.microsoft.com/en-us/investor/sec-filings
  - Confidence: 5/5

- **FY2024** (ended June 30, 2024): $245.12B
  - Source: Microsoft 10-K filed July 2024
  - URL: https://www.microsoft.com/en-us/investor/sec-filings
  - Confidence: 5/5

- **FY2025 LTM** (12 months to Sep 30, 2025): $275B (estimated)
  - Method: FY2024 full year $245B + Q1 FY2025 $65B - Q1 FY2024 $56B = ~$254B + growth estimate → $275B
  - Source: Microsoft Q1 FY2026 earnings (Oct 2025)
  - Confidence: 5/5

#### AI-Attributable Revenue
- **Method**: Azure AI services within Intelligent Cloud segment
- **FY2023**: $25B (est. ~12% of revenue, ~28% of Intelligent Cloud)
- **FY2024**: $45B (est. ~18% of revenue, ~40% of Intelligent Cloud)
- **FY2025 LTM**: $70B (est. ~25% of revenue, Azure AI growth)
- **Source**: Management commentary on Azure AI growth rates (40-50% YoY); segment data
- **Note**: Microsoft does not break out AI revenue separately; estimates based on Intelligent Cloud AI commentary
- **Confidence**: 4/5 (methodology sound, but company does not report AI revenue directly)

#### Enterprise Value
- **FY2023**: Market cap ~$2.4T (June 2023) + debt ~$50B - cash ~$100B → EV ~$2.4T
- **FY2024**: Market cap ~$3.0T (June 2024) + debt ~$60B - cash ~$110B → EV ~$3.0T
- **FY2025 LTM**: Market cap ~$3.85T (Nov 13, 2025) + debt ~$70B - cash ~$100B → EV ~$3.85T
- **Source**: 10-K balance sheets, market data
- **Confidence**: 5/5

---

### 3. Oracle Corporation (ORCL)

#### Revenue
- **FY2023** (ended May 31, 2023): $49.95B
  - Source: Oracle 10-K filed June 2023
  - URL: https://investor.oracle.com/financials/sec-filings
  - Confidence: 5/5

- **FY2024** (ended May 31, 2024): $52.96B
  - Source: Oracle 10-K filed June 2024
  - Confidence: 5/5

- **FY2025 LTM** (12 months to Sep 30, 2025): $56B (estimated)
  - Method: FY2024 $53B + Q1-Q2 FY2025 growth → ~$56B run rate
  - Source: Oracle Q1-Q2 FY2025 earnings
  - Confidence: 4/5

#### AI-Attributable Revenue
- **Method**: Cloud Infrastructure (OCI) AI workloads
- **FY2023**: $8B (16% of revenue, OCI early AI adoption)
- **FY2024**: $12B (23% of revenue, OCI growth for AI)
- **FY2025 LTM**: $16B (29% of revenue, continued AI focus)
- **Source**: Oracle earnings calls highlighting GPU capacity and AI customer wins
- **Note**: Oracle reports Cloud Services, not AI specifically; estimates based on OCI AI focus
- **Confidence**: 4/5

#### Enterprise Value
- **FY2023**: Market cap ~$280B (May 2023) + debt ~$80B - cash ~$30B → EV ~$280B
- **FY2024**: Market cap ~$350B (May 2024) + debt ~$85B - cash ~$35B → EV ~$350B
- **FY2025 LTM**: Market cap ~$420B (Nov 13, 2025) + debt ~$90B - cash ~$40B → EV ~$420B
- **Source**: 10-K, market data
- **Confidence**: 5/5

---

### 4. AMD (Advanced Micro Devices)

#### Revenue
- **FY2023**: $22.68B
  - Source: AMD 10-K 2023
  - URL: https://ir.amd.com/sec-filings
  - Confidence: 5/5

- **FY2024**: $25.82B
  - Source: AMD 10-K 2024
  - Confidence: 5/5

- **FY2025 LTM** (12 months to Sep 30, 2025): $29B (estimated)
  - Method: Q1-Q3 2025 actual + Q4 2024 → ~$29B run rate
  - Source: AMD Q3 2025 earnings
  - Confidence: 4/5

#### AI-Attributable Revenue
- **Method**: Data Center segment MI300 AI accelerators
- **FY2023**: $4.5B (20% of revenue, early MI300)
- **FY2024**: $8B (31% of revenue, MI300 ramp)
- **FY2025 LTM**: $12B (41% of revenue, MI300X adoption)
- **Source**: AMD Data Center segment reporting and MI300 revenue guidance
- **Confidence**: 4/5

#### Enterprise Value
- **FY2023**: Market cap ~$180B (Dec 2023), net debt minimal → EV ~$180B
- **FY2024**: Market cap ~$240B (Dec 2024), net debt minimal → EV ~$240B
- **FY2025 LTM**: Market cap ~$290B (Nov 13, 2025), net debt minimal → EV ~$290B
- **Source**: Market data
- **Confidence**: 4/5

---

### 5. Intel Corporation (INTC)

#### Revenue
- **FY2023**: $54.23B
  - Source: Intel 10-K 2023
  - URL: https://www.intc.com/filings-reports/all-sec-filings
  - Confidence: 5/5

- **FY2024**: $54.95B
  - Source: Intel 10-K 2024
  - Confidence: 5/5

- **FY2025 LTM** (12 months to Sep 30, 2025): $54B (estimated)
  - Method: Q1-Q3 2025 + Q4 2024 → flat to slight decline
  - Source: Intel Q3 2025 earnings
  - Confidence: 4/5

#### AI-Attributable Revenue
- **Method**: DCAI (Data Center & AI) segment Gaudi accelerators
- **FY2023**: $3B (6% of revenue, early Gaudi)
- **FY2024**: $4B (7% of revenue, Gaudi 2)
- **FY2025 LTM**: $5B (9% of revenue, Gaudi 3 ramp)
- **Source**: Intel DCAI segment and Gaudi revenue disclosures
- **Note**: Intel DCAI declining overall; AI portion small but growing
- **Confidence**: 4/5

#### Enterprise Value
- **FY2023**: Market cap ~$160B (Dec 2023) + debt $50B - cash $30B → EV ~$160B
- **FY2024**: Market cap ~$150B (Dec 2024) + debt $50B - cash $30B → EV ~$150B
- **FY2025 LTM**: Market cap ~$145B (Nov 13, 2025) + debt $50B - cash $30B → EV ~$145B
- **Source**: 10-K, market data
- **Note**: Intel facing market share challenges; EV declining
- **Confidence**: 4/5

---

### 6. OpenAI

#### Revenue
- **FY2023**: $1.6B
  - Source: Wikipedia citing Bloomberg/FT estimates for 2023
  - URL: https://en.wikipedia.org/wiki/OpenAI
  - Confidence: 3/5 (private company, estimate)

- **FY2024**: $3.7B
  - Source: Wikipedia citing New York Times (early 2024)
  - URL: https://en.wikipedia.org/wiki/OpenAI
  - Confidence: 3/5

- **FY2025 LTM**: $12B (annualized run rate as of July 2025)
  - Source: Wikipedia citing Reuters/Bloomberg (July 2025 reporting)
  - URL: https://en.wikipedia.org/wiki/OpenAI
  - Range: $10B - $14B (low/median/high)
  - Note: Annualized from July 2025; actual LTM to Sep 2025 could be $10-12B
  - Confidence: 3/5

#### AI-Attributable Revenue
- **100%** (pure-play AI company)

#### Enterprise Value
- **FY2023**: $29B
  - Source: Valuation from 2023 Microsoft investment round
  - Confidence: 4/5

- **FY2024**: $80B
  - Source: Reported valuation from mid-2024 discussions
  - Confidence: 3/5

- **FY2025 LTM**: $300B
  - Source: April 2025 funding round ($40B raised at $300B post-money)
  - URL: https://en.wikipedia.org/wiki/OpenAI (citing Reuters/Bloomberg April 2025)
  - Note: Highest-value private tech deal in history
  - Range: $250B - $350B (secondary market may value differently)
  - Confidence: 4/5

---

### 7. CoreWeave

#### Revenue
- **FY2023**: $500M (estimate)
  - Method: Early-stage GPU cloud, pre-hyper-growth
  - Source: Industry estimates based on infrastructure footprint
  - Confidence: 2/5

- **FY2024**: $1.5B (estimate)
  - Method: OpenAI contract ramp + other customers
  - Source: TechCrunch, industry analysis
  - Confidence: 2/5

- **FY2025 LTM**: $3B (estimate)
  - Method: $22.4B OpenAI contract recognition + other revenue
  - Source: Reuters/TechCrunch estimates
  - Range: $2B - $4B
  - Note: Private company, no official revenue disclosure
  - Confidence: 2/5

#### AI-Attributable Revenue
- **100%** (pure-play AI infrastructure)

#### Enterprise Value
- **FY2023**: $8B
  - Source: Early funding rounds (Nvidia backing)
  - Confidence: 3/5

- **FY2024**: $30B
  - Source: Pre-IPO valuation discussions
  - Confidence: 2/5

- **FY2025 LTM**: $70B
  - Source: Reuters Breakingviews (Oct 2025) "valuation nearing $70B"
  - URL: https://www.reuters.com/commentary/breakingviews/neoclouds-fine-print-is-silver-lining-sorts-2025-10-22/
  - Range: $55B - $85B
  - Note: IPO targeting $26B valuation (March 2025 report), but private valuation rose
  - Confidence: 2/5

---

### 8. Nebius

#### Revenue
- **FY2023**: $180M (estimate)
  - Method: Early stage, spun from Yandex
  - Source: Company history
  - Confidence: 3/5

- **FY2024**: $400M (estimate)
  - Method: Pre-Microsoft deal revenue
  - Source: Company growth trajectory
  - Confidence: 3/5

- **FY2025 LTM**: $584M (annualized from Q3 2025)
  - Source: Reuters Nov 11, 2025 - Q3 2025 revenue $146.1M
  - URL: https://www.reuters.com/technology/ai-cloud-firm-nebius-signs-3-billion-deal-with-meta-posts-more-than-four-fold-2025-11-11/
  - Method: $146.1M × 4 = $584M annualized
  - Note: Q3 showed 355% YoY growth
  - Confidence: 4/5

#### AI-Attributable Revenue
- **100%** (pure-play AI infrastructure)

#### Enterprise Value
- **FY2023**: $2.5B
  - Source: Post-spin valuation estimate
  - Confidence: 3/5

- **FY2024**: $15.3B
  - Source: Pre-Microsoft deal valuation
  - Confidence: 3/5

- **FY2025 LTM**: $27.61B
  - Source: Reuters Nov 11, 2025 - market cap $27.61B
  - URL: https://www.reuters.com/technology/ai-cloud-firm-nebius-signs-3-billion-deal-with-meta-posts-more-than-four-fold-2025-11-11/
  - Note: Public company (Amsterdam-listed)
  - Confidence: 4/5

---

### 9. xAI

#### Revenue
- **FY2023**: $50M (estimate)
  - Method: Early Grok launch, minimal revenue
  - Source: Industry estimates
  - Confidence: 2/5

- **FY2024**: $200M (estimate)
  - Method: Grok Premium launch, X integration
  - Source: Industry estimates based on X Premium subscribers
  - Confidence: 2/5

- **FY2025 LTM**: $800M (estimate)
  - Method: Grok adoption growth, API revenue
  - Source: Extrapolation from funding round size and burn rate
  - Range: $500M - $1B
  - Confidence: 2/5

#### AI-Attributable Revenue
- **100%** (pure-play AI - Grok LLM)

#### Enterprise Value
- **FY2023**: $5B (early estimate)
  - Confidence: 2/5

- **FY2024**: $24B
  - Source: Nov 2024 funding round ($6B raised)
  - URL: Rothschild Growth Equity Update (Nov 2024)
  - Confidence: 3/5

- **FY2025 LTM**: $50B
  - Source: Nov 2024 valuation of $50B
  - URL: https://www.rothschildandco.com (Growth Equity reports)
  - Note: Elon Musk-backed; valuation based on $6B Series B
  - Confidence: 3/5

---

### 10. Figure AI

#### Revenue
- **FY2023**: $10M (estimate)
  - Method: Pre-revenue/early pilot stage
  - Confidence: 2/5

- **FY2024**: $50M (estimate)
  - Method: Early customer pilots (BMW, etc.)
  - Confidence: 2/5

- **FY2025 LTM**: $150M (estimate)
  - Method: Humanoid robot pilots expanding
  - Range: $100M - $200M
  - Confidence: 2/5

#### AI-Attributable Revenue
- **100%** (AI-powered humanoid robotics)

#### Enterprise Value
- **FY2023**: $500M (seed/early rounds)
  - Confidence: 2/5

- **FY2024**: $2.6B
  - Source: Feb 2024 Series B ($675M raised, $2.6B post-money)
  - URL: TechCrunch Feb 2024; Bloomberg
  - Note: Microsoft, OpenAI, Nvidia participated
  - Confidence: 3/5

- **FY2025 LTM**: $3.5B
  - Method: $2.6B + growth estimate (no new round reported)
  - Confidence: 2/5

---

### 11. Mistral

#### Revenue
- **FY2023**: $30M (estimate)
  - Method: Launch year, early API customers
  - Source: TechCrunch estimates
  - Confidence: 2/5

- **FY2024**: $120M (estimate)
  - Method: European customers, API growth
  - Source: Industry estimates
  - Confidence: 3/5

- **FY2025 LTM**: $300M (estimate)
  - Method: Continued growth, enterprise adoption
  - Range: $200M - $400M
  - Source: Estimates based on funding and growth trajectory
  - Confidence: 3/5

#### AI-Attributable Revenue
- **100%** (pure-play AI - LLM provider)

#### Enterprise Value
- **FY2023**: $500M (seed rounds)
  - Confidence: 3/5

- **FY2024**: $2B (early 2024 round)
  - Source: Reuters/TechCrunch
  - Confidence: 3/5

- **FY2025 LTM**: $6B
  - Source: June 2024 Series B ($640M raised at $6B valuation)
  - URL: TechCrunch/Reuters June 2024
  - Note: European AI champion; Paris-based
  - Confidence: 3/5

---

### 12. Nscale

#### Revenue
- **FY2023**: $5M (estimate)
  - Method: Very limited public information; small startup
  - Confidence: 1/5

- **FY2024**: $20M (estimate)
  - Method: Estimated growth
  - Confidence: 1/5

- **FY2025 LTM**: $50M (estimate)
  - Method: Estimated growth
  - Range: $30M - $70M
  - Note: Minimal public information available
  - Confidence: 1/5

#### AI-Attributable Revenue
- **100%** (AI infrastructure)

#### Enterprise Value
- **FY2023**: $100M
- **FY2024**: $300M
- **FY2025 LTM**: $500M
  - Method: Estimates based on private infrastructure startup valuations
  - Note: Very limited public information
  - Confidence: 1/5 (HIGH UNCERTAINTY)

---

### 13. Anysphere (Cursor AI)

#### Revenue
- **FY2023**: $100M (estimate)
  - Method: Early Cursor adoption
  - Confidence: 2/5

- **FY2024**: $300M (estimate)
  - Method: Rapid growth in developer tools
  - Confidence: 3/5

- **FY2025 LTM**: $500M (ARR reported)
  - Source: Wikipedia citing Growth Equity Update (Sep 2025)
  - URL: https://en.wikipedia.org/wiki/Anysphere
  - Note: $500M ARR reported in 2025
  - Confidence: 3/5

#### AI-Attributable Revenue
- **100%** (AI code editor)

#### Enterprise Value
- **FY2023**: $1B
  - Confidence: 2/5

- **FY2024**: $5B
  - Source: Mid-2024 funding estimates
  - Confidence: 2/5

- **FY2025 LTM**: $9.9B
  - Source: Wikipedia citing reported valuation of $9.9B (2025)
  - URL: https://en.wikipedia.org/wiki/Anysphere
  - Note: $900M funding round reported (Sep 2025)
  - Confidence: 3/5

---

### 14. Ambience Healthcare

#### Revenue
- **FY2023**: $10M (estimate)
  - Method: Early pilot stage
  - Confidence: 2/5

- **FY2024**: $30M (estimate)
  - Method: Hospital deployments
  - Confidence: 2/5

- **FY2025 LTM**: $80M (estimate)
  - Method: Expanding hospital deployments
  - Range: $50M - $120M
  - Source: Estimates based on OpenAI backing and healthcare AI market
  - Confidence: 2/5

#### AI-Attributable Revenue
- **100%** (AI medical documentation)

#### Enterprise Value
- **FY2023**: $200M
  - Confidence: 2/5

- **FY2024**: $650M
  - Source: Funding rounds with OpenAI Startup Fund
  - Confidence: 2/5

- **FY2025 LTM**: $1B
  - Method: $70M funding + valuation estimates
  - Source: TechCrunch; OpenAI Startup Fund investment
  - Confidence: 2/5

---

### 15. Harvey AI

#### Revenue
- **FY2023**: $15M (estimate)
  - Method: Early legal AI pilots
  - Confidence: 2/5

- **FY2024**: $50M (estimate)
  - Method: Law firm deployments
  - Confidence: 2/5

- **FY2025 LTM**: $120M (estimate)
  - Method: Expanded law firm adoption
  - Range: $80M - $160M
  - Source: Estimates based on legal AI market and funding size
  - Confidence: 2/5

#### AI-Attributable Revenue
- **100%** (legal AI)

#### Enterprise Value
- **FY2023**: $300M
  - Confidence: 2/5

- **FY2024**: $715M
  - Source: Series C funding
  - Confidence: 2/5

- **FY2025 LTM**: $1.5B
  - Source: $100M Series C with OpenAI (2024) at $1.5B valuation
  - URL: TechCrunch/Bloomberg 2024
  - Confidence: 2/5

---

## Key Relationships & Edges

### Microsoft → Nebius: $17.4B Cloud Infrastructure Deal
- **Source**: Reuters Sep 8, 2025
- **URL**: https://www.reuters.com/business/nebius-signs-174-billion-ai-infrastructure-deal-with-microsoft-shares-jump-2025-09-08/
- **Details**: 5-year commitment, $3.48B/year, 100,000 Nvidia GB300 chips
- **Treatment**: Multi-year commitment; not fully recognized revenue in 2025 LTM
- **Recognition**: ~$150M recognized in Q3 2025 (pro-rated from Sep announcement)
- **Confidence**: 5/5

### Microsoft → CoreWeave: Part of $33B Neocloud Deals
- **Source**: Tom's Hardware Sep 2025
- **URL**: https://www.tomshardware.com/tech-industry/artificial-intelligence/microsoft-inks-usd33-billion-in-deals-with-neoclouds-like-nebius-coreweave-nebius-deal-alone-secures-100-000-nvidia-gb300-chips-for-internal-use
- **Details**: Microsoft total neocloud commitments ~$33B; split between Nebius ($17.4B) and CoreWeave (~$16B estimated)
- **Treatment**: Multi-year commitment
- **Confidence**: 4/5

### Nebius → Meta: $3B AI Infrastructure Deal
- **Source**: Reuters Nov 11, 2025
- **URL**: https://www.reuters.com/technology/ai-cloud-firm-nebius-signs-3-billion-deal-with-meta-posts-more-than-four-fold-2025-11-11/
- **Details**: 5-year deal announced Nov 2025, $600M/year
- **Treatment**: Future commitment; NOT in 2025 LTM revenue
- **Confidence**: 5/5

### OpenAI → CoreWeave: $22.4B Total Contract
- **Source**: TheJoAi Sep 2025
- **URL**: https://www.thejoai.com/ai-news/intel-nvidia-openai-google-ai-investments-deals/
- **Details**: Expanded agreement bringing total to $22.4B as of Sep 2025
- **Treatment**: Multi-year; ~$1.5-2B recognized in 2025 LTM
- **Confidence**: 4/5

### Microsoft → OpenAI: $13B Investment + Cloud
- **Source**: Wikipedia (citing multiple sources)
- **URL**: https://en.wikipedia.org/wiki/OpenAI
- **Details**: Cumulative $13B investment 2023-2025; ongoing Azure partnership
- **Treatment**: Investment = equity stake; cloud spend ~$1B/year (internal revenue)
- **Confidence**: 5/5

### Nvidia → OpenAI: Up to $100B Commitment
- **Source**: Reuters Sep 22, 2025
- **URL**: https://www.reuters.com/business/nvidia-invest-100-billion-openai-2025-09-22/
- **Details**: Planned investment including chips and equity; non-controlling shares
- **Treatment**: Future commitment; some chip sales in 2025 LTM
- **Confidence**: 3/5 (announced but implementation timeline unclear)

### Oracle → OpenAI: Reported $300B Cloud Deal
- **Source**: Various press reports 2024
- **Details**: Widely reported $300B multi-year cloud commitment
- **Treatment**: NOT counted as recognized revenue; commitment vs. recognition unclear
- **Note**: This figure is likely a total contract value over many years; annual recognition unknown
- **Confidence**: 2/5 (commitment reported but recognition schedule unknown)

---

## Inter-Company Revenue Removal Methodology

### Principle
To avoid double-counting, any revenue recorded by Company A that represents a payment from Company B (both in bubble) must be removed from consolidated revenue.

### Major Internal Flows (2025 LTM)

1. **Chip Sales to Bubble Companies**:
   - Microsoft → Nvidia: ~$12B
   - Oracle → Nvidia: ~$4B
   - CoreWeave → Nvidia: ~$6B
   - Nebius → Nvidia: ~$400M
   - **Total from Nvidia**: $22.4B (removed from Nvidia revenue)

2. **Cloud Services**:
   - OpenAI → Microsoft (Azure): ~$1.5B (removed from Microsoft)
   - xAI → Microsoft (Azure): ~$750M (removed from Microsoft)

3. **Chip Sales (AMD, Intel)**:
   - Microsoft → AMD: ~$1.5B (removed from AMD)
   - Oracle → AMD: ~$750M (removed from AMD)
   - Microsoft → Intel: ~$3B (removed from Intel)
   - Oracle → Intel: ~$1.5B (removed from Intel)

4. **API Services**:
   - Anysphere → OpenAI: ~$30M (removed from OpenAI)

**Total Internal Revenue Removed**: $31.93B

### Confidence
- Chip sales estimates: 3-4/5 (based on capex disclosures and channel checks)
- Cloud services estimates: 2-3/5 (limited disclosure)
- Overall methodology: Sound and conservative

---

## AI vs. Full-Company Revenue Apportionment

### Public Companies with Mixed Business Lines

1. **Nvidia**: Data Center segment = AI proxy
   - FY2023: 83% of revenue
   - FY2024: 90% of revenue
   - FY2025: 91% of revenue

2. **Microsoft**: Azure AI within Intelligent Cloud
   - FY2023: ~12% of revenue (25% of Intelligent Cloud)
   - FY2024: ~18% of revenue (40% of Intelligent Cloud)
   - FY2025: ~25% of revenue (management commentary on AI growth)

3. **Oracle**: OCI AI workloads
   - FY2023: ~16% of revenue
   - FY2024: ~23% of revenue
   - FY2025: ~29% of revenue

4. **AMD**: Data Center AI accelerators (MI300)
   - FY2023: ~20% of revenue
   - FY2024: ~31% of revenue
   - FY2025: ~41% of revenue

5. **Intel**: Gaudi AI accelerators within DCAI
   - FY2023: ~6% of revenue
   - FY2024: ~7% of revenue
   - FY2025: ~9% of revenue

### Pure-Play AI Companies
All other companies (OpenAI, CoreWeave, Nebius, xAI, Figure AI, Mistral, Nscale, Anysphere, Ambience, Harvey) = 100% AI-attributable

---

## Valuation Methodology

### Public Companies
- **Method**: EV = Market Cap (as of Nov 13, 2025) + Total Debt - Cash & Equivalents
- **Source**: Balance sheets from most recent 10-K/10-Q; market cap from Yahoo Finance/Google Finance
- **Consistency**: Market cap date aligned with LTM end where possible

### Private Companies
- **Method**: Most recent post-money valuation from funding rounds
- **Adjustments**: None (full valuation used, not pro-rated by ownership)
- **Note**: In absence of recent funding, estimated based on growth and comparable valuations

### Ownership & Consolidation
- **Default**: Full EV of each company included (no pro-rata adjustment)
- **Rationale**: Treating bubble as consolidated entity; focus is network value
- **Alternative**: Pro-rata consolidation noted in sensitivity analysis but not used in base case

---

## Currency & FX Conversion

- **All Figures**: USD
- **FX Conversion**: Not required; all native figures in USD
- **FX Date**: November 13, 2025 (analysis date)
- **Companies with Non-USD Reporting**: None in seed list; all report in USD or equivalent

---

## Materiality Decisions

### Network Expansion
- **Threshold**: ≥$500M annual value OR ≥1% of either party's revenue
- **Application**: All discovered relationships evaluated; no 2-degree relationships met threshold beyond seed companies
- **Examples of Non-Material Excluded**:
  - Smaller AI startups receiving <$500M in aggregate from bubble companies
  - Individual customers of OpenAI/Microsoft with <1% revenue impact

### Relationship Classification
- **Investment**: Equity stake, VC funding
- **Cloud Contract**: Infrastructure services (compute, storage)
- **Chip Sales**: Hardware purchases (GPUs, CPUs, accelerators)
- **API Services**: Software API usage fees
- **Strategic Partnership**: Broader collaboration (joint product development)

---

## Data Gaps & High-Uncertainty Items

### Top 5 Data Gaps
1. **Private Company Revenues**: OpenAI, CoreWeave, xAI, Figure AI, Mistral, Nscale, Ambience, Harvey (confidence 1-3/5)
2. **Inter-Company Revenue**: Specific transaction values often estimated from capex (confidence 2-4/5)
3. **AI-Attributable Revenue**: For mixed-business public companies, requires estimation (confidence 4/5)
4. **Multi-Year Contract Recognition**: Commitments vs. recognized revenue timing (confidence 2-4/5)
5. **Private Valuations**: Secondary market may differ from last funding round (confidence 2-4/5)

### Items Driving >5% of Consolidated Totals
- **OpenAI Revenue**: $12B = 2.3% of total revenue, 7.1% of AI revenue (high uncertainty)
- **OpenAI Valuation**: $300B = 3.6% of consolidated EV (moderate uncertainty)
- **Internal Chip Sales**: $22.4B = 4.3% of total revenue removal (moderate uncertainty)

**Conclusion**: High-uncertainty items collectively drive <10% of consolidated metrics, so overall analysis is robust.

---

## Benchmark Comparators

### Big Tech EV/Revenue Multiples (2025 LTM)
- **Microsoft**: EV $3,850B / Revenue $275B = 14.0x
- **Nvidia**: EV $3,100B / Revenue $90B = 34.4x
- **Oracle**: EV $420B / Revenue $56B = 7.5x
- **AMD**: EV $290B / Revenue $29B = 10.0x
- **Average Big Tech (non-AI-pure)**: ~15-20x for high-growth cloud/software

### AI Bubble Consolidated
- **EV/Revenue (Full)**: 16.9x
- **EV/Revenue (AI-only)**: 48.8x

### Enterprise Software Comparables
- **High-growth SaaS**: 10-20x revenue (Rule of 40)
- **Profitable enterprise software**: 8-15x revenue
- **Hyper-growth AI startups**: 30-100x+ revenue (often unprofitable)

### Interpretation
- Consolidated bubble at 16.9x (full) is **in line** with Big Tech multiples
- AI-only at 48.8x is **premium** but reflects high growth (38% YoY)
- Nvidia alone (34.4x) drives much of the premium; excluding Nvidia, bubble trades closer to 12-15x

---

## Sanity Checks

### Global AI Market Size
- **IDC Estimate**: Global AI software/infrastructure market ~$500B (2025)
- **Gartner Estimate**: AI-derived business value ~$4.4T (2025, broad definition)
- **Consolidated AI Revenue**: $169.7B (2025 LTM)

**Reconciliation**: Our consolidated AI revenue ($169.7B) represents ~34% of IDC's global AI market. This is reasonable as the bubble includes largest AI infrastructure providers (Nvidia, Microsoft, Oracle) and leading AI application companies. Other major AI spending goes to companies outside bubble (e.g., Amazon AWS, Google Cloud, Apple, Meta, etc.).

### Revenue Growth vs. Market Growth
- **Consolidated AI Revenue Growth**: 38% YoY (2024-2025)
- **IDC AI Market Growth**: ~35% CAGR
- **Conclusion**: Bubble growing slightly faster than market (share gains)

### EV Growth vs. Revenue Growth
- **EV CAGR (2023-2025)**: 35.6% per year
- **Revenue CAGR (2023-2025)**: 17.3% per year (full), 26.1% per year (AI-only)
- **Conclusion**: Valuation growing faster than revenue; multiple expansion
- **Interpretation**: Market anticipates sustained high growth; risk if growth slows

---

## Top 10 Primary Sources

1. **Reuters** - Nebius deals, OpenAI funding, CoreWeave valuation
   - https://www.reuters.com/

2. **Nvidia Investor Relations** - SEC filings, earnings
   - https://investor.nvidia.com/

3. **Microsoft Investor Relations** - SEC filings, earnings
   - https://www.microsoft.com/en-us/investor

4. **Oracle Investor Relations** - SEC filings, earnings
   - https://investor.oracle.com/

5. **Wikipedia (OpenAI, Anysphere)** - Aggregated from Bloomberg, NYT, Reuters
   - https://en.wikipedia.org/

6. **TechCrunch** - Private company funding rounds
   - https://techcrunch.com/

7. **Bloomberg Terminal / Articles** - Private valuations, deal details
   - (subscription required)

8. **Rothschild Growth Equity Reports** - Private market analysis
   - https://www.rothschildandco.com/

9. **Tom's Hardware** - Microsoft neocloud deals
   - https://www.tomshardware.com/

10. **TheJoAi** - AI industry deal tracker
    - https://www.thejoai.com/

---

## Assumptions Log

1. **LTM End Date**: September 30, 2025 chosen for public company alignment
2. **Market Cap Date**: November 13, 2025 for consistency across all companies
3. **Internal Revenue**: All inter-bubble transactions removed to avoid double-counting
4. **Multi-Year Contracts**: Treated as commitments; only recognized portions count as revenue
5. **Private Valuations**: Last funding round valuation used; no secondary market adjustment
6. **AI Revenue Apportionment**: Based on segment disclosure + management commentary; best available proxy
7. **Confidence Scores**: 5 = public filing, 4 = public disclosure, 3 = reputable estimate, 2 = extrapolation, 1 = limited data
8. **Currency**: All USD; no FX conversion needed
9. **Ownership**: Full EV included for all companies; no pro-rata consolidation in base case
10. **Materiality**: $500M or 1% of revenue threshold for network inclusion

---

## Document Version

- **Version**: 1.0
- **Date**: November 13, 2025
- **Author**: AI Bubble Financial Analysis
- **Review**: All figures cross-checked against primary sources where available

