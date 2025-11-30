# 401(k) Audit Calculation Templates & Worksheets

This document provides comprehensive calculation templates for 401(k) audits, including ADP/ACP testing, statistical sampling, materiality determination, and other essential audit calculations.

---

## Table of Contents

1. [Materiality Calculations](#materiality-calculations)
2. [Statistical Sampling Tables](#statistical-sampling-tables)
3. [ADP/ACP Testing Worksheets](#adpacp-testing-worksheets)
4. [Top-Heavy Testing Calculations](#top-heavy-testing-calculations)
5. [Coverage Testing (410(b))](#coverage-testing-410b)
6. [Contribution Limit Testing (415)](#contribution-limit-testing-415)
7. [Compensation Limit Testing (401(a)(17))](#compensation-limit-testing-401a17)
8. [Vesting Calculations](#vesting-calculations)
9. [Loan Compliance Calculations](#loan-compliance-calculations)
10. [RMD Calculations](#rmd-calculations)
11. [Forfeiture Allocation Calculations](#forfeiture-allocation-calculations)

---

## Materiality Calculations

### Planning Materiality Worksheet

Materiality for employee benefit plan audits is typically calculated as a percentage of net assets available for benefits.

#### Step 1: Determine Base Amount

| Item | Amount | Source |
|------|--------|--------|
| Net Assets Available for Benefits (Beginning of Year) | $__________ | Prior Year F/S |
| Net Assets Available for Benefits (End of Year) | $__________ | Current Trial Balance |
| **Average Net Assets** | $__________ | (Beginning + End) / 2 |

#### Step 2: Apply Materiality Percentage

| Plan Size | Typical Materiality Range | Rationale |
|-----------|---------------------------|-----------|
| Under $10 million | 1% - 3% | Higher percentage due to smaller base |
| $10 - $50 million | 0.5% - 2% | Moderate risk |
| $50 - $200 million | 0.5% - 1% | Lower percentage, higher absolute |
| Over $200 million | 0.25% - 0.75% | Large plans, lower percentage |

#### Step 3: Calculate Materiality

| Calculation | Amount |
|-------------|--------|
| Base: Average Net Assets | $__________ |
| Materiality Percentage Selected | ___% |
| **Overall Materiality** | $__________ |
| Performance Materiality (typically 50-75% of overall) | $__________ |
| Clearly Trivial Threshold (typically 3-5% of overall) | $__________ |

#### Materiality Calculation Example

```
Plan Assets: $45,000,000
Selected Percentage: 1%

Overall Materiality:     $45,000,000 × 1% = $450,000
Performance Materiality: $450,000 × 75%   = $337,500
Clearly Trivial:        $450,000 × 5%    = $22,500
```

#### Factors to Consider When Setting Materiality

| Factor | Impact on Materiality | Documentation |
|--------|----------------------|---------------|
| First-year audit | Lower | Higher risk |
| Prior audit adjustments | Lower | Control concerns |
| Plan complexity | Lower | More opportunity for error |
| Management integrity concerns | Lower | Higher risk |
| Participant demographics (near retirement) | Lower | Higher reliance on accuracy |
| Simple plan design | Higher | Less risk |
| Strong internal controls | Higher | Less substantive testing needed |

---

## Statistical Sampling Tables

### Sample Size Determination - Attribute Sampling

Use for compliance testing (e.g., testing whether contributions were properly calculated).

#### Table A: Sample Sizes for Attribute Sampling (95% Confidence Level)

| Population Size | Expected Deviation Rate 0% | Expected Deviation Rate 1% | Expected Deviation Rate 2% | Expected Deviation Rate 3% |
|-----------------|---------------------------|---------------------------|---------------------------|---------------------------|
| 50-100 | 45 | 77 | * | * |
| 101-200 | 55 | 103 | 181 | * |
| 201-500 | 64 | 129 | 195 | * |
| 501-1,000 | 74 | 159 | 265 | * |
| 1,001-2,000 | 78 | 181 | 318 | * |
| 2,001-5,000 | 82 | 195 | 360 | * |
| Over 5,000 | 87 | 211 | 410 | * |

*\* Sample size exceeds practical limits; consider alternative procedures*

**Tolerable Deviation Rate: 5%**

#### Table B: Sample Sizes Based on Risk Assessment

| Risk of Material Misstatement | Reliance on Controls | Suggested Sample Size Range |
|------------------------------|---------------------|----------------------------|
| High | Low/None | 60-90 items |
| Moderate | Moderate | 40-60 items |
| Low | High | 25-40 items |

### Sample Size Determination - Variables Sampling

Use for substantive testing (e.g., testing account balances).

#### Monetary Unit Sampling (MUS) Sample Size Formula

```
Sample Size = (Book Value × Confidence Factor) / (Materiality - Expected Error)
```

#### Confidence Factors

| Confidence Level | Risk of Incorrect Acceptance | Factor (0 errors expected) |
|-----------------|------------------------------|---------------------------|
| 95% | 5% | 3.00 |
| 90% | 10% | 2.31 |
| 85% | 15% | 1.90 |
| 80% | 20% | 1.61 |

#### MUS Sample Size Calculation Worksheet

| Input | Value |
|-------|-------|
| Book Value of Population | $__________ |
| Planning Materiality | $__________ |
| Expected Error (typically 0 for EB plans) | $__________ |
| Confidence Level Selected | ___% |
| Confidence Factor | __________ |

| Calculation | |
|-------------|---|
| Sampling Interval = Materiality / Confidence Factor | $__________ |
| Sample Size = Book Value / Sampling Interval | __________ |

#### MUS Example Calculation

```
Book Value:           $45,000,000
Materiality:          $450,000
Expected Error:       $0
Confidence Factor:    3.00 (95% confidence)

Sampling Interval = $450,000 / 3.00 = $150,000
Sample Size = $45,000,000 / $150,000 = 300 items

Rounded sample size: 300
```

### Quick Reference: Sample Size by Plan Size

| Number of Participants | Minimum Recommended Sample - Contributions | Minimum Recommended Sample - Distributions |
|-----------------------|-------------------------------------------|------------------------------------------|
| 100-250 | 25-30 | 15-20 |
| 251-500 | 30-40 | 20-25 |
| 501-1,000 | 40-50 | 25-35 |
| 1,001-2,500 | 50-60 | 35-45 |
| 2,501-5,000 | 60-75 | 45-55 |
| Over 5,000 | 75-100 | 55-75 |

---

## ADP/ACP Testing Worksheets

### ADP Test (Actual Deferral Percentage) Calculation

The ADP test ensures that highly compensated employees (HCEs) do not defer disproportionately more than non-highly compensated employees (NHCEs).

#### Step 1: Identify HCEs and NHCEs

**HCE Definition (2024):**
- More than 5% owner at any time during current or prior year, OR
- Compensation > $155,000 in prior year (and top 20% if elected)

| Employee | Compensation | 5%+ Owner? | HCE or NHCE |
|----------|-------------|------------|-------------|
| __________ | $__________ | Yes / No | HCE / NHCE |
| __________ | $__________ | Yes / No | HCE / NHCE |
| __________ | $__________ | Yes / No | HCE / NHCE |
| __________ | $__________ | Yes / No | HCE / NHCE |

#### Step 2: Calculate Individual ADPs

**ADP Formula:**
```
Individual ADP = (Elective Deferrals / 415 Compensation) × 100
```

| Employee | Elective Deferrals | 415 Compensation | Individual ADP |
|----------|-------------------|------------------|----------------|
| HCE 1 | $__________ | $__________ | ___% |
| HCE 2 | $__________ | $__________ | ___% |
| HCE 3 | $__________ | $__________ | ___% |
| **HCE Average** | | | **___% (A)** |
| NHCE 1 | $__________ | $__________ | ___% |
| NHCE 2 | $__________ | $__________ | ___% |
| NHCE 3 | $__________ | $__________ | ___% |
| **NHCE Average** | | | **___% (B)** |

#### Step 3: Apply ADP Test Limits

| If NHCE ADP (B) is: | Then HCE ADP (A) cannot exceed: |
|--------------------|--------------------------------|
| 0% - 2% | NHCE ADP × 2 |
| 2% - 8% | NHCE ADP + 2% |
| Over 8% | NHCE ADP × 1.25 |

#### Step 4: Test Results

| Calculation | Amount |
|-------------|--------|
| NHCE Average ADP | ___% |
| Maximum Allowable HCE ADP | ___% |
| Actual HCE ADP | ___% |
| **Test Result** | PASS / FAIL |

#### Step 5: Excess Contribution Calculation (If Failed)

```
Excess Amount = (HCE ADP - Maximum ADP) × HCE Compensation
```

| HCE | Excess Percentage | Compensation | Excess Amount |
|-----|-------------------|--------------|---------------|
| __________ | ___% | $__________ | $__________ |
| __________ | ___% | $__________ | $__________ |
| **Total Excess Contributions** | | | **$__________** |

---

### ACP Test (Actual Contribution Percentage) Calculation

The ACP test applies to employer matching contributions and after-tax employee contributions.

#### ACP Calculation Worksheet

**ACP Formula:**
```
Individual ACP = (Matching Contributions + After-Tax Contributions) / 415 Compensation × 100
```

| Employee | Match | After-Tax | 415 Comp | Individual ACP |
|----------|-------|-----------|----------|----------------|
| HCE 1 | $__________ | $__________ | $__________ | ___% |
| HCE 2 | $__________ | $__________ | $__________ | ___% |
| **HCE Average** | | | | **___% (C)** |
| NHCE 1 | $__________ | $__________ | $__________ | ___% |
| NHCE 2 | $__________ | $__________ | $__________ | ___% |
| **NHCE Average** | | | | **___% (D)** |

#### ACP Test Limits (Same as ADP)

| If NHCE ACP (D) is: | Then HCE ACP (C) cannot exceed: |
|--------------------|--------------------------------|
| 0% - 2% | NHCE ACP × 2 |
| 2% - 8% | NHCE ACP + 2% |
| Over 8% | NHCE ACP × 1.25 |

---

### Combined ADP/ACP Testing Summary

| Test | NHCE Average | Max HCE | Actual HCE | Result |
|------|--------------|---------|------------|--------|
| ADP | ___% | ___% | ___% | PASS/FAIL |
| ACP | ___% | ___% | ___% | PASS/FAIL |

#### Safe Harbor Exemptions

| Safe Harbor Type | ADP Test | ACP Test | Matching Requirement |
|-----------------|----------|----------|---------------------|
| Basic Safe Harbor | Exempt | Exempt | 100% on first 3%, 50% on next 2% |
| Enhanced Safe Harbor | Exempt | Exempt | 100% on first 4% |
| QACA Safe Harbor | Exempt | Exempt | 100% on first 1%, 50% on next 5% |
| Non-Elective 3% | Exempt | Not Exempt | 3% to all eligible |

---

## Top-Heavy Testing Calculations

### Top-Heavy Determination Worksheet

A plan is top-heavy if key employees own more than 60% of plan assets.

#### Step 1: Identify Key Employees

**Key Employee Definition (2024):**
- Officer with compensation > $220,000
- 5% owner
- 1% owner with compensation > $150,000

| Employee | Position | Compensation | Ownership % | Key Employee? |
|----------|----------|--------------|-------------|---------------|
| __________ | __________ | $__________ | ___% | Yes / No |
| __________ | __________ | $__________ | ___% | Yes / No |
| __________ | __________ | $__________ | ___% | Yes / No |

#### Step 2: Calculate Account Balances

| | Key Employees | Non-Key Employees | Total |
|---|--------------|-------------------|-------|
| Account Balances | $__________ | $__________ | $__________ |
| Percentage | ___% | ___% | 100% |

#### Step 3: Top-Heavy Determination

| Calculation | Result |
|-------------|--------|
| Key Employee Account Balance | $__________ |
| Total Plan Assets | $__________ |
| Key Employee Percentage | ___% |
| **Top-Heavy Status** (>60% = Top-Heavy) | TOP-HEAVY / NOT TOP-HEAVY |

#### Step 4: Minimum Contribution Requirement (If Top-Heavy)

If top-heavy, non-key employees must receive minimum contribution of **3%** of compensation (or highest key employee contribution percentage if less).

| Non-Key Employee | Compensation | Minimum Required (3%) | Actual Contribution | Shortfall |
|-----------------|--------------|----------------------|--------------------|-----------|
| __________ | $__________ | $__________ | $__________ | $__________ |
| __________ | $__________ | $__________ | $__________ | $__________ |
| **Total** | $__________ | $__________ | $__________ | $__________ |

---

## Coverage Testing (410(b))

### Ratio Percentage Test Worksheet

The plan must benefit a sufficient percentage of non-highly compensated employees.

#### Step 1: Count Employees

| Category | Count |
|----------|-------|
| Total Employees | __________ |
| Excludable Employees | |
| - Under age 21 | __________ |
| - Less than 1 year of service | __________ |
| - Covered by collective bargaining | __________ |
| - Nonresident aliens | __________ |
| **Non-Excludable Employees** | __________ |

#### Step 2: Separate HCEs and NHCEs

| | HCEs | NHCEs |
|---|------|-------|
| Non-Excludable Employees | __________ | __________ |
| Benefiting Under Plan | __________ | __________ |
| **Percentage Benefiting** | ___% | ___% |

#### Step 3: Ratio Percentage Test

```
Ratio Percentage = NHCE Percentage / HCE Percentage
```

| Calculation | Value |
|-------------|-------|
| NHCE Benefiting Percentage | ___% (A) |
| HCE Benefiting Percentage | ___% (B) |
| **Ratio Percentage (A/B)** | ___% |
| Minimum Required | 70% |
| **Test Result** | PASS / FAIL |

---

## Contribution Limit Testing (415)

### Annual Additions Limit Worksheet (2024)

The total annual additions to a participant's account cannot exceed the lesser of:
- $69,000 (2024), or
- 100% of compensation

#### Individual 415 Test

| Participant | Employee Deferrals | Employer Contributions | Forfeitures Allocated | Total Annual Additions | 415 Limit | Result |
|-------------|-------------------|----------------------|----------------------|----------------------|-----------|--------|
| __________ | $__________ | $__________ | $__________ | $__________ | $69,000 | PASS/FAIL |
| __________ | $__________ | $__________ | $__________ | $__________ | $69,000 | PASS/FAIL |

#### Participants Over Age 50 (Catch-Up Eligible)

| Participant | Base Limit | Catch-Up Used | Total Limit |
|-------------|-----------|---------------|-------------|
| __________ | $69,000 | $7,500 | $76,500 |

#### SECURE 2.0 Enhanced Catch-Up (Ages 60-63, Effective 2025)

| Participant | Age | Base Limit | Enhanced Catch-Up | Total Limit |
|-------------|-----|-----------|-------------------|-------------|
| __________ | 61 | $69,000 | $11,250 | $80,250 |

---

## Compensation Limit Testing (401(a)(17))

### Compensation Cap Worksheet (2024)

Plan compensation for testing and contribution purposes is limited to $345,000.

| Participant | Actual Compensation | Capped Compensation | Difference |
|-------------|--------------------|--------------------|------------|
| __________ | $__________ | $__________ | $__________ |
| __________ | $__________ | $__________ | $__________ |
| __________ | $__________ | $__________ | $__________ |

#### Impact on Contribution Calculations

| Participant | Match Rate | Actual Comp | Capped Comp | Match on Actual | Match on Capped | Excess |
|-------------|-----------|-------------|-------------|-----------------|-----------------|--------|
| __________ | ___% | $__________ | $345,000 | $__________ | $__________ | $__________ |

---

## Vesting Calculations

### Vesting Schedule Application Worksheet

#### Common Vesting Schedules

| Years of Service | 3-Year Cliff | 6-Year Graded | 2-to-6 Year Graded (QACA) |
|-----------------|--------------|---------------|---------------------------|
| Less than 1 | 0% | 0% | 0% |
| 1 | 0% | 0% | 0% |
| 2 | 0% | 20% | 20% |
| 3 | 100% | 40% | 40% |
| 4 | 100% | 60% | 60% |
| 5 | 100% | 80% | 80% |
| 6+ | 100% | 100% | 100% |

#### Individual Vesting Calculation

| Participant | Hire Date | Term Date | Years of Service | Vesting % | Employer Balance | Vested Amount | Forfeiture |
|-------------|-----------|-----------|------------------|-----------|------------------|---------------|------------|
| __________ | __________ | __________ | __________ | ___% | $__________ | $__________ | $__________ |
| __________ | __________ | __________ | __________ | ___% | $__________ | $__________ | $__________ |

---

## Loan Compliance Calculations

### Maximum Loan Amount Calculation

#### IRC Section 72(p) Limits

The maximum loan is the lesser of:
- $50,000 reduced by highest outstanding loan balance in prior 12 months, or
- 50% of vested account balance

#### Loan Limit Worksheet

| Participant | Vested Balance | 50% of Vested | Highest Loan (Prior 12 Mo) | $50,000 Limit | Maximum Loan |
|-------------|---------------|---------------|---------------------------|---------------|--------------|
| __________ | $__________ | $__________ | $__________ | $__________ | $__________ |
| __________ | $__________ | $__________ | $__________ | $__________ | $__________ |

**Example Calculation:**
```
Vested Balance:               $120,000
50% of Vested:               $60,000
Highest Loan (Prior 12 Mo):  $10,000
$50,000 - $10,000:           $40,000

Maximum Loan = Lesser of $60,000 or $40,000 = $40,000
```

#### Loan Repayment Testing

| Loan | Original Amount | Term (Months) | Interest Rate | Required Payment | Actual Payment | Level Amortization? |
|------|----------------|---------------|---------------|------------------|----------------|---------------------|
| __________ | $__________ | __________ | ___% | $__________ | $__________ | Yes / No |

---

## RMD Calculations

### Required Minimum Distribution Worksheet

#### RMD Age Requirements (Post-SECURE 2.0)

| Birth Year | RMD Beginning Age |
|-----------|-------------------|
| Before 1951 | 70½ (already started) |
| 1951-1959 | 73 |
| 1960 or later | 75 |

#### RMD Calculation

```
RMD = Prior Year-End Account Balance / Distribution Period Factor
```

#### Uniform Lifetime Table (Partial)

| Age | Distribution Period |
|-----|---------------------|
| 73 | 26.5 |
| 74 | 25.5 |
| 75 | 24.6 |
| 76 | 23.7 |
| 77 | 22.9 |
| 78 | 22.0 |
| 79 | 21.1 |
| 80 | 20.2 |
| 85 | 16.0 |
| 90 | 12.2 |

#### Individual RMD Calculation

| Participant | Age | Prior Year Balance | Life Expectancy Factor | Required RMD | Actual Distribution | Shortfall |
|-------------|-----|-------------------|----------------------|--------------|--------------------|-----------|
| __________ | ___ | $__________ | __________ | $__________ | $__________ | $__________ |
| __________ | ___ | $__________ | __________ | $__________ | $__________ | $__________ |

---

## Forfeiture Allocation Calculations

### Forfeiture Tracking Worksheet

| Date | Participant | Reason | Gross Forfeiture | Restoration | Net Forfeiture |
|------|-------------|--------|------------------|-------------|----------------|
| __________ | __________ | Term/5-year rule | $__________ | $__________ | $__________ |
| __________ | __________ | Term/5-year rule | $__________ | $__________ | $__________ |
| **Total Available Forfeitures** | | | | | $__________ |

#### Forfeiture Usage (Per Plan Document)

| Use | Amount | Remaining |
|-----|--------|-----------|
| Beginning Forfeiture Balance | | $__________ |
| Offset Employer Contributions | $__________ | $__________ |
| Pay Plan Expenses | $__________ | $__________ |
| Reallocate to Participants | $__________ | $__________ |
| **Ending Forfeiture Balance** | | $__________ |

#### Audit Considerations

| Forfeiture Issue | Test |
|-----------------|------|
| Timing of forfeiture recognition | Within plan year of 5 consecutive breaks |
| Use within reasonable time | Typically same or following plan year |
| Allocation per plan document | Match document terms |
| Suspense account accuracy | Reconcile balance |

---

## Appendix: Excel Formula Quick Reference

### Key Formulas for 401(k) Calculations

#### ADP/ACP Percentage
```excel
=IF(Compensation>0, Deferrals/Compensation, 0)
```

#### Average ADP
```excel
=AVERAGE(ADP_Range)
```

#### Maximum HCE ADP (Based on NHCE)
```excel
=IF(NHCE_ADP<=2, NHCE_ADP*2, IF(NHCE_ADP<=8, NHCE_ADP+2, NHCE_ADP*1.25))
```

#### Top-Heavy Percentage
```excel
=Key_Employee_Balance / Total_Plan_Assets
```

#### Ratio Percentage Test
```excel
=NHCE_Benefiting_Pct / HCE_Benefiting_Pct
```

#### Maximum Loan Amount
```excel
=MIN(Vested_Balance*0.5, 50000-Highest_Prior_Loan)
```

#### RMD Calculation
```excel
=Prior_Year_Balance / VLOOKUP(Age, Life_Expectancy_Table, 2)
```

#### Vesting Percentage (6-Year Graded)
```excel
=IF(Years<2,0,IF(Years<3,0.2,IF(Years<4,0.4,IF(Years<5,0.6,IF(Years<6,0.8,1)))))
```

---

## Document History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2024 | Initial release |

---

*This template is part of the Ultimate 401(k) Understanding Information Database. For the most current IRS limits and guidance, always verify with official IRS publications.*
