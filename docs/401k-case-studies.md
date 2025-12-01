# 401(k) Plan Audit Case Studies

Real-world scenarios and examples illustrating common audit situations, findings, and resolutions. These case studies provide practical guidance for handling complex audit issues.

---

## Table of Contents

1. [Case Study 1: Late Participant Contributions](#case-study-1-late-participant-contributions)
2. [Case Study 2: Invalid Certification](#case-study-2-invalid-certification)
3. [Case Study 3: ADP/ACP Test Failure](#case-study-3-adpacp-test-failure)
4. [Case Study 4: Participant Loan Violations](#case-study-4-participant-loan-violations)
5. [Case Study 5: Hardship Distribution Errors](#case-study-5-hardship-distribution-errors)
6. [Case Study 6: Missing Participants](#case-study-6-missing-participants)
7. [Case Study 7: Prohibited Transactions](#case-study-7-prohibited-transactions)
8. [Case Study 8: First-Year Audit Challenges](#case-study-8-first-year-audit-challenges)
9. [Case Study 9: Employer in Financial Distress](#case-study-9-employer-in-financial-distress)
10. [Case Study 10: Merger and Acquisition](#case-study-10-merger-and-acquisition)
11. [Case Study 11: Self-Directed Brokerage Issues](#case-study-11-self-directed-brokerage-issues)
12. [Case Study 12: Material Weakness Identification](#case-study-12-material-weakness-identification)
13. [Case Study 13: Mid-Year TPA Change with Partial Certification](#case-study-13-mid-year-tpa-change-with-partial-certification)
14. [Case Study 14: Amended Adoption Agreement Without Determination Letter](#case-study-14-amended-adoption-agreement-without-determination-letter)

---

## Case Study 1: Late Participant Contributions

### Background

**Plan:** ABC Manufacturing 401(k) Plan
**Participants:** 350
**Plan Year:** December 31, 20XX
**Audit Type:** Limited Scope

During contribution testing, you discover that participant deferrals are consistently deposited 10-14 business days after each bi-weekly payroll.

### Facts Discovered

| Pay Date | Deposit Date | Days Elapsed | Amount |
|----------|--------------|--------------|--------|
| 1/15/XX | 2/3/XX | 13 business days | $45,000 |
| 1/29/XX | 2/17/XX | 13 business days | $47,500 |
| 2/12/XX | 3/2/XX | 12 business days | $44,200 |
| ... | ... | ... | ... |
| 12/17/XX | 1/8/XX+1 | 14 business days | $52,000 |

**Total contributions for year:** $1,180,000
**All 26 payrolls:** 10-14 business days late

### Analysis

**DOL Safe Harbor:** Deposits within 7 business days are generally considered timely for plans with fewer than 100 participants. For larger plans, the standard is "as soon as administratively feasible."

**Key Questions:**
1. Is there a valid business reason for the delay?
2. Has the pattern been consistent?
3. What is the lost earnings impact?

### Client's Explanation

The HR Director explained:
- Payroll is processed by an external provider
- Contribution reports are received 3 days after payroll
- Manual reconciliation takes 2-3 days
- Wire transfers are only processed on Wednesdays

### Auditor's Conclusion

**Finding:** Late remittance of participant contributions – Prohibited Transaction

**Reasoning:**
- 10-14 business days exceeds any reasonable interpretation of "as soon as administratively feasible"
- Pattern is consistent, indicating systemic issue, not isolated incidents
- No technical barrier exists to faster remittance
- This constitutes a prohibited transaction under ERISA Section 406(a)(1)(D) and IRC Section 4975

### Resolution Steps

1. **Calculate Lost Earnings**
   - Use DOL Online Calculator for each late deposit
   - Apply IRC Section 6621(a)(2) underpayment rate
   - Calculate from "should have been deposited" date to actual deposit

   **Example Calculation (one payroll):**
   ```
   Payroll: 1/15/XX
   Should have been deposited: 1/24/XX (7 business days)
   Actually deposited: 2/3/XX
   Late period: 10 days
   Amount: $45,000
   Underpayment rate: 8% annually

   Lost earnings = $45,000 × (8%/365) × 10 = $98.63
   ```

2. **Deposit Lost Earnings**
   - Total lost earnings for year: $2,847
   - Allocate to affected participant accounts

3. **File Under VFCP**
   - Consider filing under DOL's Voluntary Fiduciary Correction Program
   - Provides "no action" letter from DOL
   - Requires correction and documentation

4. **Report on Schedule of Delinquent Contributions**
   - Include in supplemental schedules

5. **Recommend Process Improvements**
   - Electronic payroll feeds
   - Daily contribution deposits
   - Eliminate manual reconciliation

### Audit Documentation

```
Finding: Late Remittance of Participant Contributions

Condition: Participant contributions were deposited 10-14 business
days after each payroll throughout the plan year.

Criteria: DOL regulations require participant contributions to be
remitted as soon as administratively feasible, generally within
7 business days for small plans.

Cause: Inefficient manual reconciliation process and weekly wire
transfer schedule.

Effect: Prohibited transaction; lost earnings of $2,847 owed to
participant accounts; potential DOL penalties.

Recommendation: Implement electronic payroll feeds and daily
contribution deposits. File under VFCP. Deposit lost earnings.
```

### Key Takeaways

- Late contributions are a common finding
- Calculate lost earnings using DOL methodology
- Consider VFCP filing for DOL protection
- Report on Schedule of Delinquent Contributions
- Recommend specific process improvements

---

## Case Study 2: Invalid Certification

### Background

**Plan:** XYZ Services 401(k) Plan
**Participants:** 180
**Plan Year:** December 31, 20XX
**Audit Type:** Initially Limited Scope

The plan administrator provided a certification from the recordkeeper (a national mutual fund company) to support a limited scope audit.

### The Certification Received

```
[Mutual Fund Company Letterhead]

INVESTMENT CERTIFICATION

To the Plan Administrator:

We certify that the attached investment statements for the
XYZ Services 401(k) Plan are complete and accurate as of
December 31, 20XX.

Total Investments: $8,547,293

[Signature]
Vice President, Retirement Services
```

### Analysis

**Problems with this Certification:**

| Requirement | Met? | Issue |
|-------------|------|-------|
| Qualifying institution? | ❌ | Mutual fund company is NOT a bank, trust company, or insurance carrier |
| Regulated by federal/state agency? | ⚠️ | SEC-regulated but not for custody purposes |
| Includes all required elements? | ❌ | Missing: investment income, gains/losses, transactions |
| Covers entire plan year? | ❌ | Only certifies ending balances |
| Proper certifying language? | ❌ | Does not certify "complete and accurate" per DOL |

### Auditor's Response

**Step 1: Notify Plan Administrator**

> "We have evaluated the certification provided and determined it does not meet the requirements of ERISA Section 103(a)(3)(C) for the following reasons:
>
> 1. The certifying entity (mutual fund company) is not a qualifying institution under DOL regulations
> 2. The certification does not include all required elements (income, gains/losses, transactions)
>
> Without a valid certification, we cannot perform a limited scope audit."

**Step 2: Identify Alternatives**

| Option | Description | Feasibility |
|--------|-------------|-------------|
| Obtain proper certification | Request from the actual trustee (bank) | Preferred if bank serves as trustee |
| Convert to full scope | Perform full substantive testing on investments | Required if no valid certification available |
| Locate trust agreement | Determine who actually holds assets | First step |

**Step 3: Resolution**

Upon review of the trust agreement, it was discovered that:
- A national bank serves as trustee
- The mutual fund company is only the recordkeeper
- The bank can provide a proper certification

**New Certification Obtained:**

```
[National Bank Letterhead]

CERTIFICATION OF INVESTMENT INFORMATION
ERISA Section 103(a)(3)(C)

Plan Name: XYZ Services 401(k) Plan
Plan Year Ended: December 31, 20XX
EIN: XX-XXXXXXX  Plan Number: 001

We hereby certify that the information in the attached statements
prepared by [Bank Name] and furnished to the Plan Administrator
for preparation of the annual return/report of the Plan is complete
and accurate as of the date of this certification.

The certified information includes:
- Fair value of investments at beginning of year: $7,892,156
- Fair value of investments at end of year: $8,547,293
- Investment income: $312,847
- Net realized and unrealized gains: $342,290
- All investment transactions during the plan year

This certification is provided in accordance with the requirements
of 29 CFR 2520.103-8.

[Signature]
[Title], [Bank Name]
Dated: March 15, 20XX+1

[Bank Name] is a [state]-chartered bank regulated by [State Agency]
and the Office of the Comptroller of the Currency.
```

### Key Takeaways

- Always verify the certifying entity is a qualifying institution
- Mutual fund companies and broker-dealers do NOT qualify
- The actual trustee/custodian must provide certification
- Know the difference between recordkeeper and trustee
- Review the trust agreement to identify proper parties

---

## Case Study 3: ADP/ACP Test Failure

### Background

**Plan:** Tech Startup 401(k) Plan
**Participants:** 125 (15 HCEs, 110 NHCEs)
**Plan Year:** December 31, 20XX
**Plan Type:** Traditional 401(k) with 50% match on first 6%

### Compliance Testing Results

**ADP Test:**

| Group | Average Deferral % |
|-------|--------------------|
| HCEs | 8.5% |
| NHCEs | 3.2% |

**ADP Test Limits:**

```
NHCE Average: 3.2%
Maximum HCE Average (3.2% + 2%): 5.2%
Actual HCE Average: 8.5%
RESULT: FAILED (HCEs exceed limit by 3.3%)
```

**ACP Test:**

| Group | Average Contribution % |
|-------|-----------------------|
| HCEs | 2.8% |
| NHCEs | 1.4% |

**ACP Test Limits:**

```
NHCE Average: 1.4%
Maximum HCE Average (1.4% × 2): 2.8%
Actual HCE Average: 2.8%
RESULT: PASSED (exactly at limit)
```

### Auditor's Procedures

**1. Verify Test Accuracy**

| Step | Procedure | Result |
|------|-----------|--------|
| 1 | Verify HCE identification | 15 HCEs correctly identified (5% owners + $155,000 threshold) |
| 2 | Verify compensation used | 415 compensation properly calculated |
| 3 | Test sample of individual ADPs | Agreed to underlying records |
| 4 | Recalculate group averages | Confirmed test results |

**2. Evaluate Correction**

The plan administrator indicated the failure was discovered in February (after plan year end) and the TPA recommended corrective distributions to HCEs.

**Correction Timeline:**

| Date | Event |
|------|-------|
| Dec 31, 20XX | Plan year end |
| Feb 15, 20XX+1 | ADP test completed, failure discovered |
| March 1, 20XX+1 | Corrective distributions calculated |
| March 10, 20XX+1 | Corrective distributions processed |
| March 15, 20XX+1 | Deadline for distributions without 10% excise tax |

### Corrective Distribution Calculation

**Method:** Leveling Method (starting with highest HCE ADPs)

| HCE | Original Deferral | Original ADP | Revised ADP | Excess Amount |
|-----|-------------------|--------------|-------------|---------------|
| CEO | $23,000 | 12.5% | 5.2% | $13,432 |
| CFO | $23,000 | 11.8% | 5.2% | $12,144 |
| VP Sales | $20,500 | 9.8% | 5.2% | $9,639 |
| ... | ... | ... | ... | ... |
| **Total** | | | | **$52,847** |

**Allocable Income:**
```
Excess Amount: $52,847
Investment Return (Jan 1 - March 10): 2.1%
Allocable Income: $52,847 × 2.1% = $1,110

Total Corrective Distribution: $53,957
```

### Audit Documentation

**Finding:** ADP test failure corrected through timely corrective distributions

**Condition:** The plan failed the ADP test for the 20XX plan year. HCE average deferral percentage of 8.5% exceeded the maximum allowable of 5.2%.

**Correction:** Corrective distributions totaling $53,957 (including allocable income) were made to 8 HCEs on March 10, 20XX+1.

**Compliance Status:** Distributions were made within 2½ months after plan year end; therefore, no 10% excise tax applies. Corrective distributions are taxable to recipients in 20XX.

**Recommendation:** Consider converting to Safe Harbor 401(k) to avoid future testing failures.

### Form 1099-R Reporting

| Box | Content |
|-----|---------|
| 1 | Gross distribution: $53,957 |
| 2a | Taxable amount: $53,957 |
| 7 | Distribution code: P (excess contributions plus earnings) |
| Tax year | 20XX (the year of excess) |

### Key Takeaways

- ADP/ACP test failures are common
- Corrective distributions must be made by March 15 to avoid 10% excise tax
- Calculate allocable income through distribution date
- Document correction method and timing
- Consider recommending Safe Harbor conversion

---

## Case Study 4: Participant Loan Violations

### Background

**Plan:** Regional Healthcare 401(k) Plan
**Participants:** 500
**Plan Year:** December 31, 20XX
**Loan Program:** Yes, per plan document

### Sample Selection

From 85 outstanding loans, selected 20 for testing.

### Findings

| Loan # | Issue | Details |
|--------|-------|---------|
| 12 | Exceeds 50%/50K limit | Loan of $55,000; vested balance was $95,000 |
| 27 | Term exceeds 5 years | 7-year term for "vacation" |
| 45 | Payments not level | Balloon payment at end |
| 67 | No promissory note | Verbal agreement only |
| 89 | Cure period exceeded | Missed payments for 9 months |

### Detailed Analysis

**Loan #12 – Exceeded Maximum Amount**

```
Participant: John Smith
Date of Loan: April 15, 20XX
Loan Amount: $55,000
Vested Balance (at loan): $95,000

CALCULATIONS:
50% of vested balance: $47,500
$50,000 statutory limit: $50,000
Highest outstanding balance (prior 12 months): $0

Maximum allowable: $47,500 (lesser of 50% or $50K)
Actual loan: $55,000
Excess: $7,500

CONCLUSION: Deemed distribution of $7,500 on April 15, 20XX
```

**Loan #27 – Exceeded Term**

```
Participant: Jane Doe
Purpose: Personal vacation
Original Amount: $15,000
Term: 84 months (7 years)
Maximum Term for Non-Residence: 60 months (5 years)

CONCLUSION: Loan does not satisfy IRC 72(p)
             Deemed distribution of $15,000 on loan date
```

**Loan #89 – Cure Period Exceeded**

```
Participant: Bob Wilson
Original Loan: $25,000
Last Payment: March 15, 20XX
Outstanding Balance: $18,500
Cure Period End: June 30, 20XX (end of quarter + 1 quarter)
Audit Date: December 15, 20XX

Status: 9 months since last payment
Cure period expired: June 30, 20XX

CONCLUSION: Deemed distribution of $18,500 on July 1, 20XX
```

### Resolution

**For Each Deemed Distribution:**

1. **Tax Reporting:**
   - Issue Form 1099-R
   - Code L (loan treated as distribution)
   - Taxable in year deemed distribution occurs
   - 10% early withdrawal penalty if under age 59½

2. **Account Adjustment:**
   - Loan offset reduces participant balance
   - Investment in contract (basis) created

3. **Prohibited Transaction:**
   - Loans not meeting 72(p) are prohibited transactions
   - Report on Schedule G (if not corrected)
   - Excise tax under IRC 4975

**Correction Options:**

| Loan | Correction Approach |
|------|---------------------|
| #12 | VCP filing; return excess $7,500 + earnings to account |
| #27 | VCP filing; restructure to 5-year term |
| #45 | Restructure payment schedule |
| #67 | Execute proper promissory note |
| #89 | Deemed distribution occurred; cannot be corrected |

### Audit Documentation

```
Finding: Multiple Participant Loan Violations

Condition: 5 of 20 sampled loans (25%) contained violations of
IRC Section 72(p) or plan document terms.

Criteria: IRC 72(p) requires loans to:
- Not exceed 50% of vested balance or $50,000
- Have maximum 5-year term (except principal residence)
- Be repaid in substantially level payments at least quarterly
- Be documented with enforceable agreement

Cause: Lack of controls over loan approval process;
inadequate training of HR personnel.

Effect: Deemed distributions totaling $41,000; prohibited
transactions; participant tax liability; plan disqualification risk.

Recommendation: Implement loan approval controls including:
- Systematic calculation of maximum loan amount
- Required promissory note execution before funding
- Automated repayment monitoring with alerts
- File VCP for correctable violations
```

### Key Takeaways

- Loan violations can result in deemed distributions
- Deemed distributions create prohibited transactions
- Some violations can be corrected under VCP
- Strong controls over loan processing are essential
- Test both loan origination and ongoing repayment

---

## Case Study 5: Hardship Distribution Errors

### Background

**Plan:** Construction Company 401(k) Plan
**Participants:** 275
**Plan Year:** December 31, 20XX
**Hardship Distributions:** 12 during plan year

### Testing Performed

Tested all 12 hardship distributions.

### IRS Safe Harbor Requirements

For distributions to qualify as hardship under safe harbor:

**Immediate and Heavy Financial Need (must be one of):**
- Medical expenses
- Purchase of principal residence
- Tuition and education expenses
- Prevent eviction or foreclosure
- Funeral expenses
- Repair of damage to principal residence

**Distribution Necessary to Satisfy Need:**
- Employee has obtained all other available distributions
- Employee has obtained all available loans (unless loan would increase need)

### Findings

| # | Amount | Stated Purpose | Documentation | Issue |
|---|--------|----------------|---------------|-------|
| 3 | $15,000 | Medical | Doctor's letter | None - OK |
| 5 | $8,500 | Purchase home | None | No documentation |
| 7 | $22,000 | "Bills" | Credit card statements | Not qualifying purpose |
| 9 | $12,000 | Tuition | University bill | None - OK |
| 11 | $5,000 | Car repair | Repair invoice | Not qualifying purpose |

### Detailed Analysis

**Distribution #5 – No Documentation**

```
Participant: Mike Johnson
Amount: $8,500
Stated Purpose: Down payment on home

DOCUMENTATION PROVIDED: None

REQUIRED DOCUMENTATION:
- Purchase contract or closing statement
- Amount showing $8,500 is needed

CONCLUSION: Cannot verify hardship
             May not be valid distribution
```

**Distribution #7 – Non-Qualifying Purpose**

```
Participant: Sarah Williams
Amount: $22,000
Stated Purpose: "Pay off bills"
Documentation: Credit card statements showing $22,000 balance

ANALYSIS:
- Credit card debt is NOT a qualifying hardship purpose
- Does not fit any of the 6 safe harbor categories
- Even if participant is financially stressed,
  credit card debt alone does not qualify

CONCLUSION: Invalid hardship distribution
             Should have been denied
```

### Resolution Steps

**For Invalid Distributions:**

| Option | Description | Consequence |
|--------|-------------|-------------|
| VCP Filing | Correct under IRS program | Employee repays amount; plan deposits earnings |
| Recharacterize | Treat as other in-service (if eligible) | Must meet other distribution rules |
| Leave as-is | Document finding; potential disqualification | Plan operational failure |

**Recommended Corrections:**

- **Distribution #5:** Obtain documentation retroactively if possible
- **Distribution #7:** VCP filing; employee repays $22,000 + earnings
- **Distribution #11:** VCP filing; employee repays $5,000 + earnings

### Control Recommendations

```
Hardship Distribution Controls:

1. DOCUMENTATION CHECKLIST
   □ Written request from participant
   □ Specific hardship reason stated
   □ Supporting documentation by category:
     - Medical: Bills, EOBs, provider statements
     - Home Purchase: Contract, closing disclosure
     - Tuition: School bill, enrollment verification
     - Eviction/Foreclosure: Notice from lender/landlord
     - Funeral: Death certificate, funeral home invoice
     - Home Repair: Contractor estimate, photos

2. APPROVAL PROCESS
   □ HR review of documentation
   □ Verification of qualifying purpose
   □ Calculation of maximum amount
   □ Secondary approval for amounts > $10,000

3. AMOUNT LIMITATIONS
   □ Cannot exceed the amount of need
   □ Include taxes and penalties in calculation
   □ Document calculation of need
```

### Key Takeaways

- Hardship distributions require specific documentation
- Only 6 safe harbor purposes qualify
- "Bills" or "debt" alone does not qualify
- Strong documentation controls prevent errors
- Invalid hardships can be corrected under VCP

---

## Case Study 6: Missing Participants

### Background

**Plan:** Retail Chain 401(k) Plan
**Participants:** 850 active, 215 terminated with balances
**Plan Year:** December 31, 20XX
**Terminated Participant Accounts:** $2,340,000

### Discovery

During participant data testing, you notice:
- 47 terminated participants have not taken distributions
- Many have outdated addresses
- Some accounts date back 10+ years

### Testing Performed

Selected 15 terminated participants with balances:

| Status | Count | Total Balance |
|--------|-------|---------------|
| Valid address, no RMD issue | 6 | $185,000 |
| Returned mail | 5 | $95,000 |
| Over RMD age, no distribution | 3 | $67,000 |
| No contact in 5+ years | 1 | $12,000 |

### Key Issues

**1. Returned Mail / Missing Participants**

```
5 participants with returned mail:
- John Smith: Balance $22,000, terminated 2018
- Jane Doe: Balance $18,500, terminated 2019
- Robert Brown: Balance $31,000, terminated 2016
- Mary Johnson: Balance $12,500, terminated 2020
- William Davis: Balance $11,000, terminated 2017
```

**2. RMD Failures**

```
3 participants over age 73:
- Edward Miller: Age 76, balance $28,000, no RMDs taken
- Patricia Wilson: Age 74, balance $22,000, no RMDs taken
- James Taylor: Age 78, balance $17,000, no RMDs taken
```

### Fiduciary Obligations

**DOL Guidance on Missing Participants:**

Plan fiduciaries must take reasonable steps to locate missing participants:
1. Certified mail to last known address
2. Check related plan records
3. Contact designated beneficiary
4. Use free electronic search tools (SSA letter forwarding, etc.)
5. Use commercial locator services
6. Search internet and social media

### Required Corrections

**For RMD Failures:**

```
Participant: Edward Miller
Age: 76
Balance (12/31/XX): $28,000
Required Beginning Date: April 1, 20XX-2 (age 73)

RMD Calculation (using Uniform Lifetime Table):
Year 1 (age 73): $28,000 / 26.5 = $1,057
Year 2 (age 74): $28,500 / 25.5 = $1,118
Year 3 (age 75): $29,000 / 24.6 = $1,179
Year 4 (age 76): $28,000 / 23.7 = $1,181

Total Missed RMDs: $4,535

50% Excise Tax (participant liability): $2,268
```

**Correction Steps:**
1. Locate participant using search methods
2. Distribute missed RMDs
3. Participant files Form 5329 requesting penalty waiver
4. Document reasonable cause for waiver

**For Missing Participants:**

| Step | Action | Deadline |
|------|--------|----------|
| 1 | Certified mail to last address | Immediately |
| 2 | Search plan/employer records | Within 30 days |
| 3 | Use free locator services | Within 60 days |
| 4 | Consider commercial locator | Within 90 days |
| 5 | Document all search efforts | Ongoing |

**If Participant Cannot Be Located:**

Options for small balances (≤$7,000):
- Automatic rollover to IRA
- Escheat to state (if allowed by plan/law)

Options for larger balances:
- Continue search efforts
- Maintain in plan
- Consider DOL Missing Participant Program (terminated plans only)

### Audit Documentation

```
Finding: Missing Participants and RMD Failures

Condition:
- 5 terminated participants with returned mail ($95,000)
- 3 participants over RMD age with no distributions ($67,000)

Criteria:
- DOL requires reasonable efforts to locate missing participants
- IRC 401(a)(9) requires RMDs beginning at age 73

Cause:
- No systematic process for locating missing participants
- No monitoring of participants reaching RMD age

Effect:
- 50% excise tax liability for RMD failures (participant)
- Fiduciary breach for failing to locate participants
- Account balances may be escheated to state

Recommendation:
1. Implement missing participant search procedures
2. Create RMD monitoring and distribution system
3. Consider automatic rollover program for small balances
4. File VCP for RMD failures
```

### Key Takeaways

- Missing participants are a fiduciary issue
- Document all search efforts
- RMD monitoring is essential for terminated participants
- Consider automatic rollover programs
- File Form 5329 for penalty waiver on missed RMDs

---

## Case Study 7: Prohibited Transactions

### Background

**Plan:** Family Business 401(k) Plan
**Participants:** 45
**Plan Year:** December 31, 20XX
**Ownership:** 100% owned by Smith family

### Discovery

During expense testing, you notice a payment of $50,000 from the plan to "Smith Properties LLC" for "rent."

### Investigation

**Inquiry of Management:**

Q: What is Smith Properties LLC?
A: A real estate company owned by the Smith family that owns our office building.

Q: What was the $50,000 payment for?
A: The plan was paying rent for office space used for plan administration.

### Analysis

**Party-in-Interest Test:**

```
Smith Properties LLC:
- Owned by 5% owners of plan sponsor ✓
- Therefore: Party-in-Interest under ERISA 3(14)(H)

Transaction Type:
- Furnishing of goods/services (office space rental)
- ERISA 406(a)(1)(C) prohibits furnishing of services
  between plan and party-in-interest

CONCLUSION: Prohibited Transaction (unless exemption applies)
```

**Exemption Analysis:**

| Exemption | Applicable? | Reasoning |
|-----------|-------------|-----------|
| ERISA 408(b)(2) - Reasonable compensation | Possibly | If rent is reasonable and necessary |
| ERISA 408(c)(2) - Office space | Possibly | Specific exemption for office space rental |

**ERISA 408(c)(2) Requirements:**

For office space rental to parties-in-interest:
1. Office space must be necessary for plan operation
2. Rental must be for reasonable compensation
3. No commission to party-in-interest

**Evaluation:**

| Requirement | Analysis | Met? |
|-------------|----------|------|
| Necessary? | Plan has 45 participants; dedicated office space seems excessive | ❓ |
| Reasonable? | $50,000/year for "plan office" – need to compare to market rates | ❓ |
| No commission? | Direct payment to owner | ✓ |

### Further Investigation

**Q: How much space is rented for plan administration?**
A: About 500 square feet.

**Q: What is market rent in this area?**
A: Approximately $25-30 per square foot.

**Calculation:**
```
Space rented: 500 sq ft
Market rate: $25-30/sq ft
Expected rent: $12,500 - $15,000/year

Actual rent: $50,000/year
Rate paid: $100/sq ft

CONCLUSION: Rent significantly exceeds market rate
             Does not meet "reasonable compensation" requirement
             Prohibited transaction without exemption
```

### Resolution

**Correction Required:**

1. **Refund excess rent to plan:**
   ```
   Rent paid: $50,000
   Reasonable rent (est.): $15,000
   Excess: $35,000
   Plus lost earnings: $1,200 (estimated)
   Total refund to plan: $36,200
   ```

2. **Excise Tax:**
   - 15% of "amount involved" for each year
   - Amount involved = $50,000 (full rent, not just excess)
   - Year 1 excise tax: $7,500
   - File Form 5330

3. **Report on Schedule G:**
   - Part III: Nonexempt Transactions
   - Include all details

4. **Future Rent:**
   - Establish fair market rent through appraisal
   - Document necessity of space
   - Create proper lease agreement

### Audit Documentation

```
Finding: Prohibited Transaction - Office Space Rental

Condition: Plan paid $50,000 rent to Smith Properties LLC,
a company owned by the plan sponsor's owners.

Criteria: ERISA Section 406(a)(1)(C) prohibits furnishing of
goods/services between plan and party-in-interest unless
exemption applies. ERISA 408(c)(2) permits office space rental
at reasonable compensation.

Cause: Lack of understanding of prohibited transaction rules;
no independent review of related party transactions.

Effect: Prohibited transaction; 15% excise tax; correction
required; Schedule G disclosure.

Recommendation:
1. Refund excess rent ($35,000) plus earnings to plan
2. File Form 5330 and pay excise tax
3. Obtain appraisal for future rent
4. Implement related party transaction review procedures
```

### Key Takeaways

- Always scrutinize payments to related parties
- "Reasonable compensation" requires market rate analysis
- Even permitted transactions must meet exemption requirements
- Excise taxes apply to prohibited transactions
- Correction requires refund plus earnings

---

## Case Study 8: First-Year Audit Challenges

### Background

**Plan:** Startup Tech 401(k) Plan
**Participants:** 145 (current), 85 (at BOY)
**Plan Year:** December 31, 20XX (first audit year)
**Plan Established:** January 1, 20XX-2 (two years ago)
**Prior Years:** Never audited (small plan exemption)

### Unique Challenges

**1. No Prior Audit:**
- No audited opening balances
- No predecessor auditor workpapers

**2. Rapid Growth:**
- 85 participants at BOY → 145 at EOY
- Crossed 100-participant threshold during prior year

**3. Opening Balance Verification:**
- Must obtain sufficient evidence about opening balances
- Prior year Form 5500 available (small plan filing)

### Procedures Performed

**Opening Balance Verification:**

| Item | Procedure | Result |
|------|-----------|--------|
| Investments | Confirm with trustee | Agreed to 12/31/XX-1 trust statement |
| Participant accounts | Foot account balances | Agreed to trust statement |
| Contributions receivable | Trace to January deposits | $45,000 deposited January 5 – OK |
| Form 5500 reconciliation | Compare to prior 5500 | Agreed (no prior audit adjustments) |

**Historical Testing:**

Since opening balances were never audited, performed limited historical testing:

| Area | Historical Procedure |
|------|---------------------|
| Contributions | Tested sample from prior 2 years |
| Distributions | Tested sample from prior 2 years |
| Vesting | Verified years of service calculations from hire dates |
| Eligibility | Tested proper entry dates for sample of participants |

### Issues Discovered

**1. Prior Year Contribution Error**

Testing of 20XX-1 contributions revealed:
- One participant was excluded from plan for 3 months after becoming eligible
- Missed deferrals: $2,400
- Missed match: $1,200
- Total: $3,600

**2. Vesting Calculation Error**

Three terminated participants in prior year:
- Used incorrect vesting schedule (6-year instead of plan's 3-year cliff)
- Resulted in $8,500 in over-forfeitures

### Resolution

**Contribution Error:**
```
Corrective Contribution:
- Missed deferrals: $2,400
- Missed match: $1,200
- Lost earnings (2 years): $420
- Total corrective contribution: $4,020

Correction Method: Self-Correction Program (SCP)
```

**Vesting Error:**
```
Refund of Forfeitures:
- Participant A: $3,200 + $380 earnings = $3,580
- Participant B: $2,800 + $330 earnings = $3,130
- Participant C: $2,500 + $290 earnings = $2,790
- Total: $9,500

Note: Participants must be located and refunded
```

### Audit Report Considerations

**Question:** Can we issue an unmodified opinion on the current year given prior year findings?

**Analysis:**
- Errors are being corrected
- Opening balances have been verified
- Misstatements are being recorded as current year corrections
- No scope limitation exists

**Conclusion:** Unmodified opinion appropriate; disclose prior period adjustments in notes if material.

### Key Takeaways

- First-year audits require opening balance verification
- Consider historical testing for unaudited periods
- Document correction of prior period errors
- Self-Correction Program may apply to historical errors
- Prior year Form 5500 provides baseline for reconciliation

---

## Case Study 9: Employer in Financial Distress

### Background

**Plan:** Manufacturing Co. 401(k) Plan
**Participants:** 380
**Plan Year:** December 31, 20XX
**Situation:** Employer filed Chapter 11 bankruptcy in August 20XX

### Risk Factors

| Factor | Concern | Impact on Audit |
|--------|---------|-----------------|
| Bankruptcy filing | Going concern | Consider disclosure requirements |
| Cash flow issues | Contribution timing | Increased testing of remittances |
| Layoffs | Increased distributions | Test distribution processing |
| Management distraction | Control environment | Assess control risk |
| Vendor payments | Plan expenses | Verify proper payment |

### Procedures Performed

**1. Contribution Testing – Enhanced**

Expanded sample from 25 to 50 contribution remittances:

| Period | Days to Deposit | Issue? |
|--------|-----------------|--------|
| Jan-Jul | 3-5 days | No |
| Aug-Sep | 15-25 days | Yes – Late |
| Oct-Dec | 8-12 days | Yes – Some late |

**Finding:** After bankruptcy filing, contribution remittances deteriorated significantly.

**2. Going Concern Evaluation**

| Factor | Consideration |
|--------|---------------|
| Plan impact | Plan continues during reorganization |
| Asset protection | ERISA protects plan assets from creditors |
| Contribution obligations | DIP may continue employer contributions |
| Participant access | Participants can still take distributions |

**Conclusion:** Plan is not subject to going concern doubt; employer bankruptcy does not directly impact plan's ability to pay benefits from existing assets.

**3. Distribution Surge Testing**

Tested 45 distributions (vs. normal 25):
- Verified proper authorization
- Confirmed eligibility (termination, retirement, in-service)
- Verified calculations

**Finding:** 3 participants received distributions without proper termination documentation (later verified as actual terminations).

**4. Employer Contribution Verification**

| Contribution Type | Obligation | Status |
|-------------------|------------|--------|
| Match (current) | Required per plan | Suspended July 1 per amendment |
| Profit sharing | Discretionary | None declared |
| Safe harbor | N/A | Not a safe harbor plan |

**Finding:** Match suspension was properly communicated to participants via 30-day notice.

### Financial Statement Disclosures

Required disclosures for employer bankruptcy:

```
Note X: Plan Sponsor Bankruptcy

On August 15, 20XX, the Plan Sponsor, Manufacturing Co., filed
a voluntary petition for relief under Chapter 11 of the
United States Bankruptcy Code. The Plan Sponsor continues to
operate as a debtor-in-possession.

The Plan Sponsor suspended employer matching contributions
effective July 1, 20XX, following proper notification to
participants. The Plan Sponsor continued to remit participant
deferrals during the bankruptcy proceedings, although certain
remittances were delayed beyond the timeframes specified in
DOL regulations.

Plan assets are held in trust for the exclusive benefit of
participants and are protected from the claims of the Plan
Sponsor's creditors. The Plan Sponsor's bankruptcy filing
does not directly affect participants' ability to receive
benefits from their vested account balances.

As of the date of this report, the bankruptcy proceedings are
ongoing. The ultimate outcome of the bankruptcy case and its
effect on the Plan, if any, cannot be determined at this time.
```

### Key Takeaways

- Employer bankruptcy increases audit risk but doesn't directly impact plan
- ERISA protects plan assets from employer's creditors
- Watch for delayed contributions during financial distress
- Employer can suspend match with proper notice
- Disclosure required for significant employer events

---

## Case Study 10: Merger and Acquisition

### Background

**Situation:**
- Acquiring Company purchased Target Company on July 1, 20XX
- Target Company 401(k) Plan ($5M, 120 participants) merged into Acquiring Company 401(k) Plan ($25M, 400 participants)
- Merger effective October 1, 20XX

**Plan Being Audited:** Acquiring Company 401(k) Plan
**Plan Year:** December 31, 20XX

### Audit Considerations

**1. Pre-Merger Period (Jan 1 – Sep 30)**

For the acquired plan's pre-merger period:
- Obtain financial statements or trial balance from Target Plan
- Understand Target Plan provisions
- Identify any known issues

**2. Merger Date Testing (October 1)**

| Item | Procedure |
|------|-----------|
| Assets transferred | Agree to transfer documentation |
| Participant accounts | Reconcile accounts transferred |
| Investment mapping | Verify investment elections mapped correctly |
| Vesting | Verify service credit carried over |
| Loans | Verify loan balances transferred correctly |

**3. Post-Merger Period (Oct 1 – Dec 31)**

Normal audit procedures for the combined plan.

### Testing Performed

**Asset Transfer Verification:**

```
Target Plan Assets at 9/30/XX:        $5,247,893
Less: Distributions (9/30-10/1):       ($12,500)
Assets transferred (per trust):      $5,235,393
Per Acquiring Plan trust statement:  $5,235,393

RECONCILED ✓
```

**Participant Account Reconciliation (sample of 20):**

| Participant | Target Balance | Transferred Balance | Variance |
|-------------|---------------|---------------------|----------|
| A. Adams | $45,678 | $45,678 | $0 |
| B. Brown | $23,456 | $23,456 | $0 |
| ... | ... | ... | ... |
| T. Thomas | $67,890 | $67,890 | $0 |

**All sampled accounts reconciled without exception.**

**Investment Mapping:**

| Target Plan Fund | Acquiring Plan Fund | Mapping |
|-----------------|---------------------|---------|
| Target 2030 Fund | Vanguard Target 2030 | Automatic |
| Money Market | Stable Value | Participant choice required |
| Company Stock | No equivalent | Liquidated; participant chose new |

**Finding:** 15 participants did not make elections for unmapped investments; defaulted to QDIA per plan document.

**Vesting Credit:**

Verified service credit for Target employees:
- Prior service from Target employment recognized
- No breaks in service due to acquisition
- Sample of 10 employees' vesting verified

### Issues Discovered

**1. Loan Default:**

One participant loan from Target Plan was in default at merger:
```
Participant: Chris Wilson
Loan balance at merger: $8,500
Last payment: April 15, 20XX
Days since payment: 168 days (past cure period)

ISSUE: Loan should have been treated as deemed distribution
       prior to merger

RESOLUTION: Process deemed distribution; issue 1099-R
```

**2. Compliance Testing:**

Post-merger compliance testing must consider:
- Combined HCE/NHCE populations
- Prior year data from both plans
- Coverage testing for both groups

### Financial Statement Presentation

**Statement of Changes:**

```
Additions:
  ...
  Transfer of assets from Target Company
    401(k) Plan                              $5,235,393
  ...
```

**Note Disclosure:**

```
Note X: Plan Merger

Effective October 1, 20XX, the Target Company 401(k) Plan
(the "Target Plan") was merged into the Plan. Approximately
$5,235,000 in assets and 120 participant accounts were
transferred from the Target Plan to the Plan.

Prior to the merger, the Target Plan was sponsored by Target
Company, which was acquired by [Acquiring Company] on
July 1, 20XX. Following the merger, all former Target Plan
participants became participants in this Plan with full credit
for vesting and eligibility service.
```

### Key Takeaways

- Plan mergers require asset and account reconciliation
- Verify investment mapping and participant elections
- Recognize service credit from predecessor plan
- Watch for outstanding loans and compliance issues
- Disclose merger in financial statement notes

---

## Case Study 11: Self-Directed Brokerage Issues

### Background

**Plan:** Financial Services 401(k) Plan
**Participants:** 650
**Self-Directed Brokerage Accounts:** 85 participants, $12.5M
**Plan Year:** December 31, 20XX

### Audit Considerations

Self-directed brokerage accounts (SDBAs) create unique audit challenges:
- Wide variety of investment types
- Individual participant trading
- Complex valuations possible
- Prohibited transaction risk

### Testing Performed

**1. Brokerage Statement Reconciliation:**

| Item | Brokerage Statements | Plan Records | Variance |
|------|---------------------|--------------|----------|
| Beginning balance | $11,247,893 | $11,247,893 | $0 |
| Contributions | $1,856,000 | $1,856,000 | $0 |
| Distributions | ($723,000) | ($723,000) | $0 |
| Investment income | $412,500 | $412,500 | $0 |
| Net gains | $1,706,607 | $1,706,607 | $0 |
| Ending balance | $12,500,000 | $12,500,000 | $0 |

**2. Investment Type Analysis:**

| Investment Category | Value | % of SDBA |
|--------------------|-------|-----------|
| Equities (stocks) | $8,125,000 | 65% |
| Fixed Income | $1,875,000 | 15% |
| Mutual Funds | $1,250,000 | 10% |
| ETFs | $875,000 | 7% |
| Options | $250,000 | 2% |
| Other | $125,000 | 1% |

**3. Prohibited Investment Testing:**

Reviewed holdings for prohibited investments:

| Investment | Concern | Finding |
|------------|---------|---------|
| Employer stock | Allowed if plan permits | Verified - not held in SDBAs |
| Collectibles | Prohibited | None found |
| Life insurance | Prohibited (generally) | None found |
| S-Corp stock | Not prohibited | Found in 2 accounts |
| Real estate | Not prohibited but complex | None found |
| Cryptocurrency | Complex; emerging issue | See below |

**4. Cryptocurrency Discovery:**

```
Finding: One participant holds cryptocurrency in SDBA

Participant: John Tech
Holdings: Bitcoin ($15,000), Ethereum ($8,000)
Total crypto: $23,000

ISSUES:
1. DOL has issued warnings about crypto in 401(k)s
2. Valuation complexity
3. Plan document may not address

ANALYSIS:
- Plan document silent on cryptocurrency
- Brokerage allows crypto trading
- DOL Compliance Assistance Release 2022-01
  expresses concern but doesn't prohibit
```

### Valuation Considerations

**For SDBA Investments:**

| Investment Type | Valuation Approach | Level |
|----------------|--------------------| ------|
| Publicly traded stocks | Quoted prices | Level 1 |
| Bonds | Matrix pricing | Level 2 |
| Options | Pricing models | Level 2/3 |
| Cryptocurrency | Exchange prices | Level 1* |

*Crypto pricing on exchanges may qualify as Level 1 but with high volatility.

### Audit Documentation

```
SDBA Testing Summary:

Population: 85 accounts, $12,500,000
Sample: 15 accounts, $4,875,000

Procedures:
1. Reconciled brokerage statements to plan records
2. Tested investment valuations (agreed to quoted prices)
3. Reviewed holdings for prohibited investments
4. Evaluated unusual investments (crypto)

Findings:
- No exceptions in reconciliation
- No prohibited investments (collectibles, insurance)
- One participant holds cryptocurrency ($23,000)

Conclusion:
- SDBA balances fairly stated
- Recommend plan document clarification on cryptocurrency
- Consider communication to participants about crypto risks
```

### Recommendations to Plan Sponsor

```
1. CRYPTOCURRENCY POLICY
   Consider adopting explicit policy on cryptocurrency
   investments in SDBAs, either permitting with restrictions
   or prohibiting.

2. PARTICIPANT COMMUNICATION
   If crypto is permitted, provide education about:
   - Volatility risks
   - Regulatory uncertainty
   - Concentration risk

3. PLAN DOCUMENT REVIEW
   Review plan document and SDBA provisions to ensure
   all permitted investment types are clearly defined.

4. MONITORING
   Implement periodic review of SDBA holdings for
   prohibited investments or unusual concentrations.
```

### Key Takeaways

- SDBAs require reconciliation to brokerage statements
- Review for prohibited investments (collectibles, insurance)
- Cryptocurrency is an emerging issue requiring attention
- Plan document should address SDBA investment restrictions
- Consider concentration risk in individual accounts

---

## Case Study 12: Material Weakness Identification

### Background

**Plan:** Distribution Company 401(k) Plan
**Participants:** 525
**Plan Year:** December 31, 20XX
**Finding:** Multiple control deficiencies discovered

### Control Deficiencies Identified

| # | Deficiency | Area |
|---|------------|------|
| 1 | No reconciliation of payroll to contributions | Contributions |
| 2 | Single person approves and processes distributions | Distributions |
| 3 | No review of participant data changes | Data |
| 4 | Loans processed without documented approval | Loans |
| 5 | No monitoring of compliance test results | Compliance |

### Evaluation Process

**Step 1: Evaluate Each Deficiency Individually**

| Deficiency | Likelihood of Misstatement | Magnitude if Occurs |
|------------|---------------------------|---------------------|
| 1. No contribution reconciliation | Reasonably possible | Could be material |
| 2. No segregation - distributions | Reasonably possible | Could be material |
| 3. No data change review | More than remote | Likely less than material |
| 4. Loan approval missing | More than remote | Likely less than material |
| 5. No compliance monitoring | Remote | Could be material |

**Step 2: Evaluate Combinations**

Even if individual deficiencies are significant deficiencies, combinations may rise to material weakness.

```
COMBINATION ANALYSIS:

Deficiencies 1 + 2 together:
- Lack of reconciliation (contributions) +
- Lack of segregation (distributions)
= Overall control environment weakness affecting
  multiple transaction cycles

Combined likelihood: Reasonably possible
Combined magnitude: Material

CONCLUSION: Together, these deficiencies create a
reasonable possibility that a material misstatement
could occur and not be prevented or detected.

CLASSIFICATION: MATERIAL WEAKNESS
```

### Classification Summary

| Deficiency | Individual Classification | Combined |
|------------|--------------------------|----------|
| 1. Contribution reconciliation | Significant Deficiency | Material Weakness (combined with #2) |
| 2. Distribution segregation | Significant Deficiency | Material Weakness (combined with #1) |
| 3. Data change review | Significant Deficiency | Significant Deficiency |
| 4. Loan approval | Significant Deficiency | Significant Deficiency |
| 5. Compliance monitoring | Deficiency | Deficiency |

### Communication Requirements

**Material Weakness – Required Communications:**

1. **Written communication to management and those charged with governance**
   - Must be communicated before report release
   - Must be in writing

2. **Content of communication:**
   - Definition of material weakness
   - Description of deficiencies
   - Potential effects
   - Recommendations

**Sample Communication:**

```
To: Plan Administrator and Retirement Committee

RE: Material Weakness in Internal Control

In planning and performing our audit of the financial
statements of [Plan Name] for the year ended December 31,
20XX, we considered the Plan's internal control over financial
reporting as a basis for designing our audit procedures.
We identified the following material weakness:

MATERIAL WEAKNESS:

The Plan does not have adequate controls over the contribution
and distribution processes. Specifically:

1. No reconciliation is performed between participant
   deferrals per payroll records and contributions deposited
   to the Plan trust.

2. A single individual has the ability to both approve and
   process participant distributions without independent review.

These deficiencies, considered together, create a reasonable
possibility that a material misstatement of the Plan's
financial statements could occur and not be prevented or
detected on a timely basis.

POTENTIAL EFFECTS:

- Contribution errors may not be detected
- Unauthorized distributions could occur
- Material misstatement of plan assets and participant balances

RECOMMENDATIONS:

1. Implement monthly reconciliation of payroll deferrals to
   trust deposits, with supervisory review and sign-off.

2. Require independent approval for all distributions,
   with documented authorization before processing.

This communication is intended solely for the information
and use of management and those charged with governance
and is not intended to be and should not be used by
anyone other than these specified parties.

[Firm Name]
[Date]
```

### Impact on Audit Report

**Question:** Does a material weakness affect the audit opinion?

**Answer:** Not necessarily. The audit opinion addresses whether the financial statements are fairly presented. A material weakness indicates a control deficiency, not necessarily a financial statement error.

**However:**
- Material weakness may indicate increased risk
- May require expanded substantive testing
- If actual material misstatement found and not corrected, opinion would be modified

### Key Takeaways

- Evaluate deficiencies individually AND in combination
- Material weakness = reasonable possibility of material misstatement not being prevented/detected
- Written communication to governance is required
- Material weakness doesn't automatically affect opinion
- Provide specific recommendations for remediation

---

## Case Study 13: Mid-Year TPA Change with Partial Certification

### Background

**Plan:** Regional Services 401(k) Plan
**Participants:** 285
**Plan Year:** December 31, 20XX
**Audit Type:** Initially Limited Scope
**Situation:** TPA changed mid-year; certification only available for partial year

### Facts Discovered

The plan sponsor changed Third Party Administrators (TPAs) during the plan year:

| Period | TPA | Certification Status |
|--------|-----|---------------------|
| January 1 – September 30 | ABC Retirement Services | Valid certification provided |
| October 1 – December 31 | XYZ Benefits Administration | No certification available |

**Reason for Change:** The sponsor switched TPAs due to service quality issues and better pricing from the new provider.

### The Problem

**Former TPA (ABC Retirement Services):**
- Provided proper ERISA Section 103(a)(3)(C) certification
- Certification covers January 1 – September 30, 20XX only
- Certified by qualifying bank trustee (First National Bank)
- Investment information: $18,450,000 as of 9/30/XX

**New TPA (XYZ Benefits Administration):**
- Uses a different custodian (Regional Trust Company)
- Regional Trust Company is willing to provide certification
- However, they only have records from October 1 forward
- Cannot certify the full plan year
- Investment information: $19,875,000 as of 12/31/XX

### Analysis

**Question:** Can we perform a limited scope audit with two partial-year certifications?

**Answer:** No. ERISA Section 103(a)(3)(C) requires certification covering the **entire plan year**. Two partial certifications do not satisfy this requirement.

**Options Available:**

| Option | Description | Audit Impact |
|--------|-------------|--------------|
| **Option A** | Full scope audit for entire year | Test all investments for 12 months |
| **Option B** | Hybrid approach | Limited scope for certified period; full scope for uncertified period |
| **Option C** | Delay audit | Wait for combined certification (not possible with different custodians) |

**Recommended Approach: Option B – Hybrid Audit**

This is the most practical and cost-effective approach when:
- One period has valid certification from a qualifying institution
- The uncertified period is relatively short (3 months)
- Testing the uncertified period is feasible

### Hybrid Audit Procedures

**For Certified Period (January 1 – September 30):**

| Procedure | Scope |
|-----------|-------|
| Investment existence | Rely on certification |
| Investment valuation | Rely on certification |
| Investment transactions | Rely on certification |
| Compare certification to records | Required |

**For Uncertified Period (October 1 – December 31):**

| Procedure | Scope |
|-----------|-------|
| Investment existence | Confirm with custodian |
| Investment valuation | Verify fair values at 12/31 |
| Investment transactions | Test purchases, sales, income |
| Reconcile to certified balances | Required |

### Detailed Testing for Uncertified Period

**1. Beginning Balance Verification (October 1)**

```
Per ABC certification (9/30/XX):     $18,450,000
Per XYZ records (10/1/XX):           $18,450,000
Difference:                          $0

RECONCILED ✓
```

**2. Investment Existence Testing**

Confirmed all investment positions with Regional Trust Company as of 12/31/XX:

| Investment Type | Quantity | Value per Statement | Confirmed |
|-----------------|----------|---------------------|-----------|
| Vanguard 500 Index | 45,678 shares | $8,234,567 | ✓ |
| Bond Fund | 123,456 shares | $4,567,890 | ✓ |
| Target Date Funds | Various | $5,123,456 | ✓ |
| Stable Value | N/A | $1,949,087 | ✓ |
| **Total** | | **$19,875,000** | ✓ |

**3. Investment Valuation Testing**

For each investment, verified fair value as of 12/31/XX:

| Investment | Plan Value | Quoted Price/NAV | Source | Variance |
|------------|------------|------------------|--------|----------|
| Vanguard 500 | $8,234,567 | $180.25/share | Vanguard | $0 |
| Bond Fund | $4,567,890 | $37.00/share | Provider | $0 |
| Target Funds | $5,123,456 | Various | Provider | $0 |
| Stable Value | $1,949,087 | Contract value | Contract | $0 |

**4. Investment Transaction Testing (Q4)**

Tested sample of 25 transactions during October – December:

| Transaction Type | Count Tested | Exceptions |
|------------------|--------------|------------|
| Participant contributions | 10 | None |
| Investment purchases | 5 | None |
| Benefit payments | 5 | None |
| Investment sales | 3 | None |
| Dividend reinvestments | 2 | None |

### Financial Statement Presentation

No special presentation is required in the financial statements. The statements present year-end balances and annual activity regardless of the audit approach.

### Audit Report – Modified for Hybrid Approach

```
              INDEPENDENT AUDITOR'S REPORT

To the Plan Administrator and Plan Participants
Regional Services 401(k) Plan

Scope and Nature of the Audit

We have audited the financial statements of the Regional Services
401(k) Plan (the "Plan"), which comprise the statements of net
assets available for benefits as of December 31, 20XX and 20XX-1,
and the related statements of changes in net assets available for
benefits for the years then ended, and the related notes to the
financial statements.

ERISA-Permitted Limited Scope Audit – Partial Year

As permitted by 29 CFR 2520.103-8 of the Department of Labor's
Rules and Regulations for Reporting and Disclosure under ERISA,
and as elected by the plan administrator, we were instructed not
to perform, and we did not perform, any auditing procedures with
respect to the certified investment information for the period
January 1, 20XX through September 30, 20XX, which was certified
by First National Bank, the custodian of the Plan during that
period. We were informed that the custodian is a bank regulated
by a federal agency and that the certification required by
29 CFR 2520.103-8 has been received for this period.

Full Scope Audit Procedures – Partial Year

Due to a change in plan service providers during the year, no
certification meeting the requirements of 29 CFR 2520.103-8 was
available for the period October 1, 20XX through December 31, 20XX.
Accordingly, we performed full scope auditing procedures with
respect to the investment information for this period, including
confirming investments held with the custodian and verifying fair
values as of December 31, 20XX.

[Standard sections continue...]

Emphasis of Matter – Change in Service Providers

As discussed in Note X to the financial statements, the Plan
changed its third-party administrator and custodian effective
October 1, 20XX. Our opinion is not modified with respect to
this matter.

[Opinion section – unmodified opinion appropriate if no exceptions]
```

### Note Disclosure

```
Note X: Change in Service Providers

Effective October 1, 20XX, the Plan changed its third-party
administrator from ABC Retirement Services to XYZ Benefits
Administration. Concurrently, plan assets were transferred from
First National Bank to Regional Trust Company.

Total assets transferred on October 1, 20XX: $18,450,000

Due to the mid-year service provider change, the independent
auditor performed limited scope audit procedures for the period
January 1 through September 30, 20XX, relying on the certification
provided by First National Bank, and full scope audit procedures
for the period October 1 through December 31, 20XX.
```

### Audit Documentation

```
Finding: Mid-Year TPA Change Requiring Hybrid Audit Approach

Situation: The Plan changed third-party administrators and
custodians effective October 1, 20XX. The former custodian
(First National Bank) provided a valid ERISA 103(a)(3)(C)
certification for January 1 – September 30. The new custodian
(Regional Trust Company) could not provide a certification
covering the full plan year.

Resolution: Performed hybrid audit:
- Limited scope procedures for January 1 – September 30 (9 months)
  relying on First National Bank certification
- Full scope investment procedures for October 1 – December 31
  (3 months) including existence confirmation and valuation testing

Result: No exceptions noted. Investment balances properly
reconciled between custodians. Report includes Emphasis of
Matter paragraph regarding service provider change.

Additional Testing Performed:
- Confirmed $18,450,000 transfer between custodians
- Tested 25 investment transactions during Q4
- Verified all 12/31/XX investment valuations
- Reconciled participant accounts across TPA transition
```

### Key Takeaways

- Two partial-year certifications do NOT satisfy ERISA 103(a)(3)(C)
- Hybrid approach allows limited scope for certified period
- Full investment testing required for uncertified period
- Report should include Emphasis of Matter for service provider change
- Document reconciliation of assets transferred between custodians
- Financial statement notes should disclose the situation

---

## Case Study 14: Amended Adoption Agreement Without Determination Letter

### Background

**Plan:** Professional Services 401(k) Plan
**Participants:** 175
**Plan Year:** December 31, 20XX
**Plan Document Type:** Volume Submitter / Pre-approved Plan
**Situation:** Adoption agreement amended during year; no new Determination Letter obtained

### Facts Discovered

During review of plan documents, you discover:

**Original Plan:**
- Established: January 1, 20XX-5
- Last IRS Determination Letter: March 15, 20XX-4
- Document Type: Volume Submitter (pre-approved)

**Amendment:**
- Amendment Date: July 1, 20XX
- Amendment Number: 2020-1
- Signed by: Plan Sponsor CEO

**Amendment Content:**

```
Amendment 2020-1 to the Professional Services 401(k) Plan

Effective July 1, 20XX, the Plan is amended as follows:

1. Section 4.1(b) is amended to change the employer matching
   contribution formula from:

   "50% of the first 6% of compensation deferred"

   to:

   "100% of the first 4% of compensation deferred"

2. Section 5.3 is amended to change the vesting schedule for
   employer contributions from:

   "6-year graded vesting"

   to:

   "3-year cliff vesting"

All other provisions of the Plan remain unchanged.
```

### The Question

**Plan Administrator's Concern:**
> "Our attorney said we should get a new Determination Letter from the IRS, but we haven't done that yet. Does this affect the audit?"

### Analysis Framework

**When is a new Determination Letter required?**

| Situation | Determination Letter Required? |
|-----------|-------------------------------|
| Discretionary amendment to pre-approved plan | Generally NO |
| Changing to a different pre-approved plan | Generally NO |
| Significant customization outside plan boundaries | YES |
| Individually designed plan amendments | Recommended |
| Response to IRS examination | Depends on findings |

**Evaluating This Amendment:**

| Change | Significance | Within Pre-Approved Terms? |
|--------|--------------|---------------------------|
| Match formula (50%/6% → 100%/4%) | Common provision | YES – typical elective choice |
| Vesting (6-year graded → 3-year cliff) | Common provision | YES – IRS-permitted schedule |

### IRS Determination Letter Program Background

**Key Points:**

1. **Pre-approved plans** (prototype and volume submitter) receive Opinion Letters or Advisory Letters that cover the plan document
2. **Adopting employers** may rely on the plan's Opinion/Advisory Letter
3. **Discretionary amendments** using options already in the pre-approved document do not require a new Determination Letter
4. **Significant modifications** outside the plan's pre-approved language may require individual Determination Letter

### Auditor's Evaluation

**Step 1: Review the Amendment**

```
Amendment Analysis:

Change 1: Matching Formula
- Old: 50% of first 6%
- New: 100% of first 4%
- Question: Is this a standard adoption agreement choice?
- Answer: YES – Both are typical match formulas within
          pre-approved plan options

Change 2: Vesting Schedule
- Old: 6-year graded
- New: 3-year cliff
- Question: Is this a permitted vesting schedule?
- Answer: YES – 3-year cliff meets IRC 411(a)(2)(A) minimum
          and is a standard adoption agreement option

CONCLUSION: Both changes are discretionary amendments using
options within the pre-approved plan document. No new
Determination Letter is required.
```

**Step 2: Verify Plan Qualification**

Even without a new Determination Letter, verify:

| Item | Procedure | Result |
|------|-----------|--------|
| Amendment properly adopted | Review board resolution | ✓ Approved 6/15/XX |
| Amendment within plan authority | Compare to Volume Submitter | ✓ Options permitted |
| Effective date reasonable | Check for anti-cutback issues | ✓ Prospective only |
| Participant notice provided | Review SMM distribution | ✓ Sent 6/20/XX |
| Vesting change properly handled | Check 411(d)(6) compliance | ✓ See below |

**Step 3: Anti-Cutback Analysis (IRC 411(d)(6))**

The vesting schedule change requires analysis:

```
IRC 411(d)(6) Anti-Cutback Rule:

Question: Does changing from 6-year graded to 3-year cliff
violate anti-cutback rules?

Analysis:
- New schedule (3-year cliff) is MORE generous than old
  (6-year graded) for most participants
- However, some participants may have higher vesting under
  old schedule (e.g., 4 years of service = 60% under graded,
  0% under cliff)

Requirement: Participants must receive the GREATER of:
- Vesting under old schedule (for pre-amendment service)
- Vesting under new schedule

Documentation Check:
- Amendment states new schedule is prospective
- Plan records show "protected" vesting percentages
- Tested 10 participants with 1-5 years of service:
  All show higher of two schedules applied

RESULT: 411(d)(6) properly applied ✓
```

### Resolution

**Determination Letter Not Required**

Based on our analysis:

1. Both amendments are discretionary changes using pre-approved plan options
2. The Volume Submitter Opinion Letter remains valid
3. No individual Determination Letter is required
4. No financial statement disclosure is necessary regarding the lack of Determination Letter

**Documentation Required**

Include in management representation letter:

```
Management Representations - Plan Qualification:

We represent that:

(a) The Plan is intended to qualify under IRC Section 401(a)
    and the related trust is intended to be exempt under
    IRC Section 501(a).

(b) The Plan is operated in accordance with a pre-approved
    volume submitter plan document for which a favorable
    IRS Opinion Letter has been issued to the plan sponsor.

(c) Amendment 2020-1, effective July 1, 20XX, was adopted
    pursuant to discretionary provisions within the pre-approved
    plan document and does not require an individual
    Determination Letter from the IRS.

(d) The amendment was properly adopted by the Plan Sponsor
    with appropriate board authorization.

(e) The vesting schedule change complies with IRC Section
    411(d)(6), with affected participants receiving the greater
    of their vested percentage under the prior or new schedule.

(f) Participants were notified of the amendment through a
    Summary of Material Modifications distributed on June 20, 20XX.
```

### When WOULD a Determination Letter Be Required?

For comparison, here are amendments that WOULD require action:

| Amendment Type | Determination Letter? | Alternative |
|----------------|----------------------|-------------|
| Change plan type (e.g., add cash balance) | YES | Or adopt new pre-approved document |
| Add ESOP features | YES | Specialized plan |
| Significant customization of provisions | YES | Individual DL application |
| Correct qualification failure | DEPENDS | May use VCP instead |
| Convert from pre-approved to individually designed | YES | Required for ongoing reliance |

### Financial Statement Impact

**Disclosure Required?** NO

Since the amendment:
- Was properly adopted
- Falls within pre-approved plan options
- Does not affect the plan's tax-qualified status
- Does not create uncertainty about qualification

No disclosure regarding the Determination Letter is necessary.

**Note Disclosure for Amendment (Required):**

```
Note X: Plan Amendments

Effective July 1, 20XX, the Plan was amended to:

1. Change the employer matching contribution formula from
   50% of the first 6% of participant deferrals to 100%
   of the first 4% of participant deferrals.

2. Change the vesting schedule for employer contributions
   from a 6-year graded schedule to a 3-year cliff schedule.

Participants with service prior to July 1, 20XX, are entitled
to the greater vested percentage under either the prior or
new vesting schedule.
```

### Audit Documentation

```
Plan Document Review - Amendment Analysis

Document: Amendment 2020-1
Effective Date: July 1, 20XX
Board Resolution: June 15, 20XX

Changes Made:
1. Matching formula: 50%/6% → 100%/4%
2. Vesting schedule: 6-year graded → 3-year cliff

Analysis:
- Both changes are discretionary options within the Volume
  Submitter pre-approved plan document
- Changes do not require modification of language beyond
  standard adoption agreement elections
- Volume Submitter Opinion Letter remains valid
- Individual IRS Determination Letter is NOT required

Anti-Cutback Compliance:
- Tested 10 participants with 1-5 years of service
- All participant accounts reflect greater of prior or
  new vesting percentage
- IRC 411(d)(6) requirements satisfied

Participant Notification:
- SMM distributed June 20, 20XX (verified)
- Distribution list retained in plan records

Conclusion:
- Amendment properly adopted and documented
- No Determination Letter required for pre-approved plan options
- Management representations obtained regarding qualification
- No financial statement disclosure required for DL status
- Standard amendment disclosure included in notes
```

### Key Takeaways

- Not all amendments require a new IRS Determination Letter
- Pre-approved plan (Volume Submitter/Prototype) discretionary amendments generally do not require individual Determination Letters
- Evaluate whether amendments fall within pre-approved plan options
- Always check anti-cutback (411(d)(6)) compliance for vesting changes
- Obtain management representations regarding plan qualification
- Document your analysis of whether Determination Letter is needed
- Standard plan amendment disclosures in notes are still required

### When to Recommend a Determination Letter

Advise clients to seek a Determination Letter when:

1. Converting from pre-approved to individually designed plan
2. Making significant modifications outside pre-approved options
3. Plan has never had a Determination Letter
4. Concerns about plan qualification
5. Major corporate transactions (merger, acquisition, spin-off)
6. In connection with plan termination

---

## Summary: Common Themes Across Case Studies

| Theme | Case Studies | Key Lesson |
|-------|--------------|------------|
| Documentation | 1, 5, 7, 14 | Proper documentation prevents findings |
| Timeliness | 1, 3, 6 | Meet all deadlines |
| Controls | 4, 12 | Strong controls prevent errors |
| Related parties | 7 | Extra scrutiny required |
| Compliance | 3, 4, 5, 14 | Know the rules |
| Communication | 8, 9, 10, 13 | Transparency is essential |
| Correction | All | Most issues can be corrected |
| Service provider changes | 10, 13 | Plan transitions require careful handling |
| Plan documents | 2, 14 | Verify certifications and amendments |

---

## Document History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2024 | Initial release with 12 case studies |
| 1.1 | 2025 | Added Case Study 13 (Mid-Year TPA Change with Partial Certification) and Case Study 14 (Amended Adoption Agreement Without Determination Letter) |

---

*These case studies are based on common audit scenarios and are provided for educational purposes. Specific facts and circumstances may require different approaches. Always consult professional standards and firm guidance.*
