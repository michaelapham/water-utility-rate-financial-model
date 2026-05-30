# Water Utility Rate Financial Model
Excel financial model simulating a water utility rate sufficiency analysis for a fictional small Texas munipality. Forecasting revenue and expenses, and rate adjustments across a 5-year planning horizon.

## Project Goal
Determine whether the City of Stringtown's current water rates generate sufficient revenue to cover all operating expenses, debt service obligations, and capital improvement plan costs through Year 2030, and recommend a rate adjustment to achieve financial sufficiency and meet lender-required debt service coverage standards.

## Tools & Skills Demonstrated
- **Microsoft Excel** - cross-sheet referencing, named ranges, aggregations, IF, conditional formatting, dynamic charts, sheet protection
- **Financial modeling** - projected finances under new and existing rates from Years 2026-2030 with inflation escalation
- **Utility finance concepts** - rate structures, cost of service, debt service coverage ratio, affordability analysis

## Utility Profile: City of Stringtown, TX (Fictional)
- **Service population:** 10,325 residents
- **Total accounts:** 3,070 (2,520 residential, 550 commercial)
- **Rate structures:** Two-class tiered block rate structure
- **Planning horizon:** 2026-2030

## Model Structure: 5 Sheets
- **Inputs:** All user-controlled assumptions and rate inputs. Only sheet requiring manual entry, all other sheets pull from here via cross-sheet references.
- **Revenue_Model:** Projects annual revenue across both customer classes (residential and commerical) using tiered block rate structure calculations with account growth applied year over year for both existing rates and new proposed rates starting in Year 2027.
- **Expense_Model:** Projects annual operating expenses, capital improvement plan costs, debt service, and cash reserve contributions with inflation escalation applied to operating line items.
- **Rate_Sufficiency_Analysis:** Core analysis sheet, compares projected revenue against total cost of service, calculates annual surplus/deficit, debt service coverage ratio, and proposed rates to achieve target DSCR of 1.15.
- **Dashboard:** Executive summary for non-technical stakeholders. Includes KPI cards, three dynamic charts, and plain English findings summary. Updates automatically when Inputs are changed.
