# nVent Electric Investment Research

An independent, ongoing research project on nVent Electric (`NYSE: NVT`) and the changing economics of electrical and thermal infrastructure for high-density data centers.

The project asks a simple question: **is the market still valuing nVent primarily as a traditional electrical-products company while its earnings mix is shifting toward higher-growth data-center infrastructure?**

This is a living research repository rather than a one-time stock pitch. The model is designed to be updated as new earnings releases, backlog disclosures, capacity additions, and data-center product metrics become available.

## Research focus

The working thesis is built around three testable ideas:

1. **Data-center content per megawatt is increasing.** Higher rack density requires more liquid cooling, power distribution, connection, enclosure, and protection content.
2. **nVent participates in both white space and gray space.** Its opportunity extends beyond rack-level cooling to broader electrical infrastructure around the data hall.
3. **Backlog and capacity additions may translate into earnings above current expectations.** The model tests whether revenue growth can persist long enough—and at sufficient margins—to justify the current valuation.

The model does not assume that nVent is undervalued. Valuation is treated as an output of operating assumptions, not as a starting premise.

## Modeling approach

The core workbook uses nVent's disclosed operating segments:

- **Systems Protection:** enclosures, electrical protection, power distribution, and liquid-cooling-related infrastructure.
- **Electrical Connections:** fastening, grounding, connection, and related electrical products.

Data-center exposure is used as a driver of Systems Protection growth and margins rather than modeled as a separate segment. nVent does not currently disclose enough standalone data-center profit, asset, and cash-flow information to support a reliable separate valuation.

The workbook includes:

- historical annual and quarterly financials;
- Bear, Base, and Bull operating scenarios;
- segment revenue and margin forecasts through 2031;
- adjusted EPS and unlevered free-cash-flow builds;
- a mid-year-convention DCF;
- forward-P/E trading comparables;
- a segment-based sum-of-the-parts valuation;
- formula and consistency checks; and
- a source library and model-building guide.

## Current model read

As of July 22, 2026, the Base case produces approximately:

| Metric | Base case |
|---|---:|
| 2026E revenue | $5.0bn |
| 2026E adjusted EPS | $4.55 |
| DCF value per share | $129.6 |
| Trading-comps value per share | $169.0 |
| SOTP value per share | $166.8 |
| Blended value per share | $148.9 |

Against a $159 reference share price, the blended Base case implies modest downside. The present model therefore supports the view that nVent's business quality is improving, but it does **not yet establish a sufficient margin of safety**. The most important open questions are the duration of Systems Protection growth, the path to a roughly 24% segment margin, and whether backlog converts into 2027–2028 earnings revisions.

## Repository structure

```text
.
├── README.md
├── guide/
│   └── 建模实操说明.md
├── model/
│   └── nVent_Core_Valuation_Model.xlsx
└── sources/
    ├── README.md
    ├── ir/
    └── sec/
```

The downloaded source documents are retained locally for auditability but excluded from Git by default. `sources/README.md` links to the primary public filings and investor materials used in the model.

## How to use the model

1. Open `model/nVent_Core_Valuation_Model.xlsx` and start with `Cover` and `Checks`.
2. Select Bear, Base, or Bull in `Assumptions!B3`.
3. Calibrate 2026 revenue and EPS to company guidance before extending the forecast.
4. Build 2027–2031 from segment growth and margins rather than plugging EPS.
5. Review UFCF conversion, DCF sensitivity, comparable-company inputs, and SOTP assumptions.
6. Confirm that the final check status is `OK` before relying on valuation outputs.

## Research discipline

- Primary filings and company materials are preferred over secondary summaries.
- Historical data, operating assumptions, linked formulas, and outputs use distinct formatting in the workbook.
- Data-center revenue is not added separately to segment revenue, avoiding double counting.
- Market-data inputs are date-stamped and should be refreshed before publication.
- Bear-case work is used to test the thesis, not merely to create a lower target price.

## Disclaimer

This repository is for independent research and educational purposes only. It is not investment advice, a recommendation to buy or sell securities, or a substitute for independent due diligence. Estimates may be incomplete or incorrect, and market inputs can become stale quickly.
