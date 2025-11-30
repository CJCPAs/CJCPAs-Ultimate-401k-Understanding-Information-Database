# 401(k) Discrimination Testing

## Overview

Discrimination testing ensures that 401(k) plans provide benefits fairly to all employees, not just highly compensated employees (HCEs). These tests are required under the Internal Revenue Code to maintain the plan's tax-qualified status. This comprehensive guide covers all aspects of discrimination testing, from basic concepts to complex correction strategies.

## Table of Contents

1. [Testing Fundamentals](#testing-fundamentals)
2. [Highly Compensated Employee (HCE) Determination](#highly-compensated-employee-hce-determination)
3. [Actual Deferral Percentage (ADP) Test](#actual-deferral-percentage-adp-test)
4. [Actual Contribution Percentage (ACP) Test](#actual-contribution-percentage-acp-test)
5. [Top-Heavy Testing](#top-heavy-testing)
6. [Coverage Testing (IRC Section 410(b))](#coverage-testing-irc-section-410b)
7. [General Nondiscrimination Testing (IRC Section 401(a)(4))](#general-nondiscrimination-testing-irc-section-401a4)
8. [Safe Harbor Alternatives](#safe-harbor-alternatives)
9. [Testing Corrections](#testing-corrections)
10. [Testing Best Practices](#testing-best-practices)

---

## Testing Fundamentals

### Purpose of Discrimination Testing

The fundamental purpose is to ensure that:
- Tax-advantaged benefits are broadly shared
- HCEs don't receive disproportionate benefits
- Plans serve the interests of all employees
- The plan maintains qualified status

### Key Testing Concepts

| Concept | Definition |
|---------|------------|
| HCE | Highly Compensated Employee - those with compensation above threshold or 5%+ owners |
| NHCE | Non-Highly Compensated Employee - everyone else |
| Key Employee | For top-heavy testing - officers, owners meeting specific thresholds |
| Excludable Employee | Employees who may be excluded from testing |
| Compensation | Plan-defined pay used for testing purposes |

### Testing Categories

| Test | Purpose | IRC Section |
|------|---------|-------------|
| ADP | Tests employee deferrals | 401(k)(3) |
| ACP | Tests matching and after-tax | 401(m)(2) |
| Top-Heavy | Tests asset concentration | 416 |
| Coverage | Tests participation breadth | 410(b) |
| General Nondiscrimination | Tests contribution/benefit fairness | 401(a)(4) |
| Annual Addition | Tests contribution limits | 415 |

### Testing Timeline

| Test | Determination Date | Correction Deadline |
|------|-------------------|---------------------|
| ADP/ACP | Plan year end | 2.5 months (QNEC) / 12 months |
| Top-Heavy | Prior plan year end | Following plan year |
| Coverage | Each day of plan year | Plan year end |

---

## Highly Compensated Employee (HCE) Determination

### HCE Definition

An employee is an HCE for the current plan year if during the current or preceding plan year they:

**5% Owner Test:**
- Own more than 5% of the employer
- Attribution rules apply (family, partnerships, etc.)
- Includes direct and indirect ownership

**Compensation Test:**
- Received compensation exceeding $155,000 (2024) in the prior year
- Optional: Limited to top 20% by compensation (top-paid group election)

### Determination Timeline

```
HCE Status for 2024 Testing:
- Based on 2023 compensation and 2023/2024 ownership
- Compensation threshold: >$155,000 in 2023
- 5% owner: At any time in 2023 or 2024
```

### HCE Compensation Thresholds (Historical)

| Year | Threshold |
|------|-----------|
| 2024 | $155,000 |
| 2023 | $150,000 |
| 2022 | $135,000 |
| 2021 | $130,000 |
| 2020 | $130,000 |

### Top-Paid Group Election

Plan may elect to limit HCEs to the top 20% by compensation:

| Benefit | Consideration |
|---------|---------------|
| Fewer HCEs | May improve test results |
| More NHCEs | Increases NHCE denominator |
| Consistency | Must apply consistently |
| Documentation | Election must be documented |

### Example HCE Determination

```
Employee Analysis for 2024 Testing:

John Smith:
- 2023 Compensation: $160,000 ✓ (exceeds $155,000)
- Ownership: 0%
- HCE Status: YES (compensation)

Mary Johnson:
- 2023 Compensation: $120,000
- Ownership: 8% ✓ (exceeds 5%)
- HCE Status: YES (ownership)

Robert Williams:
- 2023 Compensation: $145,000 (below threshold)
- Ownership: 2% (below 5%)
- HCE Status: NO (NHCE)
```

### Family Attribution Rules

Ownership is attributed among family members:

| Relationship | Attribution |
|--------------|-------------|
| Spouse | Full attribution |
| Children | Full attribution |
| Grandchildren | Full attribution |
| Parents | Full attribution (if 50%+ owner) |
| Siblings | No attribution |

---

## Actual Deferral Percentage (ADP) Test

### What is Tested

The ADP test compares the average deferral rates of HCEs to NHCEs:

| Included | Excluded |
|----------|----------|
| Pre-tax elective deferrals | Catch-up contributions |
| Roth deferrals | QNECs (unless used) |
| Deemed 401(k) contributions | QMACs (unless used) |

### Calculating Individual ADP

For each eligible employee:

```
ADP = Eligible Deferrals / Plan Compensation × 100

Example:
Employee's deferrals: $10,000
Plan compensation: $100,000
Individual ADP: $10,000 / $100,000 = 10%
```

### Calculating Group ADP

Average the individual ADPs:

```
HCE Group ADP = Sum of HCE Individual ADPs / Number of HCEs
NHCE Group ADP = Sum of NHCE Individual ADPs / Number of NHCEs
```

### ADP Test Limits

The HCE ADP cannot exceed:

| If NHCE ADP is: | HCE ADP cannot exceed: |
|-----------------|------------------------|
| 0% - 2% | 2 × NHCE ADP |
| 2% - 8% | NHCE ADP + 2% |
| Over 8% | 1.25 × NHCE ADP |

### ADP Test Example

```
Plan Year 2024 ADP Test:

NHCE Group (85 employees):
- Total compensation: $4,250,000
- Total deferrals: $153,000
- Average individual ADP: 3.60%

HCE Group (15 employees):
- Total compensation: $2,625,000
- Total deferrals: $157,500
- Average individual ADP: 6.00%

Test Application:
- NHCE ADP: 3.60%
- Maximum HCE ADP: 3.60% + 2% = 5.60%
- Actual HCE ADP: 6.00%

RESULT: FAIL
Excess: 6.00% - 5.60% = 0.40%
```

### Prior Year vs Current Year Testing

| Method | Description | Advantage |
|--------|-------------|-----------|
| Prior Year | Uses last year's NHCE ADP | Predictability |
| Current Year | Uses current year's NHCE ADP | Better matching |

Election requirements:
- Choose method in plan document
- Apply consistently
- Can switch from prior to current year
- Cannot switch from current to prior year (generally)

### ADP Special Rules

#### Disaggregation

Must disaggregate testing for:
- Otherwise excludable employees
- Employees under different allocation formulas

#### Early Participation

Plans may have special rules for:
- Employees with less than 2 years of eligibility service
- May test separately
- NHCE ADP cannot exceed HCE ADP

#### ESOP Rules

401(k) plans with ESOP components:
- May have special testing provisions
- Dividends may be treated specially

---

## Actual Contribution Percentage (ACP) Test

### What is Tested

The ACP test covers:

| Included | Excluded |
|----------|----------|
| Matching contributions | Non-matching employer contributions |
| Employee after-tax contributions | Forfeitures (unless allocated as match) |
| Allocated forfeitures (if used for match) | QNECs (unless used) |

### Calculating Individual ACP

```
ACP = (Matching + After-Tax) / Plan Compensation × 100

Example:
Employee's match received: $3,000
Employee's after-tax: $2,000
Plan compensation: $100,000
Individual ACP: ($3,000 + $2,000) / $100,000 = 5%
```

### ACP Test Limits

Same structure as ADP:

| If NHCE ACP is: | HCE ACP cannot exceed: |
|-----------------|------------------------|
| 0% - 2% | 2 × NHCE ACP |
| 2% - 8% | NHCE ACP + 2% |
| Over 8% | 1.25 × NHCE ACP |

### Aggregate Limit Test

When both ADP and ACP tests are run:

```
If HCE ADP and HCE ACP each individually pass, must also satisfy:
(HCE ADP + HCE ACP) ≤ Aggregate Limit

Aggregate Limit = Greater of:
- (NHCE ADP + NHCE ACP) × 2 + 2%
- (NHCE ADP × 2) + (NHCE ACP + 2%)
- (NHCE ADP + 2%) + (NHCE ACP × 2)
```

### ACP Test Example

```
Plan Year 2024 ACP Test:

NHCE Group (85 employees):
- Average individual ACP: 2.50%

HCE Group (15 employees):
- Average individual ACP: 4.80%

Test Application:
- NHCE ACP: 2.50%
- Maximum HCE ACP: 2.50% + 2% = 4.50%
- Actual HCE ACP: 4.80%

RESULT: FAIL
Excess: 4.80% - 4.50% = 0.30%
```

### Matching Contribution Formulas

| Match Type | Testing Treatment |
|------------|-------------------|
| Basic match | Included in ACP |
| Enhanced match | Included in ACP |
| Discretionary match | Included in ACP |
| True-up match | Included in ACP |
| Safe harbor match | May be excluded from ACP |

---

## Top-Heavy Testing

### Purpose

Top-heavy testing ensures that key employees don't hold a disproportionate share of plan assets.

### Key Employee Definition

An employee is a Key Employee if, at any time during the plan year:

| Category | Threshold |
|----------|-----------|
| Officer | Compensation > $220,000 (2024) |
| 5% owner | More than 5% ownership |
| 1% owner | More than 1% ownership AND compensation > $150,000 |

### Top-Heavy Determination

A plan is top-heavy if:

```
Key Employee Account Balances / Total Account Balances > 60%

Determination Date: Last day of preceding plan year
```

### Account Balances Included

| Included | Adjustments |
|----------|-------------|
| Current account balances | Add distributions in past 5 years |
| Former key employees | Include if key in past 5 years |
| Beneficiary accounts | Include beneficiaries of key employees |
| Rollovers | Include rollover contributions |

### Top-Heavy Consequences

If plan is top-heavy:

| Requirement | Description |
|-------------|-------------|
| Minimum contribution | 3% of compensation for non-key employees |
| Accelerated vesting | 3-year cliff or 6-year graded |
| Reduced compensation limit | $345,000 (2024) |

### Top-Heavy Minimum Contribution

```
Minimum Contribution = 3% × Compensation
(or highest key employee contribution rate if less than 3%)

Example:
Non-key employee compensation: $60,000
Top-heavy minimum: $60,000 × 3% = $1,800
```

### Top-Heavy Example

```
Plan Year 2024 Top-Heavy Test:

Key Employees (5):
- Total account balances: $2,500,000

Non-Key Employees (95):
- Total account balances: $3,500,000

Total Plan Assets: $6,000,000
Key Employee Ratio: $2,500,000 / $6,000,000 = 41.67%

RESULT: NOT TOP-HEAVY (41.67% ≤ 60%)
```

### Top-Heavy Exemptions

Plans may be exempt if:
- Safe harbor contributions meet minimum
- Plan is part of required aggregation group that is not top-heavy
- All accrued benefits are fully vested

---

## Coverage Testing (IRC Section 410(b))

### Purpose

Coverage testing ensures the plan covers a sufficient percentage of employees.

### Ratio Percentage Test

Most common coverage test:

```
Ratio = (% of NHCEs benefiting) / (% of HCEs benefiting)

Must be at least 70%
```

### Example Ratio Percentage Test

```
Total NHCEs: 100
NHCEs benefiting: 85
NHCE percentage: 85%

Total HCEs: 20
HCEs benefiting: 20
HCE percentage: 100%

Ratio: 85% / 100% = 85%

RESULT: PASS (85% ≥ 70%)
```

### Average Benefit Test

Alternative if ratio percentage fails:

1. **Nondiscriminatory classification test** - Classification must be reasonable and established under objective business criteria

2. **Average benefit percentage test** - Average benefit percentage for NHCEs must be at least 70% of average for HCEs

### Excludable Employees

May exclude from testing:

| Category | Requirement |
|----------|-------------|
| Age/service | Haven't met minimum requirements |
| Union employees | If benefits bargained for separately |
| Nonresident aliens | With no U.S. source income |
| Separate lines of business | If properly established |

### Benefits, Rights, and Features

Each benefit, right, or feature must satisfy coverage:

| Feature | Coverage Required |
|---------|-------------------|
| Loans | Available to NHCEs on nondiscriminatory basis |
| Hardship withdrawals | Available to NHCEs on nondiscriminatory basis |
| In-service distributions | Available to NHCEs on nondiscriminatory basis |
| Investment options | Available to all participants |

---

## General Nondiscrimination Testing (IRC Section 401(a)(4))

### Overview

Plans must not discriminate in favor of HCEs in:
- Contributions
- Benefits
- Rights and features
- Amendment patterns

### Design-Based Safe Harbors

Plans that meet design-based safe harbors automatically satisfy:

#### Uniform Allocation Formula

```
Same percentage of compensation for all eligible participants

Example: 3% of compensation for all participants
```

#### Uniform Points Allocation

Points-based allocation that doesn't discriminate:

| Factor | Points |
|--------|--------|
| Age | Per year |
| Service | Per year |
| Both combined | Must be uniform |

### General Test

If safe harbors don't apply:

1. Determine allocation rates for each employee
2. Group employees into rate groups
3. Test each rate group for coverage
4. Must satisfy coverage for each rate group

### Cross-Testing

Converts contributions to equivalent benefit accruals:

- Used for new comparability plans
- Allows different allocation rates if equivalent benefits
- Complex calculations required
- Must satisfy minimum gateway

---

## Safe Harbor Alternatives

### Safe Harbor 401(k) Plans

Exempt from ADP/ACP testing with:

| Type | Contribution |
|------|--------------|
| Basic match | 100% on first 3% + 50% on next 2% (4% max) |
| Enhanced match | At least as generous as basic |
| Non-elective | 3% to all eligible employees |
| QACA match | 100% on first 1% + 50% on next 5% (3.5% max) |

### Safe Harbor Requirements

| Requirement | Description |
|-------------|-------------|
| Vesting | 100% immediate (2-year cliff for QACA) |
| Notice | 30-90 days before plan year |
| Consistency | Generally cannot reduce mid-year |
| Eligibility | Same as deferrals |

### QACA Safe Harbor

Qualified Automatic Contribution Arrangement:

| Feature | Requirement |
|---------|-------------|
| Auto-enrollment | 3% minimum default rate |
| Escalation | Up to 10% (6% minimum for testing exemption) |
| Vesting | 2-year cliff vesting permitted |
| Match | Reduced match formula permitted |

### Safe Harbor Notice Requirements

Must provide to each eligible employee:

| Content | Description |
|---------|-------------|
| Safe harbor contribution | Type and amount |
| Other contributions | Any additional employer contributions |
| Vesting | Vesting schedule |
| Withdrawal restrictions | Limitations on distributions |
| Contact information | How to get more information |

---

## Testing Corrections

### ADP/ACP Failure Corrections

#### Corrective Distributions

Distribute excess contributions to HCEs:

| Deadline | Consequence |
|----------|-------------|
| 2.5 months after plan year | No excise tax |
| 12 months after plan year | 10% excise tax on employer |
| After 12 months | Plan disqualification risk |

#### Leveling Method

```
Step 1: Identify HCE with highest ADP
Step 2: Reduce that HCE's ADP to next highest HCE
Step 3: Test again
Step 4: If still failing, repeat
Step 5: Continue until test passes
```

#### Dollar Leveling Method

```
Step 1: Identify HCE with highest dollar amount
Step 2: Reduce to next highest dollar amount
Step 3: Retest
Step 4: Continue until test passes
```

#### Gap Period Earnings

Corrective distributions must include:
- Earnings through distribution date
- Gap period = plan year end to distribution date

### QNEC/QMAC Corrections

Make additional contributions to NHCEs:

| Type | Purpose |
|------|---------|
| QNEC | Increases NHCE ADP |
| QMAC | Increases NHCE ACP |

Requirements:
- 100% immediately vested
- Subject to distribution restrictions
- Must be deposited by correction deadline

### Recharacterization

Recharacterize HCE deferrals as after-tax:
- Rare correction method
- Complex tax implications
- Must be permitted by plan

### Top-Heavy Corrections

If minimum contribution not made:
- Make contribution by tax filing deadline (with extensions)
- Correct under EPCRS if late

### Coverage Corrections

Options include:
- Expand eligibility
- Make QNEC to excluded NHCEs
- Amend plan retroactively (limited)
- EPCRS correction

---

## Testing Best Practices

### Data Quality

| Practice | Benefit |
|----------|---------|
| Clean census data | Accurate testing |
| Verify HCE status | Correct classification |
| Reconcile compensation | Proper calculations |
| Document employees excluded | Support for exclusions |

### Mid-Year Projections

Run projections during the year:
- Identify potential failures early
- Implement corrections proactively
- Adjust HCE deferrals if needed
- Consider safe harbor adoption

### Documentation

| Document | Content |
|----------|---------|
| Testing results | Complete calculations |
| HCE determinations | How status determined |
| Corrections | Method and amounts |
| Elections | Testing method, top-paid group |

### Common Pitfalls

| Pitfall | Prevention |
|---------|------------|
| Wrong compensation definition | Use plan document definition |
| Incorrect HCE status | Apply lookback rules correctly |
| Missing participants | Include all eligible |
| Improper exclusions | Document exclusion basis |
| Late corrections | Track deadlines carefully |

### Testing Timeline

```
Plan Year End (December 31)
         ↓
Gather Data (January - February)
         ↓
Run Initial Tests (February)
         ↓
Correction Deadline - QNEC (March 15)
         ↓
Correction Deadline - No Tax (March 15)
         ↓
Correction Deadline - 10% Tax (December 31)
         ↓
Form 5500 Filing (July 31 or extended)
```

---

## Testing Reporting

### Form 5500 Disclosures

| Line | Content |
|------|---------|
| Schedule H/I | Financial information |
| Line 4a | Participant count |
| Line 4b-4g | Contribution information |
| Schedule R | Retirement plan information |

### Testing Documentation

Maintain for 6+ years:
- Complete testing calculations
- Participant data used
- HCE/NHCE classifications
- Correction calculations
- Distribution/contribution records

---

## Related Resources

- [Compliance Testing](401k-compliance-testing.md)
- [Plan Types](401k-plan-types.md)
- [Contribution Rules](401k-contribution-rules.md)
- [Correction Programs](401k-correction-programs.md)
- [IRS Requirements](401k-irs-requirements.md)

---

*Last Updated: 2024*
