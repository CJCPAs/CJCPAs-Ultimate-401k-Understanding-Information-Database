# Common 401(k) Audit Findings

## Overview

Understanding common audit findings helps plan sponsors proactively address issues before they become problems. This comprehensive guide covers the most frequently identified deficiencies, their causes, corrections, and prevention strategies.

## Table of Contents

1. [Contribution Issues](#contribution-issues)
2. [Participant Data Errors](#participant-data-errors)
3. [Distribution Problems](#distribution-problems)
4. [Loan Violations](#loan-violations)
5. [Investment Issues](#investment-issues)
6. [Fiduciary Failures](#fiduciary-failures)
7. [Documentation Deficiencies](#documentation-deficiencies)
8. [Compliance Failures](#compliance-failures)
9. [Internal Control Weaknesses](#internal-control-weaknesses)
10. [Correction Methods](#correction-methods)

---

## Contribution Issues

### Late Deposit of Employee Deferrals

**Description:**
Employee deferrals not deposited within the DOL's required timeframe.

**DOL Requirement:**
- Deposit as soon as reasonably possible
- No later than 15th business day of following month (this is the outer limit, not a safe harbor)
- Safe harbor for small plans: 7 business days

**Common Causes:**
- Lack of awareness of requirements
- Payroll processing delays
- Manual processes
- Staff turnover
- Cash flow management using participant funds

**Example Finding:**
```
Observation: During our testing of 40 payroll periods, we identified
15 instances where employee deferrals were deposited more than 7
business days after the payroll date.

Average Delay: 12 business days
Maximum Delay: 23 business days
Total Late Amount: $125,000
```

**Impact:**
- Lost earnings must be calculated and contributed
- Reportable on Form 5500 Schedule H
- DOL prohibited transaction
- Potential excise tax

**Correction:**
- Calculate lost earnings using DOL VFCP calculator
- Deposit deferrals plus lost earnings
- File under VFCP if significant
- Report on Schedule H

**Prevention:**
- Establish same-day or next-day deposit procedures
- Automate payroll/remittance process
- Monitor deposit timing
- Segregate payroll responsibilities

### Incorrect Deferral Calculations

**Description:**
Employee deferrals not calculated correctly based on elections.

**Common Causes:**
- Incorrect compensation definition
- System errors
- Bonus/commission exclusions
- Election not properly recorded
- Failure to apply limits

**Example Finding:**
```
Participant: John Smith
Election: 6% of compensation
Compensation: $100,000 (including $15,000 bonus)
Expected Deferral: $6,000
Actual Deferral: $5,100 (bonus excluded in error)
Underdeferral: $900
```

**Correction:**
- Calculate correct deferral
- Make up missed contributions
- QNEC if necessary under EPCRS

### Employer Contribution Errors

**Description:**
Employer matching or profit sharing contributions calculated incorrectly.

**Types of Errors:**
| Error Type | Description |
|------------|-------------|
| Formula error | Match formula not applied correctly |
| Eligibility error | Ineligible participant received contribution |
| Compensation error | Wrong compensation used |
| Exclusion error | Eligible participant excluded |
| Timing error | Contribution made too late |

**Example Finding:**
```
Plan match formula: 100% on first 3%, 50% on next 2%
Participant: Jane Doe
Compensation: $80,000
Deferral: 5% ($4,000)

Expected Match:
- First 3%: $80,000 × 3% = $2,400
- Next 2%: $80,000 × 2% × 50% = $800
- Total: $3,200

Actual Match: $2,400 (only first tier applied)
Underfunding: $800
```

---

## Participant Data Errors

### Incorrect Eligibility Determination

**Description:**
Employees not enrolled when eligible or enrolled too early.

**Common Causes:**
- Service calculation errors
- Age miscalculation
- Break in service not tracked
- Rehire not properly handled
- Entry date calculation wrong

**Example Finding:**
```
Employee: Mary Johnson
Hire Date: April 15, 2023
Plan Requirement: 1 year of service, 1,000 hours
Entry Dates: January 1 and July 1

Hours by April 14, 2024: 2,080
Actual Entry: July 1, 2024
Should Have Entered: April 15, 2024 (or January 1, 2024 
                      if entry date provision applied)
Missed Deferrals: 2.5 months
```

**Impact:**
- Lost opportunity to defer
- Must provide make-up contribution (QNEC)
- Lost employer match

### Incorrect Compensation

**Description:**
Wrong compensation used for contributions or testing.

**Common Errors:**
| Error | Result |
|-------|--------|
| Excluded bonuses | Understated deferrals/match |
| Included severance | Overstated eligible compensation |
| Wrong compensation period | Incorrect contribution calculation |
| Limit not applied | Contributions on excess compensation |

### Incorrect Vesting

**Description:**
Vesting percentage not calculated correctly.

**Common Causes:**
- Service not properly credited
- Break in service rules not applied
- Schedule not per plan document
- Prior plan service not counted

**Example Finding:**
```
Participant terminated after 4 years service
Plan schedule: 6-year graded
Correct vesting: 60%
Applied vesting: 40% (2-year graded used in error)
Underpayment: $3,000 of employer contributions
```

---

## Distribution Problems

### Incorrect Distribution Amount

**Description:**
Distribution amount does not match what participant was entitled to receive.

**Common Causes:**
- Vesting calculation error
- Account balance error
- Outstanding loan not accounted for
- Pending contributions not included
- Earnings not allocated

### Missing Spousal Consent

**Description:**
Required spousal consent not obtained for distribution.

**Requirement:**
- Plans subject to QJSA rules
- Spouse must consent to non-annuity distribution
- Witnessed or notarized

**Example Finding:**
```
Distribution: $150,000 lump sum
Married participant: Yes
QJSA plan: Yes
Spousal consent on file: None
Finding: Prohibited distribution without consent
```

### Improper Hardship Distribution

**Description:**
Hardship withdrawal does not meet requirements.

**Common Issues:**
| Issue | Description |
|-------|-------------|
| Not safe harbor event | Reason doesn't qualify |
| Excess amount | More than needed |
| Missing documentation | No supporting evidence |
| Rollover permitted | Should not allow rollover |

### Failure to Make Required Minimum Distributions

**Description:**
RMDs not made when required.

**Common Causes:**
- Plan doesn't track RMD eligibility
- "Still working" exception misapplied
- Wrong life expectancy factor
- Calculation error

**Example Finding:**
```
Participant: Robert Williams, Age 75
Status: Retired
Account Balance (prior year-end): $500,000
Required RMD: $500,000 ÷ 24.6 = $20,325
Actual Distribution: $0
50% Excise Tax (pre-SECURE 2.0): $10,163
```

---

## Loan Violations

### Exceeding Maximum Loan Amount

**Description:**
Loan exceeds IRC Section 72(p) limits.

**Limits:**
- Lesser of $50,000 or 50% of vested balance
- $50,000 reduced by highest outstanding balance in prior 12 months

**Example Finding:**
```
Participant: James Brown
Vested Balance: $80,000
50% of Vested: $40,000
Loan Amount: $45,000

Issue: Loan exceeds 50% of vested balance
Excess: $5,000
Result: Entire $45,000 is deemed distribution
```

### Loan in Default/Deemed Distribution Not Processed

**Description:**
Participant has stopped repaying loan, but no deemed distribution processed.

**Default occurs:**
- When payment missed per plan terms
- After cure period expires
- Creates deemed distribution

**Example Finding:**
```
Loan: $25,000
Last Payment: January 2024
Cure Period: Per plan, loan defaults after 3 missed payments
Status as of Audit: 6 missed payments
Deemed Distribution Date: Should have been April 2024
1099-R Issued: None
```

### Improper Loan Terms

**Description:**
Loan does not meet IRC requirements.

**Requirements:**
| Requirement | Standard |
|-------------|----------|
| Repayment term | 5 years maximum (15 for primary residence) |
| Repayment method | Level amortization |
| Interest rate | Reasonable (typically prime + 1%) |
| Documentation | Written, enforceable |

---

## Investment Issues

### Failure to Follow Investment Policy

**Description:**
Investments not consistent with documented investment policy.

**Common Issues:**
- Investments outside policy parameters
- No regular monitoring
- Underperforming funds not addressed
- Fee benchmarking not performed

### Missing or Incomplete Investment Documentation

**Description:**
Inadequate documentation of investment decisions.

**Example Finding:**
```
Observation: The Committee changed the small-cap fund option
during the year. We were unable to obtain documentation of:
- Analysis performed for fund selection
- Committee meeting minutes approving change
- Comparison of alternatives considered
- Fee analysis
```

### Incorrect Investment Valuation

**Description:**
Investments not valued at fair value per GAAP.

**Common Issues:**
- Stale pricing
- Improper valuation methodology
- Hard-to-value assets not assessed
- Limited marketability not considered

---

## Fiduciary Failures

### Lack of Fiduciary Process

**Description:**
No documented process for fiduciary decisions.

**Missing Elements:**
| Element | Issue |
|---------|-------|
| Meeting minutes | Decisions not documented |
| Committee charter | Roles not defined |
| Monitoring procedures | No regular review |
| Service provider review | No benchmarking |

### Excessive Fees

**Description:**
Plan fees exceed reasonable levels for services provided.

**Example Finding:**
```
Plan Assets: $5,000,000
Recordkeeping Fee: $35,000 (0.70%)
Industry Benchmark (similar size): $15,000-$20,000 (0.30%-0.40%)
Observation: Fees significantly exceed benchmarks
Recommendation: Obtain competitive bids
```

### Prohibited Transactions

**Description:**
Transactions that are prohibited under ERISA Section 406.

**Common Prohibited Transactions:**
| Transaction | Issue |
|-------------|-------|
| Late deposits | Loan from plan to employer |
| Party-in-interest deals | Non-arm's length transactions |
| Self-dealing | Fiduciary benefits from decision |
| Improper use of assets | Not for exclusive benefit |

---

## Documentation Deficiencies

### Missing Plan Document Amendments

**Description:**
Plan document not updated for required changes.

**Common Missing Amendments:**
- SECURE Act provisions
- SECURE 2.0 provisions
- CARES Act changes
- Regulatory updates
- IRS remedial amendment period items

### Missing or Outdated SPD

**Description:**
Summary Plan Description not current or not distributed.

**Requirements:**
- Provide within 90 days of becoming participant
- Update within 210 days of plan year end (if changes)
- SMM for interim changes

### Missing Beneficiary Designations

**Description:**
Beneficiary forms not on file for participants.

**Example Finding:**
```
Participants with Balances: 500
Missing Beneficiary Forms: 85 (17%)
Impact: Default beneficiary provisions apply
Risk: May not reflect participant intent
```

---

## Compliance Failures

### Nondiscrimination Test Failures

**Description:**
Plan fails ADP, ACP, or other nondiscrimination tests.

**Common Issues:**
| Test | Issue |
|------|-------|
| ADP Test | HCE deferrals too high relative to NHCEs |
| ACP Test | HCE matching too high |
| Coverage Test | Not enough NHCEs covered |
| Top-Heavy | Key employees exceed 60% of assets |

### Failure to Apply Contribution Limits

**Description:**
Contributions exceeded IRS limits.

**Limits Tested:**
- 402(g) - Employee deferral limit
- 415 - Annual additions limit
- 401(a)(17) - Compensation limit
- Catch-up eligibility

**Example Finding:**
```
Participant: Susan Davis, Age 48
Deferrals: $25,000
402(g) Limit: $23,000
Excess: $2,000

Issue: Non-catch-up eligible participant exceeded limit
Correction: Distribute excess plus earnings by April 15
```

### Form 5500 Errors

**Description:**
Errors or inconsistencies in Form 5500 filing.

**Common Errors:**
| Error | Description |
|-------|-------------|
| Participant count | Doesn't match records |
| Asset amounts | Don't match financial statements |
| Missing schedules | Required schedules omitted |
| Late filing | Not filed timely |

---

## Internal Control Weaknesses

### Inadequate Segregation of Duties

**Description:**
Same person performs incompatible functions.

**Example:**
```
Finding: The Payroll Manager:
- Processes payroll
- Initiates 401(k) remittances
- Reconciles bank accounts
- Reviews participant accounts

Risk: Single individual controls entire process
Recommendation: Segregate duties or implement compensating controls
```

### Lack of Reconciliation

**Description:**
Plan accounts not reconciled regularly.

**Should Reconcile:**
| Account | Frequency |
|---------|-----------|
| Trust account to recordkeeper | Monthly |
| Participant accounts to total | Quarterly |
| Contributions to payroll | Each payroll |
| Loans outstanding | Quarterly |

### Missing Review/Approval

**Description:**
No review or approval of transactions.

**Example Finding:**
```
Observation: Distributions processed without 
second-party review or approval.

28 distributions tested
0 had evidence of secondary approval
Total value: $1.2 million

Risk: Unauthorized or incorrect distributions
```

---

## Correction Methods

### IRS Correction Programs (EPCRS)

#### Self-Correction Program (SCP)

**For:** Insignificant operational failures, significant failures in qualified plans with established practices

**Requirements:**
- Plan must be qualified
- Reasonable practices to ensure compliance
- Correction within time limits
- No IRS fee

#### Voluntary Correction Program (VCP)

**For:** Operational and plan document failures

**Process:**
1. Identify failure
2. Calculate correction
3. Prepare submission
4. Pay applicable fee
5. Receive compliance statement

**Fees (2024):**
| Plan Assets | Fee |
|-------------|-----|
| Under $500,000 | $1,500 |
| $500,000 - $10 million | $3,000 |
| Over $10 million | $3,500 |

#### Audit Closing Agreement Program (Audit CAP)

**For:** Failures found during IRS audit

**Process:**
- Negotiate with IRS
- Correction determined by IRS
- Sanction amounts negotiated
- Closing agreement executed

### DOL Correction Programs

#### Voluntary Fiduciary Correction Program (VFCP)

**For:** Certain fiduciary violations

**Covered Violations:**
- Late deposits
- Improper participant loans
- Delinquent loan repayments
- Imprudent investments
- Improper expenses

**Benefits:**
- No civil penalties
- No excise taxes (if corrected)
- Class exemption for certain transactions

#### Delinquent Filer Voluntary Compliance Program (DFVCP)

**For:** Late Form 5500 filings

**Reduced Penalties:**
| Plan Type | Per Day | Maximum |
|-----------|---------|---------|
| Small Plan | $10 | $750 |
| Large Plan | $10 | $2,000 |

---

## Prevention Strategies

### Administrative Best Practices

1. **Document everything** - Meeting minutes, decisions, processes
2. **Review regularly** - Contributions, participant data, compliance
3. **Train personnel** - Keep staff current on requirements
4. **Monitor service providers** - Regular oversight and review
5. **Stay current** - Track regulatory changes

### Control Environment

1. **Segregate duties** - No single person controls process
2. **Require approvals** - Multiple levels for significant transactions
3. **Reconcile regularly** - Monthly at minimum
4. **Audit internally** - Periodic self-audits
5. **Maintain policies** - Written procedures for all functions

### Audit Preparation

1. **Start early** - Begin gathering documents well before audit
2. **Review prior findings** - Ensure corrections implemented
3. **Self-assess** - Identify issues before auditor does
4. **Organize documentation** - Make records accessible
5. **Communicate** - Keep all parties informed

---

## Related Resources

- [Audit Overview](401k-audit-overview.md)
- [Audit Process](401k-audit-process.md)
- [Audit Reports](401k-audit-reports.md)
- [Correction Programs](401k-correction-programs.md)

---

*Last Updated: 2024*
