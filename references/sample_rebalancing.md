# Sample Quarterly Rebalancing Analysis

*This is an illustrative example of a full quarterly review output.*

---

## March 2026 — Q1 Rebalance

### Portfolio Snapshot Summary

| Account | Value | % of Total |
|---------|-------|------------|
| 401k — Fidelity | $180,000 | 52.2% |
| IRA — Vanguard | $125,000 | 36.2% |
| Taxable — Schwab | $40,000 | 11.6% |
| **Total** | **$345,000** | **100%** |

---

### Drift Analysis

*Strategy uses 25% relative drift trigger. Portfolio total: $305,000 (active accounts, excl. taxable).*

| Category | Target % | Target $ | Current $ | Current % | Drift % | Trigger? |
|----------|----------|----------|-----------|-----------|---------|----------|
| US Large Cap | 45% | $137,250 | $152,000 | 49.8% | +10.7% | No |
| US Small/Mid Cap | 20% | $61,000 | $48,500 | 15.9% | **-20.5%** | No (near) |
| International | 15% | $45,750 | $38,000 | 12.5% | **-16.9%** | No (near) |
| Bonds | 10% | $30,500 | $35,000 | 11.5% | +14.7% | No |
| Tech Sector (SOXX) | 5% | $15,250 | $22,000 | 7.2% | **+44.3%** | ✓ YES |
| Cash | 5% | $15,250 | $9,500 | 3.1% | -38.0% | ✓ YES |

**Positions triggering rebalance:** SOXX (overweight 44%), Cash (underweight 38%)

---

### Recommended Trades

**Self-Directed IRA — Execute in priority order:**

| Priority | Action | Ticker | Shares | Est. Amount | Reason |
|----------|--------|--------|--------|-------------|--------|
| 1 | SELL | SOXX | 14 | ~$6,750 | 44% over target; trim toward 5% |
| 2 | BUY | VWO | 75 | ~$3,200 | International underweight; add EM |
| 3 | BUY | IWM | 16 | ~$3,550 | Small cap underweight |

**Cash check:**
- Starting cash (IRA): $4,200
- SOXX proceeds: +$6,750
- VWO purchase: -$3,200
- IWM purchase: -$3,550
- **Ending cash: $4,200 → target range $4,500–$6,000** ✓ (within tolerance)

---

### Narrative

**SOXX trim:** Semiconductors had a strong quarter and are now 44% above target — well past the 25% trigger. Selling 14 shares brings the position from ~$22K to ~$15.2K, back in line with the 5% target. The semiconductor thesis is intact; this is mechanical trimming, not a view change.

**IWM add:** Small cap has drifted toward the lower boundary of the trigger. Adding here while we have proceeds from the SOXX trim is efficient. Not a forced trade — taking the opportunity while cash is available.

**VWO add:** International developed (VXUS in the 401k) is adequate, but emerging markets are underweight. VWO adds EM exposure efficiently in the IRA where it's accessible.

**No action on 401k:** The 401k's limited fund menu means we can't address the international underweight directly. It's being handled via IRA trades. The 401k allocation is within tolerance.

---

### Notes

- SOXX has now been trimmed two quarters in a row. If it continues to run, worth discussing whether 5% target should be revisited, or if we're fighting the tape on a strong thesis.
- User deferred decision to increase international allocation last quarter. Worth revisiting at Q2.
- Cash rebuild: ending cash is slightly below target after these trades. Next quarter's payroll contributions should restore this without additional action.

---

*Next quarterly review: June 2026*
