# 401(k) Substantive Testing

## Overview

Substantive testing is a critical component of the 401(k) plan audit that involves detailed examination of transactions and account balances to detect material misstatements. Unlike internal control testing, which evaluates processes, substantive testing directly tests the dollar amounts in the financial statements. This comprehensive guide covers all aspects of substantive testing for 401(k) plan audits.

## Table of Contents

1. [Substantive Testing Fundamentals](#substantive-testing-fundamentals)
2. [Contributions Testing](#contributions-testing)
3. [Distributions Testing](#distributions-testing)
4. [Participant Account Balance Testing](#participant-account-balance-testing)
5. [Investment Testing](#investment-testing)
6. [Loan Testing](#loan-testing)
7. [Forfeiture Testing](#forfeiture-testing)
8. [Administrative Expense Testing](#administrative-expense-testing)
9. [Analytical Procedures](#analytical-procedures)
10. [Documentation and Conclusions](#documentation-and-conclusions)

---

## Substantive Testing Fundamentals

### Purpose of Substantive Testing

Substantive testing provides evidence that:
- Financial statement amounts are accurate
- Transactions are properly authorized
- Amounts are properly classified
- Disclosures are complete and accurate

### Relationship to Internal Controls

| Approach | Internal Control Reliance | Substantive Testing |
|----------|---------------------------|---------------------|
| Strong controls | High reliance | Reduced testing |
| Weak controls | Low reliance | Increased testing |
| No controls tested | No reliance | Maximum testing |

### Assertions Tested

| Assertion | Description | Testing Focus |
|-----------|-------------|---------------|
| Existence | Assets/liabilities exist | Confirm investments, participant accounts |
| Completeness | All transactions recorded | Test cutoff, search for unrecorded items |
| Rights/Obligations | Plan owns assets | Verify ownership, trust agreements |
| Valuation | Amounts properly valued | Test fair values, allocation accuracy |
| Presentation | Proper classification | Review financial statement format |

### Sample Selection Methods

| Method | When Used |
|--------|-----------|
| Random | General testing |
| Systematic | Large populations |
| Haphazard | Specific characteristics |
| Stratified | Mixed population values |
| Monetary unit | High-value focus |

### Sample Size Factors

| Factor | Effect on Sample Size |
|--------|----------------------|
| Control reliance | More reliance = smaller samples |
| Tolerable misstatement | Higher tolerance = smaller samples |
| Population size | Larger population = larger samples |
| Risk assessment | Higher risk = larger samples |
| Expected errors | More expected = larger samples |

---

## Contributions Testing

### Employee Deferral Testing

#### Objectives
- Verify deferrals calculated per elections
- Confirm timely deposit to trust
- Verify proper allocation to accounts
- Test compliance with 402(g) limits

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of pay periods/participants | Sample selection memo |
| 2 | Obtain deferral election forms | Election forms |
| 3 | Obtain payroll registers | Payroll records |
| 4 | Recalculate expected deferral | Calculation workpaper |
| 5 | Compare to actual withholding | Variance analysis |
| 6 | Trace to trust deposit | Bank statements |
| 7 | Calculate deposit timeliness | Days calculation |
| 8 | Trace to participant account | Account statements |
| 9 | Verify proper source coding | Recordkeeper reports |
| 10 | Test 402(g) limit compliance | Limit analysis |

#### Sample Workpaper

```
SUBSTANTIVE TEST: Employee Deferrals
Plan Year: 2024
Sample Size: 40 participants × 4 pay periods = 160 items

Participant: Sarah Thompson
Employee ID: 45678
Election: 8% pre-tax

Pay Date: June 15, 2024
Gross Pay: $6,250.00 (bi-weekly)
Expected Deferral: $6,250.00 × 8% = $500.00
Actual Deferral: $500.00 ✓

Deposit Date: June 18, 2024
Days to Deposit: 2 business days ✓ (timely)

Account Posting: $500.00 ✓
Source: Pre-tax deferral ✓

Exception: None
```

### Employer Contribution Testing

#### Match Contribution Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain plan document match formula | Plan excerpt |
| 2 | Select sample of participants | Selection memo |
| 3 | Obtain participant compensation | Payroll/census |
| 4 | Obtain participant deferrals | Contribution reports |
| 5 | Calculate expected match | Match calculation |
| 6 | Compare to actual match | Variance analysis |
| 7 | Verify eligibility for match | Service/hours records |
| 8 | Trace to trust deposit | Bank records |
| 9 | Verify account allocation | Participant statements |

#### Match Calculation Example

```
Plan Match Formula: 100% on first 3%, 50% on next 2%

Participant: Michael Roberts
Compensation: $85,000
Deferral: $6,800 (8%)

Expected Match:
- First 3%: $85,000 × 3% × 100% = $2,550
- Next 2%: $85,000 × 2% × 50% = $850
- Total Expected: $3,400

Actual Match Allocated: $3,400 ✓

Variance: $0.00
Exception: None
```

#### Profit Sharing Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain allocation formula | Plan document |
| 2 | Verify total contribution amount | Board resolution |
| 3 | Obtain eligible participant list | Census data |
| 4 | Calculate total eligible compensation | Compensation summary |
| 5 | Allocate to sample participants | Allocation workpaper |
| 6 | Compare to actual allocations | Variance analysis |
| 7 | Test eligibility requirements | Service records |
| 8 | Verify 415 limit compliance | Limit testing |

---

## Distributions Testing

### Objectives

- Verify distribution triggered by eligible event
- Confirm proper authorization
- Verify vesting correctly applied
- Test calculation accuracy
- Confirm proper tax withholding/reporting

### Distribution Testing Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of distributions | Sample selection |
| 2 | Obtain distribution request/election | Distribution forms |
| 3 | Verify triggering event | HR/termination records |
| 4 | Verify authorization | Approval documentation |
| 5 | Calculate vested balance | Vesting calculation |
| 6 | Recalculate distribution amount | Calculation workpaper |
| 7 | Compare to actual payment | Payment records |
| 8 | Verify withholding | Withholding calculation |
| 9 | Trace to 1099-R | Tax forms |
| 10 | Trace to payment record | Check/wire/rollover |

### Distribution Testing Workpaper

```
SUBSTANTIVE TEST: Distributions
Sample Size: 35 distributions

Participant: James Anderson
Distribution Type: Termination - Full Distribution
Termination Date: August 31, 2024

Account Balance at Distribution:
- Employee pre-tax: $48,500 (100% vested)
- Employee Roth: $12,000 (100% vested)
- Employer match: $18,000 (subject to vesting)
- Profit sharing: $9,500 (subject to vesting)
- Total Account: $88,000

Vesting Calculation:
- Years of service: 4 years
- Vesting schedule: 6-year graded
- Vesting percentage: 60%

Vested Amounts:
- Employee pre-tax: $48,500 × 100% = $48,500
- Employee Roth: $12,000 × 100% = $12,000
- Employer match: $18,000 × 60% = $10,800
- Profit sharing: $9,500 × 60% = $5,700
- Total Vested: $77,000

Distribution:
- Direct rollover to IRA: $77,000
- Withholding: $0 (direct rollover)

Forfeiture: $88,000 - $77,000 = $11,000

1099-R Verification:
- Box 1 (Gross): $77,000 ✓
- Box 2a (Taxable): $65,000 ✓ (pre-tax + match + PS)
- Code: G (direct rollover) ✓

Exception: None
```

### Types of Distributions

| Distribution Type | Special Testing |
|-------------------|-----------------|
| Termination | Verify termination date and vesting |
| Retirement | Verify age and plan provisions |
| Death | Verify beneficiary designation |
| Disability | Verify disability determination |
| Hardship | Verify qualifying reason and documentation |
| In-service | Verify eligibility per plan terms |
| QDRO | Verify court order and alternate payee |
| RMD | Verify age and calculation |

### Hardship Withdrawal Testing

Additional procedures:

| Step | Procedure |
|------|-----------|
| 1 | Verify reason qualifies as safe harbor hardship |
| 2 | Review supporting documentation |
| 3 | Verify amount does not exceed need |
| 4 | Verify sources used (employee deferrals first) |
| 5 | Verify suspension of deferrals (if required) |
| 6 | Verify no rollover option offered |

---

## Participant Account Balance Testing

### Objectives

- Verify individual account balances are accurate
- Confirm all activity properly recorded
- Verify proper allocation of earnings
- Test money source balances

### Account Roll-Forward Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of participants | Sample selection |
| 2 | Obtain beginning balance | Prior year statement |
| 3 | Add contributions | Contribution records |
| 4 | Add earnings/gains | Earnings allocation |
| 5 | Subtract distributions | Distribution records |
| 6 | Subtract fees | Fee records |
| 7 | Account for transfers | Transfer records |
| 8 | Compare to ending balance | Year-end statement |
| 9 | Verify by money source | Source breakdown |

### Account Roll-Forward Workpaper

```
SUBSTANTIVE TEST: Participant Account Roll-Forward
Participant: Linda Martinez
Account ID: 78901

Beginning Balance (1/1/24):          $175,000.00

Activity:
+ Employee pre-tax deferrals          $19,200.00
+ Employee Roth deferrals              $4,800.00
+ Employer match                       $7,200.00
+ Investment earnings                 $22,750.00
- Distributions                             $0.00
- Participant fees                       -$180.00
+ Loan repayment (principal)           $6,000.00
- Loan interest (to account)               $0.00
                                      -----------
Calculated Ending Balance:           $234,770.00

Per Year-End Statement:              $234,770.00 ✓

Variance: $0.00
Exception: None
```

### Participant Data Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of participants | Sample selection |
| 2 | Compare date of birth | HR records |
| 3 | Compare date of hire | HR records |
| 4 | Compare compensation | Payroll/W-2 |
| 5 | Verify service calculation | Service records |
| 6 | Verify employment status | HR records |
| 7 | Verify address | Address records |
| 8 | Verify beneficiary on file | Beneficiary forms |

---

## Investment Testing

### Full Scope Investment Testing

#### Existence Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain year-end custodian statements | Custodian records |
| 2 | Send positive confirmation to custodian | Confirmation letter |
| 3 | Reconcile confirmation response | Reconciliation |
| 4 | Investigate any differences | Analysis |
| 5 | Verify security descriptions | Security detail |

#### Valuation Testing

| Investment Type | Valuation Procedure |
|-----------------|---------------------|
| Mutual funds | Compare NAV to independent source |
| Collective trusts | Evaluate pricing methodology |
| Common stock | Verify quoted market price |
| Stable value | Evaluate contract value and wrap contracts |
| Company stock | Verify quoted price or valuation |
| Real estate | Evaluate appraisal |

#### Valuation Testing Workpaper

```
SUBSTANTIVE TEST: Investment Valuation
Investment Type: Mutual Funds
Sample Size: 10 funds

Fund: ABC Growth Fund (ABCGX)
Shares held: 125,000
Year-end NAV per share: $45.67

Per Plan Records:
Shares: 125,000
Value: $5,708,750 ($45.67 × 125,000)

Independent Verification:
Source: Morningstar
NAV 12/31/24: $45.67 ✓

Variance: $0.00
Exception: None
```

### Limited Scope Investment Testing

#### Certification Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Identify certifying institution | Plan records |
| 2 | Obtain certification letter | Certification |
| 3 | Verify certification requirements met | Checklist |
| 4 | Verify amounts agree to statements | Reconciliation |
| 5 | Identify non-certified investments | Analysis |
| 6 | Test non-certified investments fully | Testing workpapers |

#### Certification Checklist

```
☐ Certification in writing
☐ Signed by authorized official
☐ Dated appropriately (as of year-end)
☐ Certifies accuracy of information
☐ Certifies completeness of information
☐ States information prepared per GAAP

Certified Information:
☐ Beginning value
☐ Ending value
☐ Purchases
☐ Sales proceeds
☐ Investment income
☐ Realized gains/losses
☐ Unrealized appreciation/depreciation
```

### Investment Transaction Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of purchases | Transaction report |
| 2 | Verify authorization | Approval records |
| 3 | Verify trade date | Trade confirmation |
| 4 | Verify settlement | Settlement records |
| 5 | Verify pricing | Independent source |
| 6 | Select sample of sales | Transaction report |
| 7 | Verify proceeds calculation | Sale confirmation |
| 8 | Calculate gain/loss | Calculation workpaper |
| 9 | Trace to investment income | Income reports |

---

## Loan Testing

### Objectives

- Verify loans comply with IRC 72(p)
- Confirm compliance with plan terms
- Verify proper documentation
- Test for deemed distributions

### Loan Testing Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain loan register | Loan report |
| 2 | Select sample of loans | Sample selection |
| 3 | Obtain loan documentation | Loan agreement |
| 4 | Verify 50% vested balance limit | Balance verification |
| 5 | Verify $50,000 maximum | Amount verification |
| 6 | Verify repayment term | Loan terms |
| 7 | Verify level amortization | Amortization schedule |
| 8 | Verify reasonable interest rate | Rate documentation |
| 9 | Trace repayments | Repayment records |
| 10 | Test for defaults | Default analysis |

### Loan Compliance Testing

```
SUBSTANTIVE TEST: Participant Loans
Participant: David Chen
Loan ID: L-2024-0456
Loan Date: May 15, 2024
Original Amount: $35,000

Maximum Amount Tests:
- Vested balance at loan: $95,000
- 50% of vested: $47,500
- $50,000 statutory maximum
- Maximum allowed: $47,500
- Loan amount: $35,000 ✓ (below maximum)

Highest Outstanding Balance (12 months):
- 12-month lookback: $20,000 prior loan
- Remaining of $50,000 limit: $50,000 - $20,000 = $30,000
- Issue: $35,000 exceeds $30,000 ✗

Repayment Terms:
- Loan purpose: General purpose
- Maximum term: 5 years (60 months)
- Actual term: 48 months ✓

Amortization:
- Monthly payment: $811.49
- Interest rate: 7.5%
- Level amortization: Yes ✓

Exception Identified: Loan exceeded $50,000 reduced limit

Resolution Required:
- Excess amount ($5,000) may be treated as deemed distribution
- Plan sponsor should consult EPCRS for correction options
- Document correction in audit workpapers
- Monitor for similar issues in loan processing controls
```

### Deemed Distribution Testing

For loans in default:

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Identify defaulted loans | Default report |
| 2 | Determine default date | Payment history |
| 3 | Calculate deemed distribution amount | Calculation |
| 4 | Verify proper 1099-R reporting | Tax forms |
| 5 | Verify continued repayment (if applicable) | Payment records |

---

## Forfeiture Testing

### Objectives

- Verify forfeitures properly calculated
- Confirm timing of forfeiture
- Verify appropriate use of forfeitures
- Test allocation accuracy

### Forfeiture Testing Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain forfeiture activity report | Forfeiture report |
| 2 | Select sample of forfeitures | Sample selection |
| 3 | Verify termination date | HR records |
| 4 | Verify vesting at termination | Vesting calculation |
| 5 | Calculate expected forfeiture | Calculation |
| 6 | Compare to actual forfeiture | Forfeiture record |
| 7 | Verify timing per plan | Plan terms |
| 8 | Trace forfeiture use | Allocation records |
| 9 | Verify use per plan document | Plan document |

### Forfeiture Testing Workpaper

```
SUBSTANTIVE TEST: Forfeitures
Participant: Amanda Wilson
Termination Date: October 15, 2024

Account at Termination:
- Employee deferrals: $28,000 (100% vested)
- Employer match: $14,000 (subject to vesting)
- Profit sharing: $7,000 (subject to vesting)

Years of Service: 2.3 years
Vesting Schedule: 3-year cliff

Vesting Analysis:
- Employee deferrals: 100% = $28,000 vested
- Employer match: 0% (under 3 years) = $0 vested
- Profit sharing: 0% (under 3 years) = $0 vested

Calculated Forfeiture:
- Match forfeiture: $14,000
- PS forfeiture: $7,000
- Total: $21,000

Per Forfeiture Report: $21,000 ✓

Use of Forfeitures:
Per Plan Document: Applied to reduce employer contributions ✓
Forfeiture Account Balance at Year-End: $45,000
Prior Year Balance: $30,000
Current Year Forfeitures: $75,000
Forfeitures Used: $60,000
Ending Balance: $45,000 ✓

Exception: None
```

---

## Administrative Expense Testing

### Objectives

- Verify expenses are reasonable
- Confirm proper authorization
- Verify allocation method
- Test payment accuracy

### Expense Testing Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain expense listing | Expense report |
| 2 | Compare to prior year | Trend analysis |
| 3 | Compare to budget/contracts | Budget/contracts |
| 4 | Select sample for detailed testing | Sample selection |
| 5 | Verify authorization | Approval records |
| 6 | Verify service received | Service agreements |
| 7 | Verify amount per contract/invoice | Invoices |
| 8 | Trace payment | Payment records |
| 9 | Test allocation methodology | Allocation records |

### Expense Testing Workpaper

```
SUBSTANTIVE TEST: Administrative Expenses
Sample Size: 20 expense items

Expense: Recordkeeping Services
Vendor: ABC Recordkeeping, Inc.
Invoice: INV-2024-0789
Amount: $125,000

Per Service Agreement:
- Annual fee: $25 per participant
- Participants: 5,000
- Expected: $125,000

Per Invoice: $125,000 ✓
Variance: $0.00

Authorization: Committee minutes dated 1/15/24 ✓
Payment: Wire transfer 12/15/24 ✓
Payment per bank statement: $125,000 ✓

Paid From: Plan assets ✓
Allocation: Pro-rata to participant accounts ✓

Exception: None
```

---

## Analytical Procedures

### Purpose

Analytical procedures help identify:
- Unusual fluctuations
- Potential misstatements
- Areas requiring additional testing
- Reasonableness of recorded amounts

### Year-over-Year Analysis

| Account | Analysis |
|---------|----------|
| Net assets | Compare to prior year, explain change |
| Contributions | Compare to prior year and payroll |
| Distributions | Compare to prior year and participant counts |
| Investment income | Compare to investment returns |
| Expenses | Compare to prior year and contracts |

### Ratio Analysis

| Ratio | Purpose |
|-------|---------|
| Contribution per participant | Identify unusual patterns |
| Distribution per terminated participant | Reasonableness check |
| Expense per participant | Benchmark comparison |
| Investment return | Compare to market indices |

### Analytical Procedures Workpaper

```
SUBSTANTIVE ANALYTICAL PROCEDURES
Plan Year 2024

Net Assets:
- Beginning: $45,000,000
- Ending: $52,500,000
- Change: $7,500,000 (16.7%)

Expected Change:
+ Contributions: $4,200,000
+ Investment earnings: $5,400,000 (12% return)
- Distributions: $2,100,000
- Expenses: $150,000
= Expected change: $7,350,000 (16.3%)

Variance: $150,000 (0.4%)
Conclusion: Reasonable, no further testing

Contribution Analysis:
- Employee deferrals: $3,200,000
- Prior year: $3,000,000
- Change: $200,000 (6.7%)
- Participant change: 5%
- Conclusion: Increase reasonable given participant growth

Distribution Analysis:
- Total distributions: $2,100,000
- Terminated participants: 42
- Average: $50,000
- Prior year average: $48,000
- Conclusion: Reasonable
```

---

## Documentation and Conclusions

### Workpaper Documentation Requirements

| Element | Requirement |
|---------|-------------|
| Objectives | What is being tested |
| Procedures | Steps performed |
| Sample selection | How selected, size |
| Testing results | Detailed results |
| Exceptions | Findings identified |
| Conclusions | Testing conclusion |

### Exception Evaluation

When exceptions are found:

| Step | Action |
|------|--------|
| 1 | Quantify the error |
| 2 | Determine cause |
| 3 | Evaluate if isolated or systemic |
| 4 | Extend testing if systemic |
| 5 | Project to population |
| 6 | Evaluate effect on opinion |

### Conclusion Summary

```
SUBSTANTIVE TESTING CONCLUSION SUMMARY

Area: Contributions
Procedures: Tested 160 contribution items
Exceptions: None
Conclusion: Satisfactory

Area: Distributions
Procedures: Tested 35 distributions
Exceptions: 1 vesting calculation error ($500)
Projected error: Not significant
Conclusion: Satisfactory

Area: Investments
Procedures: Limited scope - certification obtained
Non-certified items: Self-directed brokerage ($2.1M)
Testing: Fully tested, no exceptions
Conclusion: Satisfactory

Area: Loans
Procedures: Tested 25 loans
Exceptions: 1 potential excess loan
Disposition: Under review by plan sponsor
Conclusion: Pending resolution

Overall Conclusion: Substantive testing complete.
One unresolved item (loan). Financial statements 
appear fairly stated in all material respects.
```

### Effect on Audit Opinion

| Finding | Potential Effect |
|---------|------------------|
| No exceptions | Support unqualified opinion |
| Minor exceptions | Document, may not affect opinion |
| Significant exceptions | May require adjustment |
| Material misstatement | May affect opinion |
| Scope limitations | May affect opinion |

---

## Related Resources

- [Audit Testing Procedures](401k-audit-testing.md)
- [Internal Controls Testing](401k-internal-controls.md)
- [Audit Process](401k-audit-process.md)
- [Audit Findings](401k-audit-findings.md)
- [Limited Scope Audit](401k-limited-scope-audit.md)

---

*Last Updated: 2024*
