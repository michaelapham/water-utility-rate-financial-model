# Water Utility Rate Financial Model
Excel financial model simulating a water utility rate sufficiency analysis for a fictional small Texas munipality. Forecasting revenue and expenses, and rate adjustments across a 5-year planning horizon.

## Project Goal
Determine whether the City of Stringtown's current water rates generate sufficient revenue to cover all operating expenses, debt service obligations, and cash reserve contributions costs through Year 2030, and recommend a rate adjustment to achieve financial sufficiency and meet lender-required debt service coverage standards.

## Tools & Skills Demonstrated
- **Microsoft Excel** - cross-sheet referencing, named ranges, aggregations, IF, conditional formatting, dynamic charts, sheet protection
- **Financial modeling** - projected finances under new and existing rates from Years 2026-2030 with inflation escalation
- **Utility finance concepts** - rate structures, cost of service, debt service coverage ratio, revenue requirements, affordability analysis

## Utility Profile: City of Stringtown, TX (Fictional)
- **Service population:** 10,325 residents
- **Total accounts:** 3,070 (2,520 residential, 550 commercial)
- **Rate structures:** Two-class tiered block rate structure
- **Planning horizon:** 2026-2030

## Model Structure: 5 Sheets
- **Inputs:** All user-controlled assumptions and rate inputs. Only sheet requiring manual entry, all other sheets pull from here via cross-sheet references.
- **Revenue_Model:** Projects annual revenue across both customer classes (residential and commerical) using tiered block rate structure calculations with account growth applied year over year for both existing rates and new proposed rates starting in Year 2027.
- **Expense_Model:** Projects annual operating expenses, debt service, and cash reserve contributions with inflation escalation applied to operating line items.
- **Rate_Sufficiency_Analysis:** Core analysis sheet, compares projected revenue against total cost of service, calculates annual surplus/deficit, debt service coverage ratio, and proposed rates to achieve target DSCR of 1.15.
- **Dashboard:** Executive summary for non-technical stakeholders. Includes KPI cards, three dynamic charts, and plain English findings summary. Updates automatically when Inputs are changed.

## Key Findings
- **Current DSCR of 0.73** falls below the minimum 1.15 lender requirement: the utility is under-collecting relative to total cost of service
- **A ~8% system-wide rate adjustment** across both customer classes restores financial sufficiency and achieves the target 1.15 DSCR through the 5-year planning horizon
- **Residential average monthly bill increase from $32.75 to $35.75/month:** A $3.00/month increase represents approximately 1.1% of median household income in Stringtown, TX, which is well within the EPA's 2.5% affordability threshold
- **Commercial average monthly bill increase from $95.48 to $100.48/month:** A 5% increase in the average monthly bill for commercial customers
- **System-wide average monthly bill increase from $43.99 to $47.35/month:** $3.36/month average increase across all 3,070 accounts
- **Without a rate adjustment** the utility projects cumulative deficits growing through the Year 2030 as inflation escalates operating costs faster than flat-rate revenues

## How to Use the Model
1. Open `Water_Utility_Rate_Model_MichaelPham.xlsx`
2. Navigate to the **Inputs** sheet
3. Enter your utility's data in the light-grey-highlighted cells
4. Review findings on the **Rate_Sufficiency_Analysis** sheet
5. Present results using the **Dashboard** sheet

## Model Limitations and Notes
- Consumption figures grew at 1.0% year-over-year for simplicity for planning-level analysis
- Model is designed for small to mid-size water utilities (only 2 tiered rate structures), and not suitable for large metropolitan systems with more complex rate structures
- Does not account for uncollected bills/late fees, one-time fees, capital improvement plan costs, depreciation
- Expenses are rough estimates and may not be exhaustive of real-world considerations

## Data Sources & References
- **AWWA (American Water Works Association):** consumption benchmarks and rate study methodology guidance
- **EPA Water Finance Center:** affordability threshold (2.5% of median household income)
- **Environmental Finance Center, UNC:** rates analysis model structure used for reference
- All utility data is fictional and created for portfolio demonstration purposes

## Author
- Michael Pham
- github.com/michaelapham
- linkedin.com/in/michaelapham99
