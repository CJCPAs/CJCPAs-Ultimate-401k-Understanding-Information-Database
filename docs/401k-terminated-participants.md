# Terminated Participants in 401(k) Plans

## Overview

Managing terminated participants is a critical aspect of 401(k) plan administration. When employees leave, plans must properly handle their accounts, process distributions, calculate vesting, manage forfeitures, and comply with regulatory requirements. This comprehensive guide covers all aspects of terminated participant management.

## Table of Contents

1. [Terminated Participant Overview](#terminated-participant-overview)
2. [Termination Processing](#termination-processing)
3. [Vesting Calculations](#vesting-calculations)
4. [Distribution Options](#distribution-options)
5. [Automatic Cash-Outs](#automatic-cash-outs)
6. [Missing Participants](#missing-participants)
7. [Forfeiture Processing](#forfeiture-processing)
8. [Required Minimum Distributions](#required-minimum-distributions)
9. [Death Benefits](#death-benefits)
10. [Audit Considerations](#audit-considerations)

---

## Terminated Participant Overview

### Types of Terminations

| Type | Description | Special Considerations |
|------|-------------|----------------------|
| Voluntary resignation | Employee quits | Standard distribution rules |
| Involuntary termination | Layoff, discharge | Same distribution rules |
| Retirement | Normal, early, late | May have special provisions |
| Death | During employment | Beneficiary distributions |
| Disability | Unable to work | May have earlier distribution |
| Military leave | Active duty | USERRA protections |

### Key Terminology

| Term | Definition |
|------|------------|
| Vested balance | Amount participant owns |
| Non-vested balance | Amount subject to forfeiture |
| Distribution | Payment from plan |
| Rollover | Tax-free transfer to another plan/IRA |
| Forfeiture | Non-vested amount returned to plan |
| Cash-out | Small balance forced distribution |

### Regulatory Framework

| Regulation | Requirement |
|------------|-------------|
| IRC 401(a)(14) | Distribution timing |
| IRC 411 | Vesting requirements |
| ERISA 203 | Vesting standards |
| IRC 402 | Distribution taxation |
| DOL 2550.404a-3 | Safe harbor for missing participants |

---

## Termination Processing

### Termination Workflow

```
Employee Termination
        ↓
HR Notifies Plan Administrator
        ↓
Update Employment Status
        ↓
Calculate Vested Balance
        ↓
Process Forfeitures (if any)
        ↓
Provide Distribution Options
        ↓
Process Distribution Request
        ↓
Tax Reporting (1099-R)
```

### Data Requirements

| Data Element | Purpose |
|--------------|---------|
| Termination date | Vesting, distribution timing |
| Employment status | Active vs. terminated |
| Reason for termination | May affect distribution options |
| Final compensation | Calculations, testing |
| Hours through termination | Vesting service |
| Current address | Communications, tax reporting |

### Timeline Requirements

| Action | Deadline |
|--------|----------|
| Update status | Within 30 days of termination |
| Provide distribution notice | Reasonable time after termination |
| Process distribution request | Per plan document (typically 30-90 days) |
| Issue 1099-R | January 31 following distribution year |

### Termination Notice to Participant

Must inform terminated participant of:
- Account balance
- Vested percentage
- Distribution options
- Timing requirements
- Tax consequences
- Rollover options

---

## Vesting Calculations

### Vesting Fundamentals

#### Always 100% Vested

| Contribution Type | Reason |
|-------------------|--------|
| Employee deferrals (pre-tax) | IRC requirement |
| Employee deferrals (Roth) | IRC requirement |
| Rollover contributions | Participant's own money |
| Safe harbor contributions | Safe harbor requirement |
| QNEC/QMAC | Testing requirement |

#### Subject to Vesting Schedule

| Contribution Type | Typical Schedule |
|-------------------|------------------|
| Employer match | 3-year cliff or 6-year graded |
| Profit sharing | 3-year cliff or 6-year graded |
| Other employer contributions | Per plan document |

### Vesting Calculation Methods

#### Cliff Vesting

```
3-Year Cliff Vesting:
Years 0-2: 0% vested
Year 3+: 100% vested

Example:
Employee with 2.5 years of service
Employer match balance: $10,000
Vested amount: $0 (0%)
```

#### Graded Vesting

```
6-Year Graded Vesting:
Year 2: 20%
Year 3: 40%
Year 4: 60%
Year 5: 80%
Year 6+: 100%

Example:
Employee with 4 years of service
Employer match balance: $10,000
Vested amount: $6,000 (60%)
```

### Service Counting

#### Year of Service

Typically 1,000 hours in computation period:

| Computation Period | Hours Requirement |
|-------------------|-------------------|
| Initial period | 12 months from hire |
| Subsequent periods | Plan year or anniversary |

#### Break in Service Rules

| Type | Definition |
|------|------------|
| 1-year break | Less than 501 hours in computation period |
| 5-year break | 5 consecutive 1-year breaks |

**Effect of Breaks:**
- After 5-year break, prior non-vested service may be disregarded
- Rule of parity may apply

### Vesting Calculation Workpaper

```
VESTING CALCULATION

Participant: John Smith
Termination Date: October 15, 2024

Service Calculation:
- Hire date: March 1, 2020
- Termination date: October 15, 2024
- Years of service: 4.63 years
- Vesting service: 4 years (completed plan years)

Account Balances at Termination:
                        Balance    Vested%   Vested Amount
Employee pre-tax        $45,000    100%      $45,000
Employee Roth           $12,000    100%      $12,000
Employer match          $15,000     60%       $9,000
Profit sharing           $8,000     60%       $4,800
                        -------              -------
Total                   $80,000              $70,800

Forfeiture Calculation:
Total balance:          $80,000
Vested balance:         $70,800
Forfeiture:              $9,200
```

---

## Distribution Options

### Distribution Events

Participant may receive distribution upon:

| Event | Description |
|-------|-------------|
| Termination of employment | Separation from service |
| Death | To beneficiary |
| Disability | IRS definition |
| Plan termination | Full distribution required |
| Age 59½ | In-service distribution |
| Hardship | If permitted and qualified |

### Distribution Methods

| Method | Description |
|--------|-------------|
| Lump sum | Full account balance |
| Partial distribution | Portion of balance |
| Installments | Periodic payments |
| Annuity | Life income (if available) |
| Direct rollover | Tax-free to IRA/qualified plan |

### Distribution Form Requirements

| Form | Requirement |
|------|-------------|
| Distribution election | Participant's choice |
| Spousal consent | If QJSA plan and not rollover |
| Tax withholding | 20% mandatory on eligible amounts |
| Direct rollover notice | Required explanation |
| Special tax notice | IRC 402(f) notice |

### Direct Rollover Option

Plan must offer direct rollover to:

| Destination | Available |
|-------------|-----------|
| Traditional IRA | Yes |
| Roth IRA | Yes (taxable if pre-tax) |
| Employer's plan | If accepts rollovers |
| 403(b) | Yes |
| Governmental 457(b) | Yes |

### Tax Considerations

| Distribution Type | Tax Treatment |
|-------------------|---------------|
| Pre-tax distribution | Ordinary income |
| Roth distribution | Tax-free if qualified |
| Direct rollover | No current tax |
| Indirect rollover | 20% withholding, 60 days to complete |
| Early distribution | 10% penalty if under 59½ |

---

## Automatic Cash-Outs

### Small Balance Force-Out

Plans may force distribution of small balances:

| Balance | Treatment |
|---------|-----------|
| $0 | No distribution needed |
| $1-$1,000 | May distribute to participant |
| $1,001-$5,000 | Must roll to IRA if no election |
| $5,001-$7,000 | May roll to IRA (SECURE 2.0) |
| Over limit | Cannot force out |

### Automatic Rollover Rules

When automatic IRA rollover required:

| Requirement | Description |
|-------------|-------------|
| IRA provider | Must select qualified provider |
| Investment | Principal preservation (typically) |
| Fees | Must be reasonable |
| Notice | Must notify participant |

### Cash-Out Process

```
Cash-Out Workflow:

Termination
    ↓
Determine Vested Balance
    ↓
Below Cash-Out Threshold?
    ↓
Yes → Send Distribution Notice
    ↓
Wait for Election Period (30-180 days)
    ↓
No Election Received?
    ↓
If $1,001-$5,000 → Automatic IRA Rollover
If $1-$1,000 → Cash Distribution
```

### Notice Requirements

Before cash-out:

| Notice | Content |
|--------|---------|
| Distribution options | All available choices |
| Tax consequences | Withholding, penalties |
| Rollover rights | Direct rollover option |
| Election period | Time to make election |
| Default treatment | What happens if no election |

---

## Missing Participants

### Definition of Missing Participant

Participant is "missing" when:
- Mail returned undeliverable
- No response to communications
- Cannot locate current address
- Distribution cannot be completed

### DOL Safe Harbor for Missing Participants

#### Required Search Steps

| Step | Description |
|------|-------------|
| 1 | Certified mail to last known address |
| 2 | Check related plan records |
| 3 | Check employer records |
| 4 | Use free electronic search tools |
| 5 | Use commercial locator service (if cost-effective) |
| 6 | Contact designated beneficiary |

#### Search Documentation

```
MISSING PARTICIPANT SEARCH LOG

Participant: Jane Doe
SSN: XXX-XX-1234
Last Known Address: 123 Main St, Anytown, USA

Search Actions:
Date        Action                          Result
------------------------------------------------------
1/15/24     Certified mail to last address  Returned unclaimed
1/25/24     Checked employer HR records     No updated info
2/1/24      Free online search (various)    No results
2/15/24     Commercial locator service      No results
3/1/24      Contact emergency contact       Unable to reach

Conclusion: Participant deemed missing after reasonable search
Next Steps: Hold in plan per fiduciary decision
```

### Options for Missing Participant Funds

| Option | Description |
|--------|-------------|
| Hold in plan | Maintain account in plan |
| Transfer to IRA | Set up IRA for participant |
| State unclaimed property | Escheat to state |
| PBGC program | For terminating plans |
| Federally insured bank | Bank account in participant's name |

### Escheatment Considerations

| Factor | Consideration |
|--------|---------------|
| State laws | Vary by state |
| Dormancy period | Typically 3-5 years |
| Due diligence | Required before escheatment |
| Plan document | May address process |

---

## Forfeiture Processing

### When Forfeitures Occur

Forfeitures typically occur when:
- Non-vested participant terminates
- Participant takes cash-out before fully vested
- After specified break in service period

### Forfeiture Timing

Per plan document, typically:

| Timing | Description |
|--------|-------------|
| Upon distribution | When vested balance distributed |
| After break period | After 5 consecutive 1-year breaks |
| Upon cash-out | Upon distribution of vested portion |
| End of plan year | For terminated participants |

### Use of Forfeitures

Plan document specifies use:

| Use | Description |
|-----|-------------|
| Reduce employer contributions | Offset future contributions |
| Allocate to participants | Pro-rata allocation |
| Pay expenses | Reasonable plan expenses |
| Combination | Any combination above |

### Forfeiture Timing Rules

Recent IRS guidance requires forfeitures to be used by end of:
- Plan year following forfeiture
- Or reasonable time for administrative processing

### Forfeiture Tracking

```
FORFEITURE ACCOUNT RECONCILIATION

Beginning Balance (1/1/24):        $25,000

Current Year Forfeitures:
- Smith, John (3/15/24)            $9,200
- Williams, Mary (7/22/24)         $5,400
- Johnson, Robert (11/3/24)        $3,800
Total Forfeitures:                 $18,400

Use of Forfeitures:
- Reduce employer match           ($30,000)
- Pay audit fees                   ($8,000)
Total Used:                       ($38,000)

Ending Balance (12/31/24):          $5,400
```

---

## Required Minimum Distributions

### When RMDs Begin

For terminated participants:

| Situation | Required Beginning Date |
|-----------|------------------------|
| 5%+ owner | April 1 after year reaching RMD age |
| Non-owner | April 1 after later of RMD age or termination |

### RMD Ages

| Birth Year | RMD Age |
|------------|---------|
| Before 1951 | 72 |
| 1951-1959 | 73 |
| 1960+ | 75 |

### RMD Processing

| Step | Action |
|------|--------|
| 1 | Identify participants subject to RMD |
| 2 | Calculate RMD amount |
| 3 | Notify participant |
| 4 | Process distribution |
| 5 | Issue 1099-R |

### RMD Calculation

```
RMD Calculation:

Participant: Robert Johnson
Age at year-end: 75
Account Balance (12/31/prior year): $500,000

Uniform Lifetime Table factor (age 75): 24.6

RMD = $500,000 / 24.6 = $20,325

Minimum distribution required: $20,325
```

### RMD Penalties

| Issue | Penalty |
|-------|---------|
| Failure to take RMD | 25% of shortfall |
| Timely correction | Reduced to 10% |

---

## Death Benefits

### Death Before Distribution

When participant dies:

| Step | Action |
|------|--------|
| 1 | Verify death (death certificate) |
| 2 | Identify beneficiary |
| 3 | Notify beneficiary of options |
| 4 | Process beneficiary claim |
| 5 | Distribute per beneficiary election |

### Beneficiary Categories

| Category | Distribution Options |
|----------|---------------------|
| Surviving spouse | Rollover to own account, remain in plan, lump sum |
| Non-spouse designated | 10-year rule or immediate distribution |
| Eligible designated beneficiary | Life expectancy distributions |
| Non-designated (estate) | 5-year rule |

### Eligible Designated Beneficiaries

| Type | Description |
|------|-------------|
| Surviving spouse | Married at death |
| Minor child | Of participant (not grandchild) |
| Disabled | IRS definition |
| Chronically ill | IRS definition |
| Not more than 10 years younger | Age proximity |

### Death Benefit Distribution Rules

#### Spouse Beneficiary

| Option | Description |
|--------|-------------|
| Roll to own IRA | Treat as own |
| Remain in plan | If permitted |
| Lump sum | Full distribution |
| Stretch | Life expectancy distributions |

#### Non-Spouse Beneficiary (Post-SECURE Act)

| Type | Distribution Period |
|------|---------------------|
| Eligible designated | Life expectancy |
| Designated (not eligible) | 10-year rule |
| Non-designated | 5-year rule |

---

## Audit Considerations

### Terminated Participant Testing

Auditors test terminated participants for:

| Area | Testing Focus |
|------|---------------|
| Status | Proper termination coding |
| Vesting | Accurate vesting calculation |
| Distributions | Proper processing |
| Forfeitures | Correct timing and use |
| Missing participants | Proper search procedures |
| RMDs | Timely distributions |

### Sample Testing Procedures

```
TERMINATED PARTICIPANT AUDIT TEST

Participant: Sarah Miller
Termination Date: June 30, 2024

Test Items:
1. Verify termination date per HR records ✓
2. Verify status updated in plan records ✓
3. Calculate vesting:
   - Service: 3.5 years
   - Schedule: 6-year graded
   - Expected: 40% ✓
4. Verify forfeiture calculation ✓
5. Verify distribution processed correctly ✓
6. Verify 1099-R issued ✓
7. Trace distribution to bank statement ✓

Conclusion: No exceptions
```

### Common Audit Findings

| Finding | Description |
|---------|-------------|
| Incorrect vesting | Wrong service calculation |
| Late forfeitures | Not processed timely |
| Missing distributions | Cash-outs not processed |
| Improper forfeiture use | Used contrary to plan |
| Missing participant issues | Inadequate search |
| RMD failures | Not distributed timely |

### Documentation Requirements

Maintain for 6+ years:

| Document | Purpose |
|----------|---------|
| Termination records | Verify termination date |
| Vesting calculations | Support vested amounts |
| Distribution elections | Participant authorization |
| 1099-R forms | Tax reporting |
| Forfeiture records | Track forfeiture amounts and use |
| Search documentation | Missing participant efforts |

---

## Best Practices

### Process Improvements

| Practice | Benefit |
|----------|---------|
| Automated status updates | Timely processing |
| Vesting calculators | Accurate calculations |
| Distribution tracking | Complete processing |
| Missing participant procedures | Documented search efforts |
| Regular reconciliation | Identify issues early |

### Monitoring and Reporting

| Report | Frequency |
|--------|-----------|
| Terminated participant list | Monthly |
| Pending distributions | Weekly |
| Forfeiture activity | Monthly |
| Missing participant status | Quarterly |
| RMD tracking | Monthly (for applicable participants) |

### Common Issues and Solutions

| Issue | Solution |
|-------|----------|
| Late termination updates | Automated HR feed |
| Vesting errors | Systematic calculations |
| Distribution delays | Clear procedures and deadlines |
| Forfeiture timing | Calendar reminders |
| Missing participants | Proactive address verification |

---

## Related Resources

- [Distributions](401k-distributions.md)
- [Vesting](401k-vesting.md)
- [Participant Data Management](401k-participant-data.md)
- [Administration](401k-administration.md)
- [Audit Testing](401k-audit-testing.md)

---

*Last Updated: 2024*
