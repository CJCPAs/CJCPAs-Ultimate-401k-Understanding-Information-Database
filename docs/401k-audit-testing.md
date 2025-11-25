# 401(k) Audit Testing Procedures

## Overview

This document provides detailed, step-by-step audit testing procedures for each area of a 401(k) plan audit. These procedures serve as a comprehensive guide for auditors and help plan sponsors understand what to expect during the audit process.

## Table of Contents

1. [Contributions Testing](#contributions-testing)
2. [Benefit Payments Testing](#benefit-payments-testing)
3. [Participant Account Testing](#participant-account-testing)
4. [Investment Testing](#investment-testing)
5. [Loan Testing](#loan-testing)
6. [Forfeitures Testing](#forfeitures-testing)
7. [Administrative Expenses Testing](#administrative-expenses-testing)
8. [Compliance Testing Procedures](#compliance-testing-procedures)
9. [Related Party Transaction Testing](#related-party-transaction-testing)
10. [Rollover Testing](#rollover-testing)

---

## Contributions Testing

### Employee Deferrals (Pre-Tax and Roth)

#### Objectives
- Verify deferrals are properly calculated based on elections
- Confirm timely deposit to trust
- Ensure proper allocation to participant accounts
- Verify compliance with 402(g) limits

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain deferral election forms for sample | Election forms |
| 2 | Verify election on file matches what was withheld | Payroll records |
| 3 | Calculate expected deferral based on compensation | Compensation records |
| 4 | Compare calculated amount to actual deduction | Pay stubs |
| 5 | Trace deferral to bank deposit | Bank statements |
| 6 | Calculate business days to deposit | Payroll and deposit dates |
| 7 | Trace deposit to participant account | Participant statements |
| 8 | Verify proper money source coding | Recordkeeper reports |
| 9 | Test deferral changes during year | Changed elections |
| 10 | Verify 402(g) limit monitoring | Limit reports |

#### Sample Deferral Test Workpaper

```
Participant: John Smith
Employee ID: 12345
Pay Date: March 15, 2024
Gross Pay: $4,166.67
Deferral Election: 8%

Expected Deferral: $4,166.67 × 8% = $333.33
Actual Deferral: $333.33 ✓

Deposit Date: March 18, 2024
Business Days: 1 ✓ (timely)

Account Posting: $333.33 ✓
Money Source: Pre-tax deferral ✓
```

### Employer Matching Contributions

#### Objectives
- Verify match calculated per plan formula
- Confirm eligibility for match
- Verify proper allocation
- Ensure vesting properly applied

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain plan document match formula | Plan document |
| 2 | Identify participants receiving match | Contribution report |
| 3 | Select sample for testing | Selection documentation |
| 4 | Calculate expected match per formula | Calculations |
| 5 | Compare to actual match allocated | Participant accounts |
| 6 | Verify compensation used is correct | Payroll records |
| 7 | Verify eligibility to receive match | Eligibility records |
| 8 | Verify hours/service requirements met | Service records |
| 9 | Trace match to trust deposit | Bank statements |
| 10 | Verify vesting percentage applied | Vesting report |

#### Sample Match Calculation

```
Plan Formula: 100% on first 3%, 50% on next 2%
Participant: Jane Doe
Annual Compensation: $75,000
Employee Deferral: $5,250 (7% of $75,000)

Match Calculation:
- First 3%: $75,000 × 3% × 100% = $2,250
- Next 2%: $75,000 × 2% × 50% = $750
- Total Expected Match: $3,000

Actual Match Allocated: $3,000 ✓
```

### Profit Sharing/Non-Elective Contributions

#### Objectives
- Verify allocation method per plan document
- Confirm eligibility determination
- Test allocation accuracy
- Verify last-day requirements (if applicable)

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain plan document allocation formula | Plan document |
| 2 | Determine allocation method (pro-rata, integrated, etc.) | Plan terms |
| 3 | Obtain list of eligible participants | Eligibility report |
| 4 | Verify eligibility criteria applied | Census data |
| 5 | Calculate total eligible compensation | Compensation report |
| 6 | Calculate individual allocations | Allocation schedule |
| 7 | Compare to actual allocations | Contribution report |
| 8 | Trace contribution to trust | Bank statements |
| 9 | Verify posting to accounts | Participant statements |
| 10 | Test 415 limits | Limit testing report |

---

## Benefit Payments Testing

### Distributions to Participants

#### Objectives
- Verify distribution triggered by eligible event
- Confirm proper vesting applied
- Verify calculation accuracy
- Confirm proper authorization
- Verify tax withholding and reporting

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of distributions | Distribution report |
| 2 | Obtain distribution election form | Election form |
| 3 | Verify triggering event (termination, retirement, etc.) | HR records |
| 4 | Verify participant was eligible for distribution | Plan document |
| 5 | Calculate vested percentage | Vesting schedule |
| 6 | Verify account balance at distribution | Account statement |
| 7 | Calculate expected distribution amount | Calculation worksheet |
| 8 | Compare to actual distribution | Payment record |
| 9 | Verify proper authorization | Approval documentation |
| 10 | Verify tax withholding | Withholding calculation |
| 11 | Trace to 1099-R | Tax form |
| 12 | Trace to bank statement or check | Payment evidence |

#### Sample Distribution Test

```
Participant: Robert Johnson
Distribution Type: Termination - Full Distribution
Termination Date: September 30, 2024

Account Balance Summary:
- Employee deferrals: $45,000
- Employer match: $15,000
- Profit sharing: $8,000
- Total: $68,000

Vesting Analysis:
- Employee deferrals: 100% = $45,000
- Employer match: 80% (4 years) = $12,000
- Profit sharing: 80% (4 years) = $6,400
- Total vested: $63,400

Forfeitures: $68,000 - $63,400 = $4,600

Distribution:
- Gross amount: $63,400
- Federal withholding (20%): $12,680
- Net payment: $50,720

1099-R Amount: $63,400 ✓
```

### Hardship Withdrawals

#### Objectives
- Verify immediate and heavy financial need
- Confirm amount limited to need
- Verify proper documentation
- Confirm suspension of deferrals (if required by plan)

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of hardship withdrawals | Hardship report |
| 2 | Verify reason qualifies as safe harbor hardship | Hardship request |
| 3 | Review supporting documentation | Medical bills, etc. |
| 4 | Verify amount does not exceed need | Amount verification |
| 5 | Verify proper authorization | Approval documentation |
| 6 | Confirm distribution is from permitted sources | Account breakdown |
| 7 | Verify no rollover option provided | Distribution form |
| 8 | Verify 1099-R properly coded | Tax form |
| 9 | Test suspension of deferrals (if applicable) | Payroll records |

---

## Participant Account Testing

### Participant Data Accuracy

#### Objectives
- Verify census data is accurate
- Confirm eligibility properly determined
- Verify compensation used for contributions

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of participants | Participant list |
| 2 | Obtain personnel file information | HR records |
| 3 | Compare date of birth | Birth date verification |
| 4 | Compare date of hire | Hire date documentation |
| 5 | Compare compensation | W-2 or payroll |
| 6 | Verify eligibility entry date | Eligibility calculation |
| 7 | Verify employment status | Status records |
| 8 | Verify hours of service | Time records |
| 9 | Verify address | Address records |
| 10 | Test beneficiary designation | Beneficiary forms |

### Account Balance Verification

#### Objectives
- Verify account balances are accurately maintained
- Confirm all activity properly recorded
- Verify money source balances correct

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of participant accounts | Account list |
| 2 | Obtain beginning balance | Prior year statement |
| 3 | Add contributions | Contribution records |
| 4 | Add investment earnings | Earnings allocation |
| 5 | Subtract distributions | Distribution records |
| 6 | Subtract fees | Fee records |
| 7 | Account for transfers | Transfer records |
| 8 | Reconcile to ending balance | Year-end statement |
| 9 | Verify by money source | Source breakdown |

#### Sample Account Roll-Forward

```
Participant: Mary Williams
Account ID: 98765

Beginning Balance (1/1/24):                    $125,000

Activity:
+ Employee deferrals                            $18,400
+ Employer match                                 $6,200
+ Investment earnings                           $14,750
- Distributions                                     $0
- Administrative fees                             -$125
= Ending Balance (12/31/24):                  $164,225

Per Year-End Statement:                       $164,225 ✓
```

---

## Investment Testing

### Full Scope Investment Testing

#### Objectives
- Verify existence of investments
- Confirm accurate valuation
- Verify proper recording of transactions
- Test investment income allocation

#### Existence Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain year-end investment statements | Custodian statements |
| 2 | Send confirmation to custodian | Confirmation request |
| 3 | Receive and reconcile confirmation | Confirmation response |
| 4 | Investigate differences | Reconciliation |
| 5 | For securities, verify quantity and description | Statement detail |
| 6 | For alternative investments, verify existence | Investment documents |

#### Valuation Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain year-end fair values | Custodian report |
| 2 | For mutual funds, verify NAV to independent source | Pricing service |
| 3 | For collective trusts, obtain pricing methodology | Fund documents |
| 4 | For company stock, verify quoted price | Market data |
| 5 | For stable value, evaluate wrap contracts | Contract terms |
| 6 | For hard-to-value assets, evaluate methodology | Valuation analysis |
| 7 | Calculate fair value hierarchy classification | GAAP analysis |

#### Transaction Testing

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of purchases | Transaction report |
| 2 | Verify authorization | Approval records |
| 3 | Verify trade date and settlement | Trade confirmations |
| 4 | Verify pricing | Independent pricing |
| 5 | Select sample of sales | Transaction report |
| 6 | Verify proceeds calculation | Sale confirmation |
| 7 | Verify gain/loss calculation | Gain/loss report |
| 8 | Test dividend/interest income | Income statements |

### Limited Scope Investment Testing

#### Objectives
- Obtain proper certification
- Verify certified amounts
- Test non-certified items

#### Certification Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Identify certifying institution | Plan records |
| 2 | Obtain certification letter | Certification |
| 3 | Verify certification meets requirements | Checklist |
| 4 | Verify certification is signed | Signature verification |
| 5 | Verify certification date is appropriate | Date check |
| 6 | Trace certified amounts to financial statements | Reconciliation |
| 7 | Identify any non-certified investments | Investment analysis |
| 8 | Test non-certified investments fully | Testing workpapers |

#### Certification Requirements Checklist

```
☐ Certification is in writing
☐ Signed by authorized official
☐ Dated appropriately
☐ Confirms accuracy of information
☐ Confirms completeness of information
☐ States information prepared in accordance with GAAP
☐ Covers all required investment information:
  ☐ Fair value of investments
  ☐ Investment income
  ☐ Realized gains/losses
  ☐ Investment expenses
  ☐ Investment transactions
```

---

## Loan Testing

### Participant Loan Procedures

#### Objectives
- Verify loans comply with IRC 72(p)
- Confirm loans comply with plan terms
- Verify proper documentation
- Test for deemed distributions

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain loan register | Loan report |
| 2 | Select sample of outstanding loans | Selection documentation |
| 3 | Obtain loan documentation | Loan agreement |
| 4 | Verify loan does not exceed 50% of vested balance | Balance verification |
| 5 | Verify loan does not exceed $50,000 | Amount verification |
| 6 | Verify repayment term ≤ 5 years (or 15 for residence) | Loan terms |
| 7 | Verify level amortization | Amortization schedule |
| 8 | Verify reasonable interest rate | Rate documentation |
| 9 | Trace repayments to participant statements | Repayment records |
| 10 | Identify loans in default | Default report |
| 11 | Test deemed distribution treatment | Tax records |

#### Loan Compliance Test

```
Participant: James Anderson
Loan Date: March 1, 2024
Original Amount: $25,000

Compliance Tests:
1. Maximum Amount Test:
   - Vested balance at loan: $65,000
   - 50% of vested: $32,500
   - Maximum allowed: $32,500
   - Loan amount: $25,000 ✓ (below maximum)

2. $50,000 Maximum:
   - Loan amount: $25,000 ✓ (below $50,000)

3. Repayment Term:
   - Loan purpose: General purpose
   - Maximum term: 5 years (60 months)
   - Actual term: 48 months ✓

4. Amortization:
   - Monthly payment: $573.51
   - Interest rate: 6%
   - Level amortization: Yes ✓

5. Repayment Status:
   - Payments current: Yes ✓
   - Any missed payments: None ✓
```

---

## Forfeitures Testing

### Forfeiture Procedures

#### Objectives
- Verify forfeitures properly calculated
- Confirm timing of forfeiture
- Verify appropriate use of forfeitures
- Test forfeiture allocation (if applicable)

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain forfeiture activity report | Forfeiture report |
| 2 | Select sample of forfeitures | Selection documentation |
| 3 | Verify termination date | HR records |
| 4 | Verify vesting percentage at termination | Vesting calculation |
| 5 | Calculate expected forfeiture | Calculation worksheet |
| 6 | Compare to actual forfeiture | Forfeiture record |
| 7 | Verify proper timing of forfeiture | Plan terms |
| 8 | Trace forfeiture use | Forfeiture allocation |
| 9 | Verify use per plan document | Plan document |

#### Sample Forfeiture Calculation

```
Participant: Sarah Miller
Termination Date: July 15, 2024
Years of Service: 2.5 years
Vesting Schedule: 6-year graded

Account at Termination:
- Employee deferrals: $12,000 (100% vested)
- Employer match: $6,000
- Profit sharing: $4,000

Vesting Calculation (2 years):
- Match: $6,000 × 20% vested = $1,200 vested
- Profit sharing: $4,000 × 20% vested = $800 vested

Forfeitures:
- Match: $6,000 - $1,200 = $4,800
- Profit sharing: $4,000 - $800 = $3,200
- Total forfeiture: $8,000 ✓

Use of Forfeitures:
Per plan document: Applied to reduce employer contributions ✓
```

---

## Administrative Expenses Testing

### Expense Testing Procedures

#### Objectives
- Verify expenses are reasonable
- Confirm proper authorization
- Verify allocation method (if paid from plan)
- Test specific expense categories

#### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Obtain expense listing | Expense report |
| 2 | Review for reasonableness | Industry benchmarks |
| 3 | Select sample of expenses | Selection documentation |
| 4 | Verify proper authorization | Approval documentation |
| 5 | Verify service was received | Service agreements |
| 6 | Verify amount agrees to contract/invoice | Invoices |
| 7 | Verify payment | Check or wire record |
| 8 | Verify proper classification | GL coding |
| 9 | If allocated to participants, verify methodology | Allocation documentation |

---

## Compliance Testing Procedures

### ERISA Compliance Testing

| Area | Procedures |
|------|------------|
| Fidelity bond | Verify bond in place, adequate amount, proper coverage |
| SPD distribution | Sample test for timely distribution |
| SAR distribution | Verify timely distribution |
| QDIA notice | Verify proper notice provided |
| Fee disclosures | Test 404a-5 notice distribution |
| Blackout notices | If applicable, verify provided |

### Plan Document Compliance

| Area | Procedures |
|------|------------|
| Eligibility | Test sample for proper application |
| Contribution formulas | Verify applied as documented |
| Vesting | Test sample calculations |
| Distributions | Verify per plan terms |
| Loans | Verify terms match plan |

---

## Related Party Transaction Testing

### Objectives
- Identify related party relationships
- Test transactions with related parties
- Verify prohibited transaction exemptions

### Detailed Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Identify parties in interest | Relationship list |
| 2 | Identify related party transactions | Transaction analysis |
| 3 | Evaluate each transaction | Exemption analysis |
| 4 | Verify statutory or administrative exemption applies | Exemption documentation |
| 5 | Test terms of transactions | Transaction terms |
| 6 | Verify proper disclosure | Schedule G/H |

---

## Rollover Testing

### Incoming Rollover Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of rollovers | Rollover report |
| 2 | Verify rollover from eligible plan | Rollover certification |
| 3 | Verify proper documentation | Rollover forms |
| 4 | Verify timely deposit | Deposit records |
| 5 | Verify proper coding as rollover | Account records |
| 6 | Verify 100% vesting | Vesting status |

### Outgoing Rollover Procedures

| Step | Procedure | Documentation |
|------|-----------|---------------|
| 1 | Select sample of outgoing rollovers | Distribution report |
| 2 | Verify proper distribution election | Election form |
| 3 | Verify direct rollover to eligible plan/IRA | Rollover documentation |
| 4 | Verify no withholding on direct rollover | Payment record |
| 5 | Verify 1099-R properly coded | Tax form |

---

## Testing Documentation Summary

### Required Workpapers

| Area | Documentation Required |
|------|----------------------|
| Contributions | Sample selection, calculations, tracing |
| Distributions | Sample selection, eligibility, calculations, authorization |
| Participant data | Sample selection, verification to HR records |
| Investments | Confirmations, valuations, transactions |
| Loans | Sample selection, compliance calculations |
| Forfeitures | Calculations, use verification |
| Expenses | Sample selection, authorization, reasonableness |

### Conclusions

Each testing area should conclude with:
- Summary of procedures performed
- Exceptions identified
- Evaluation of exceptions
- Overall conclusion
- Effect on audit opinion

---

## Related Resources

- [Audit Overview](401k-audit-overview.md)
- [Audit Process](401k-audit-process.md)
- [Internal Controls Testing](401k-internal-controls.md)
- [Audit Findings](401k-audit-findings.md)

---

*Last Updated: 2024*
