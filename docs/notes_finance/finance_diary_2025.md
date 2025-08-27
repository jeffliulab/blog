# Finance Learning Notes


#### The Federal Reserve, Short-Term Treasury Yields, and Long-Term Treasury Yields

August 27, 2025

First, let's learn about the Federal Reserve's conventional tools:

1. Federal Funds Rate: Rate hikes/cuts
2. Open Market Operations (OMO): Buying/selling Treasury securities
3. Balance Sheet Policy: QE (Quantitative Easing) / QT (Quantitative Tightening)
4. Forward Guidance
5. Emergency Lending Facilities: Discount Window, PMCCF/SMCCF
6. Swap Lines: U.S. dollar liquidity swap lines
7. Special Guarantee and Credit Tools: TALF, targeted support for ABS/student loans, etc.

Direct short-end impact: When the Fed announces a rate hike/cut or conducts OMO, short-term Treasury yields (especially those within 1 year) are directly affected, because the federal funds rate is the interbank overnight rate and almost directly anchors short-term Treasury yields.

| Tool               | Direction       | Impact (Short-Term Treasuries)                  |
| ------------------ | --------------- | ----------------------------------------------- |
| Federal Funds Rate | Rate Hike       | Short-end rates rise, yield curve flattens      |
| Federal Funds Rate | Rate Cut        | Short-end rates fall, yield curve steepens      |
| OMO                | Buy Treasuries  | Increases demand, bond prices rise, yields fall |
| OMO                | Sell Treasuries | Increases supply, bond prices fall, yields fall |

Direct long-end impact: When the Fed uses QE/QT or forward guidance, it affects long-term Treasury (10-30 year) yields.

| Tool             | Direction                     | Impact (Long-Term Treasuries)                         |
| ---------------- | ----------------------------- | ----------------------------------------------------- |
| Balance Sheet    | QE                            | Treasury demand increases, prices rise, yields fall   |
| Balance Sheet    | QT                            | Treasury supply increases, prices fall, yields rise   |
| Forward Guidance | Maintain low rates long-term  | Future expectations are lowered, long-end yields fall |
| Forward Guidance | Maintain high rates long-term | Future expectations are raised, long-end yields rise  |

There are also some special tools for extraordinary times:

| Tool               | Direction                   | Impact                                                                                                                                         |
| ------------------ | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Emergency Lending  | Discount Window             | Provides liquidity to banks, eases short-term funding pressure, short-end rates fall                                                           |
| Emergency Lending  | Corporate credit facilities | Stabilizes credit markets, lowers corporate financing costs, demand for Treasuries may fall, long-term rates may rise but not definitively     |
| Swap Lines         | U.S. dollar swap lines      | Ensures global USD liquidity, suppresses short-term USD funding costs, short-term Treasury yields fall                                         |
| Special Guarantees | TALF/Targeted Support       | Stabilizes specific markets, eases panic, investor demand for safe-haven bonds weakens, long-term Treasury rates may rise but not definitively |

Therefore, the Fed's interest rate adjustments do not directly affect long-end Treasury rates; the overall macroeconomic situation must be considered. In other words, after a Fed rate cut, although short-term rates fall, long-term rates depend on many other factors.

```
20-Year Yield ≈ (Average of future short-term rates)
+ (Future inflation compensation)
+ (Term premium)
+ (Supply/demand pressure / funding preference)
```

For example, let's look at the current data from the United States:

* **Current 20-Year Rate Status**
  * Nominal Rate ≈ **4.86%** (8/25)
  * TIPS Real Rate ≈ **2.35%**
  * Implied Inflation Compensation ≈ **2.5%**
  * Consistent with 5y5y forward inflation expectation (≈2.34%)
* **Average of Future Short-Term Rates (Policy Path)**
  * FOMC Dot Plot: 2025 at 3.9%, 2026 at 3.6%, long-run around 3%
  * Market pricing a drop to 3.2–3.4% in the next 12 months
  * The average of short-end rates is moving down moderately, putting some downward pressure on the long end but not indicating extreme easing.
* **Future Inflation Compensation**
  * PCE YoY at 2.6%, Cleveland Fed nowcast around 2.7–2.9%
  * Long-term market expectations are anchored in the 2.3–2.6% range
  * Consumer surveys have recently risen to ~3%
  * Inflation compensation remains stubbornly high, which is unfavorable for the long end.
