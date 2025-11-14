# AI Bubble Financial Analysis

## Quick Start

**See [FINAL_RESULTS.md](FINAL_RESULTS.md) for the complete analysis summary, consolidated numbers table, and interpretation.**

---

## Overview

This analysis treats the AI ecosystem as a consolidated entity, examining 15 seed companies and their material relationships to produce consolidated outside revenue and enterprise value for 2023, 2024, and 2025 LTM (ending September 30, 2025).

### Seed Companies
1. Nvidia
2. OpenAI  
3. Microsoft
4. Oracle
5. AMD
6. Intel
7. CoreWeave
8. Nebius
9. xAI
10. Figure AI
11. Mistral
12. Nscale
13. Anysphere (Cursor AI)
14. Ambience Healthcare
15. Harvey AI

---

## Key Results (2025 LTM)

- **Consolidated Outside Revenue**: $488.65 billion
- **Consolidated Enterprise Value**: $8,275.0 billion  
- **EV/Revenue Multiple**: 16.9x (full), 48.8x (AI-only)
- **Revenue Growth (2023-2025)**: 17.3% CAGR
- **EV Growth (2023-2025)**: 35.6% CAGR
- **Conclusion**: **Valuation growing ~2x faster than revenue**

---

## File Structure

### Core Deliverables
| File | Description |
|------|-------------|
| **[FINAL_RESULTS.md](FINAL_RESULTS.md)** | Complete results with upfront table, interpretation, top 10 sources |
| **[executive_summary.md](executive_summary.md)** | 300-400 word executive summary with 3-point sensitivity |
| **[nodes.csv](nodes.csv)** | All 15 companies with financial data (revenue, EV, confidence scores) |
| **[edges.csv](edges.csv)** | Network relationships with transaction values and citations |
| **[consolidated_summary.csv](consolidated_summary.csv)** | Summary metrics for 2023, 2024, 2025 LTM |
| **[consolidated.json](consolidated.json)** | Structured JSON with full data and metadata |

### Supporting Documentation
| File | Description |
|------|-------------|
| **[sources_and_assumptions.md](sources_and_assumptions.md)** | Every data point with URL, confidence score, and methodology |
| **[sensitivity_analysis.md](sensitivity_analysis.md)** | Impact of ±20% changes on top 5 uncertain items |
| **[top_contributors.csv](top_contributors.csv)** | Companies ranked by % of revenue and % of EV |
| **[internal_revenue_analysis.md](internal_revenue_analysis.md)** | Detailed inter-company revenue removal |
| **[consolidated_calculations.md](consolidated_calculations.md)** | Full calculation workings for all three periods |

### Visualization Data
| File | Description |
|------|-------------|
| **[visualization_revenue_flows.csv](visualization_revenue_flows.csv)** | Sankey diagram data (internal vs external flows) |
| **[visualization_top_external_revenue.csv](visualization_top_external_revenue.csv)** | Top 10 revenue contributors |
| **[visualization_top_ev_contributors.csv](visualization_top_ev_contributors.csv)** | Top 10 EV contributors |

---

## Methodology

### Bubble Membership
- **Included**: All 15 seed companies
- **Materiality Threshold**: 1-degree relationships with ≥$500M annual value OR ≥1% of revenue
- **Result**: No 2-degree expansions qualified; network = 15 seed companies

### Data Collection
- **Public Companies**: SEC filings (10-K, 10-Q) from EDGAR
- **Private Companies**: Best available estimates from FT, WSJ, Bloomberg, Reuters, TechCrunch
- **Confidence Scores**: 5 = SEC filing, 4 = public disclosure, 3 = reputable estimate, 2 = extrapolation, 1 = limited data

### Consolidation Rules
1. **Outside Revenue** = Total revenue - Internal revenue (bubble-to-bubble payments)
2. **Enterprise Value** = Sum of individual EVs (market cap + debt - cash for public; last funding round for private)
3. **AI-Attributable** = Segment disclosure (public) or 100% (private pure-plays)
4. **Commitments** = Multi-year contracts NOT counted as revenue unless recognition confirmed

### Internal Revenue Removed (2025 LTM)
- Chip sales (Nvidia to Microsoft/Oracle/CoreWeave/Nebius): $22.4B
- Cloud services (OpenAI/xAI to Microsoft): $2.25B
- AMD/Intel sales to Microsoft/Oracle: $6.75B
- API services (Anysphere to OpenAI): $30M
- **Total**: $31.93B

---

## Key Findings

### 1. Multiple Expansion Drives Valuation
- EV/Revenue expanded from 11.7x (2023) to 16.9x (2025 LTM)
- Valuation CAGR (35.6%) nearly 2x revenue CAGR (17.3%)
- **Interpretation**: Market anticipating sustained high growth; risk if growth slows

### 2. Concentration Risk
- Microsoft (46.5% of EV) + Nvidia (37.5% of EV) = 84% of consolidated value
- Top 5 companies = 94% of consolidated EV
- **Implication**: Bubble highly sensitive to Nvidia/Microsoft stock prices

### 3. AI Revenue Growth Decelerating
- 2023→2024: +46.7%  
- 2024→2025: +38.2%
- Still strong, but slowing from hyper-growth phase

### 4. Private AI Valuations Immaterial
- OpenAI + CoreWeave + xAI + others = 8% of consolidated EV
- 40% correction in private AI valuations → only 2.1% impact on consolidated EV
- **Implication**: Private AI "froth" is noise; public tech multiples drive bubble valuation

### 5. Internal Dependencies Create Fragility
- $32B of circular revenue flows (e.g., Microsoft funds OpenAI → OpenAI pays Microsoft Azure)
- Any break in the chain affects multiple companies

---

## Sensitivity Analysis Summary

| Scenario | EV Impact | EV/Revenue | Implication |
|----------|-----------|------------|-------------|
| **Top-5 uncertainties ±20%** | ±$74B (±0.9%) | 16.7-17.1x | Analysis robust to data gaps |
| **Private AI correction -40%** | -$174B (-2.1%) | 16.6x | Private valuations immaterial |
| **Public tech selloff -20%** | -$1,532B (-18.5%) | 13.8x | **KEY RISK**: 84% in 2 stocks |

**Takeaway**: Bubble valuation driven by public tech (especially Nvidia/Microsoft), not private AI hype.

---

## Confidence Assessment

### High Confidence (≥90%)
- Consolidated revenue and EV calculations
- Conclusion that valuation is growing faster than revenue  
- Finding that Microsoft + Nvidia dominate (84% of EV)

### Moderate Confidence (70-90%)
- AI-attributable revenue estimates (segment disclosure-based)
- Inter-company revenue removal ($32B estimate)
- Private company valuations (last funding round)

### Lower Confidence (50-70%)
- Specific revenue figures for CoreWeave, xAI, Figure AI, smaller privates
- Future contract recognition schedules
- Precise market cap dates for some estimates

**Overall**: Despite data gaps in private companies (8% of EV), analysis conclusions are robust.

---

## Data Sources

### Primary Sources (Public Companies)
- **SEC EDGAR** - 10-K, 10-Q filings for Nvidia, Microsoft, Oracle, AMD, Intel
- **Company Investor Relations** - Earnings releases, presentations

### Secondary Sources (Private Companies)
- **Reuters, Bloomberg, FT, WSJ** - Funding announcements, revenue estimates
- **TechCrunch** - Startup funding rounds and valuations
- **Wikipedia** - Aggregated citations from multiple reputable sources
- **Rothschild Growth Equity Reports** - Private market analysis

### See [sources_and_assumptions.md](sources_and_assumptions.md) for complete documentation of every data point.

---

## Limitations & Caveats

1. **Private Company Data**: 10 of 15 companies are private; revenue figures are estimates with ranges
2. **AI Revenue Apportionment**: For mixed-business companies (Microsoft, Oracle), AI revenue estimated from segments
3. **LTM Timing**: Some companies on different fiscal years; LTM to Sep 30, 2025 uses blended data
4. **Market Caps**: Nov 13, 2025 market close used for consistency; intraday fluctuations not reflected
5. **Multi-Year Contracts**: Recognition schedules not always public; commitments vs. revenue unclear
6. **No Pro-Rata Consolidation**: Full EV included for all companies; alternative pro-rata available in sensitivity

---

## How to Use This Analysis

### For Investors
1. Review [FINAL_RESULTS.md](FINAL_RESULTS.md) for high-level takeaways
2. Check [top_contributors.csv](top_contributors.csv) to see concentration risk
3. Read [sensitivity_analysis.md](sensitivity_analysis.md) for downside scenarios
4. Monitor Nvidia and Microsoft earnings (84% of consolidated EV)

### For Researchers
1. Start with [nodes.csv](nodes.csv) and [edges.csv](edges.csv) for raw data
2. Review [sources_and_assumptions.md](sources_and_assumptions.md) for methodology
3. Use [consolidated.json](consolidated.json) for programmatic access
4. Check confidence scores to assess data quality

### For Journalists/Analysts
1. Use [executive_summary.md](executive_summary.md) as starting point (300-400 words)
2. Cite specific figures from [consolidated_summary.csv](consolidated_summary.csv)
3. Reference [FINAL_RESULTS.md](FINAL_RESULTS.md) for top 10 sources
4. Note high-uncertainty items flagged in analysis

---

## Updates & Maintenance

This analysis is a point-in-time snapshot as of **November 13, 2025**. To update:

1. **Quarterly**: Refresh public company data from SEC filings
2. **As announced**: Update private company valuations when new funding rounds close
3. **Monthly**: Check for new material relationships (e.g., major cloud deals)
4. **Annual**: Re-run full consolidation for new fiscal year

---

## Contact & Attribution

This analysis was produced following a detailed plan that includes:
- Comprehensive network mapping
- Public filing research for 5 public companies
- Private market research for 10 private companies  
- Inter-company revenue removal
- Full sensitivity analysis
- Complete source documentation

All figures are documented with confidence scores and source URLs in [sources_and_assumptions.md](sources_and_assumptions.md).

---

## License

See [LICENSE](LICENSE) file in repository root.