* **Term Premium**
  * ACM model shows the 10-year term premium is about 0.5–0.8%
  * MOVE index, a measure of interest rate volatility, is around 79, which is not low
  * QT is still in progress
  * The term premium is positive and on the high side, pushing up long-end rates.
* **Supply/Demand / Funding Preference**
  * QRA: 10yr at $42bn, 20yr at $13–16bn, 30yr at $22–25bn. Supply is high but stable.
  * The Treasury Department is increasing the frequency of buybacks to ease liquidity pressure.
  * Foreign net inflows were $77.8bn in June, with foreign holdings of Treasuries reaching a record $9.13T.
  * Against the backdrop of QT and the deficit, the supply side continues to exert upward pressure on the long end.
* **Formula Synthesis**
  * 20-Year Rate ≈ Average of short-end rates (moderately moving down) + Inflation compensation (stubbornly at 2.5%) + Term premium (positive and rising) + Supply pressure (high but stable)
  * This yields the current interest rate level of about 4.8–4.9%.
* **Implications for TLT**
  * A simple rate cut is not enough to push TLT higher.
  * If inflation compensation doesn't come down + term premium remains high + supply pressure is significant → long-end rates will stay elevated, putting pressure on TLT.
  * A favorable combination for TLT: A fall in inflation expectations, a contraction in the term premium (QT slows down / risk premium decreases), and an easing of supply pressure.
  * An unfavorable combination for TLT: Sticky inflation, continued QT, and upward pressure on supply and risk premiums from a high deficit.

From this, a preliminary conclusion can be drawn: the current **trend for TLT is weak**. Although the Fed is cutting rates, **stubborn inflation compensation, a high term premium, and significant fiscal supply pressure** are keeping long-end rates elevated, leaving TLT without sustained upward momentum.

Based on the content above, I have organized a preliminary version of a long-term Treasury yield dashboard to incorporate into my AI Financial Agent for learning and investment guidance.

#### Duration of U.S. Treasury Bonds

August 4, 2025

U.S. Treasury bonds are highly resilient financial products. While it's not accurate to say they are risk-free, among the many risky investment options, they still stand out as the most risk-resistant.

Duration is a measure of how sensitive a bond’s price is to changes in interest rates.

> Rule of thumb: For every 1% change in interest rates, a bond's price changes by approximately “Duration * 1%”

On a related note, I’ve been thinking of buying some Treasury bonds recently. When selecting U.S. Treasury bonds, I considered four products:

* 10-Year U.S. Treasury Bond
* 30-Year U.S. Treasury Bond
* IEF
* TLT

Comparison of data for the four products:

| Instrument   | Price  | Yield | Estimated Reaction to Fed Rate Change (4.35→3.50) |
| ------------ | ------ | ----- | -------------------------------------------------- |
| TLT          | 95–96 | 4.86% | +10%                                               |
| IEF          | 95–96 | 4.16% | +5%                                                |
| 10-Year Bond | 1000   | 4.38% | +6.5%                                              |
| 30-Year Bond | 1000   | 4.8%  | +15%                                               |

If my goal is to hold for 5 years, betting on the Fed returning to a low-interest-rate era while earning stable dividend income, then:

* **IEF**: Stable dividends, low volatility, duration matches 5-year horizon fairly well
* **10-Year Bond**: Pays interest semiannually, offers stable liquidity, moderate price volatility

If my goal is to invest steadily so that I no longer need to earn income through labor after 20 years, then starting from 2025 (T=0), I invest an additional **T x $10,000** each year into a Treasury bond portfolio. Assuming an average annual return of 4%, the projection is:

| T  | Annual Investment | Portfolio Value | Annual Yield |
| -- | ----------------- | --------------- | ------------ |
| 0  | 1                 | 1               | 0.04         |
| 1  | 1                 | 2               | 0.08         |
| 2  | 2                 | 4               | 0.16         |
| 3  | 3                 | 7               | 0.28         |
| .. | ..                | ..              | ..           |
| 20 | 20                | 210             | 8.4          |

By year 20, I could be earning $80,000 in passive income annually. From this perspective, the yield isn’t particularly high, but it’s not low either. Considering the goal is stable passive income, and assuming a $2 million principal, this goal doesn’t seem out of reach. The key is whether I can maintain a continuous increase in income and achieve the plan of earning T in year T. This is actually harder than achieving a 4% return, but I’m optimistic about my income prospects and believe that my future self will find ways to earn even more.
