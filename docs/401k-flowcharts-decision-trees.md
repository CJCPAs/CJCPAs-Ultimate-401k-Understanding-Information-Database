# 401(k) Audit Flowcharts & Decision Trees

Visual guides and decision trees for navigating complex 401(k) audit decisions. These flowcharts cover audit scope determination, testing procedures, compliance issues, and reporting decisions.

---

## Table of Contents

1. [Audit Scope Determination](#audit-scope-determination)
2. [Audit Requirement Decision Tree](#audit-requirement-decision-tree)
3. [Limited Scope vs Full Scope](#limited-scope-vs-full-scope)
4. [Certification Evaluation](#certification-evaluation)
5. [Contribution Testing Flow](#contribution-testing-flow)
6. [Distribution Testing Flow](#distribution-testing-flow)
7. [Compliance Testing Decision Tree](#compliance-testing-decision-tree)
8. [ADP/ACP Test Failure Response](#adpacp-test-failure-response)
9. [Audit Finding Classification](#audit-finding-classification)
10. [Opinion Modification Decisions](#opinion-modification-decisions)
11. [Late Contribution Evaluation](#late-contribution-evaluation)
12. [Participant Loan Compliance](#participant-loan-compliance)
13. [Prohibited Transaction Identification](#prohibited-transaction-identification)
14. [Form 5500 Reconciliation](#form-5500-reconciliation)
15. [First-Year Audit Decision Flow](#first-year-audit-decision-flow)

---

## Audit Scope Determination

### When Is an Audit Required?

```
                           ┌─────────────────────────┐
                           │  Count eligible         │
                           │  participants at BOY    │
                           └───────────┬─────────────┘
                                       │
                    ┌──────────────────┼──────────────────┐
                    │                  │                  │
                    ▼                  ▼                  ▼
            ┌───────────┐      ┌───────────────┐   ┌─────────────┐
            │  < 100    │      │   100 - 120   │   │    > 120    │
            │           │      │               │   │             │
            └─────┬─────┘      └───────┬───────┘   └──────┬──────┘
                  │                    │                  │
                  ▼                    ▼                  ▼
          ┌──────────────┐    ┌────────────────┐   ┌─────────────┐
          │ NO AUDIT     │    │ Apply 80-120   │   │ AUDIT       │
          │ REQUIRED     │    │ Rule (below)   │   │ REQUIRED    │
          │ (Small Plan) │    │                │   │             │
          └──────────────┘    └────────────────┘   └─────────────┘
```

### The 100/120 Rule (Commonly Miscalled "80-120 Rule")

**The number "80" is irrelevant.** Only two thresholds matter: **100** and **120**.

```
                      ┌──────────────────────────┐
                      │ Was an audit required    │
                      │ in the PRIOR year?       │
                      └────────────┬─────────────┘
                                   │
               ┌───────────────────┴───────────────────┐
               │                                       │
               ▼                                       ▼
       ┌───────────────┐                       ┌───────────────┐
       │   YES         │                       │   NO          │
       │   (Large      │                       │   (Small      │
       │    Plan)      │                       │    Plan)      │
       └───────┬───────┘                       └───────┬───────┘
               │                                       │
               ▼                                       ▼
    ┌────────────────────┐              ┌──────────────────────┐
    │ Current Year       │              │ Current Year         │
    │ Participants?      │              │ Participants?        │
    └──────────┬─────────┘              └───────────┬──────────┘
               │                                    │
    ┌──────────┴──────────┐             ┌──────────┴──────────┐
    │                     │             │                     │
    ▼                     ▼             ▼                     ▼
  ≥100                  <100          ≤120                  >120
    │                     │             │                     │
    ▼                     ▼             ▼                     ▼
 ┌──────┐           ┌──────┐       ┌──────┐             ┌──────┐
 │AUDIT │           │  NO  │       │  NO  │             │AUDIT │
 │REQ'D │           │AUDIT │       │AUDIT │             │REQ'D │
 │      │           │(elect│       │(stay │             │      │
 │(stay │           │small)│       │small)│             │      │
 │large)│           │      │       │      │             │      │
 └──────┘           └──────┘       └──────┘             └──────┘
```

**Key thresholds:**
- **100** = Point where large plans can drop to small (under 100 = can elect small)
- **121** = Point where small plans must become large (over 120 = audit required)

**Key Points (Updated 2023):**
- Count only participants **with account balances** (not all "eligible" employees)
- Count at beginning of plan year (for existing plans)
- For first-year plans, count at **end** of plan year
- Include terminated participants with balances
- Exclude eligible employees who have not enrolled ($0 balance)
- The number "80" triggers nothing—ignore it

---

## Limited Scope vs Full Scope

### Determining Audit Scope

```
                    ┌────────────────────────────────┐
                    │ Does the Plan hold all assets  │
                    │ with a qualifying institution? │
                    │ (Bank, Trust Co, Insurance Co) │
                    └───────────────┬────────────────┘
                                    │
                    ┌───────────────┴───────────────┐
                    │                               │
                    ▼                               ▼
               ┌─────────┐                     ┌─────────┐
               │   YES   │                     │   NO    │
               └────┬────┘                     └────┬────┘
                    │                               │
                    ▼                               ▼
    ┌───────────────────────────┐           ┌──────────────┐
    │ Did the institution       │           │ FULL SCOPE   │
    │ provide a certification?  │           │ AUDIT        │
    └─────────────┬─────────────┘           │ REQUIRED     │
                  │                         └──────────────┘
      ┌───────────┴───────────┐
      │                       │
      ▼                       ▼
 ┌─────────┐             ┌─────────┐
 │   YES   │             │   NO    │
 └────┬────┘             └────┬────┘
      │                       │
      ▼                       ▼
 ┌────────────────┐     ┌──────────────┐
 │ Does the cert  │     │ FULL SCOPE   │
 │ meet all DOL   │     │ AUDIT        │
 │ requirements?  │     │ REQUIRED     │
 └───────┬────────┘     └──────────────┘
         │
  ┌──────┴──────┐
  │             │
  ▼             ▼
┌───┐         ┌───┐
│YES│         │NO │
└─┬─┘         └─┬─┘
  │             │
  ▼             ▼
┌──────────┐  ┌──────────────┐
│ LIMITED  │  │ FULL SCOPE   │
│ SCOPE    │  │ AUDIT        │
│ ALLOWED  │  │ REQUIRED     │
└──────────┘  └──────────────┘
```

---

## Certification Evaluation

### Is the Certification Valid?

```
┌─────────────────────────────────────────────────────────────────────┐
│                    CERTIFICATION EVALUATION                          │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
              ┌─────┤ 1. QUALIFYING INSTITUTION│─────┐
              │     └─────────────────────────┘     │
              │                                     │
              ▼                                     ▼
      ┌───────────────┐                     ┌───────────────┐
      │ Is certifying │                     │ Is it a:      │
      │ entity one of:│                     │ - Credit Union│
      │ - Bank        │  ───► NO ──────────►│ - Broker/Dlr  │
      │ - Trust Co    │                     │ - Mutual Fund │
      │ - Ins Carrier │                     └───────┬───────┘
      └───────┬───────┘                             │
              │                                     ▼
              │ YES                         ┌───────────────┐
              │                             │ NOT QUALIFYING│
              ▼                             │ → FULL SCOPE  │
      ┌───────────────┐                     └───────────────┘
      │ 2. REGULATED? │
      │ By federal or │
      │ state agency? │
      └───────┬───────┘
              │
      ┌───────┴───────┐
      │               │
      ▼               ▼
    ┌───┐           ┌───┐
    │YES│           │NO │────► FULL SCOPE REQUIRED
    └─┬─┘           └───┘
      │
      ▼
┌─────────────────────────┐
│ 3. REQUIRED CONTENT     │
│ Does cert include:      │
│ □ Fair value of assets  │
│ □ Investment income     │
│ □ Realized gains/losses │
│ □ Unrealized gains/loss │
│ □ All transactions      │
└───────────┬─────────────┘
            │
    ┌───────┴───────┐
    │               │
    ▼               ▼
  ┌───┐           ┌───┐
  │ALL│           │NO │────► REQUEST CORRECTED CERT
  └─┬─┘           └───┘      OR FULL SCOPE
    │
    ▼
┌─────────────────────────┐
│ 4. PERIOD COVERAGE      │
│ Does cert cover entire  │
│ plan year?              │
└───────────┬─────────────┘
            │
    ┌───────┴───────┐
    │               │
    ▼               ▼
  ┌───┐           ┌───┐
  │YES│           │NO │────► FULL SCOPE FOR
  └─┬─┘           └───┘      UNCERTIFIED PERIOD
    │
    ▼
┌─────────────────────────┐
│ 5. SIGNED & DATED       │
│ By authorized official? │
└───────────┬─────────────┘
            │
    ┌───────┴───────┐
    │               │
    ▼               ▼
  ┌───┐           ┌───┐
  │YES│           │NO │────► REQUEST PROPER
  └─┬─┘           └───┘      SIGNATURE
    │
    ▼
┌──────────────────────────┐
│  ✓ VALID CERTIFICATION   │
│    Limited Scope Allowed │
└──────────────────────────┘
```

---

## Contribution Testing Flow

### Testing Participant Contributions

```
┌─────────────────────────────────────────────────────────────────────┐
│                    CONTRIBUTION TESTING FLOW                         │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ 1. OBTAIN POPULATION    │
                    │ All contribution        │
                    │ remittances for year    │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ 2. RECONCILE TO TRUST   │
                    │ Total contributions per │
                    │ remittances = Trust?    │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │ AGREES  │                     │ DIFFERS │
           └────┬────┘                     └────┬────┘
                │                               │
                │                               ▼
                │                    ┌─────────────────────┐
                │                    │ INVESTIGATE         │
                │                    │ Document variance   │
                │                    │ Determine if error  │
                │                    └─────────────────────┘
                │
                ▼
    ┌─────────────────────────┐
    │ 3. SELECT SAMPLE        │
    │ (Per sampling plan)     │
    └───────────┬─────────────┘
                │
                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                      FOR EACH SAMPLE ITEM                            │
└─────────────────────────────────────────────────────────────────────┘
                │
    ┌───────────┴───────────┐
    │                       │
    ▼                       ▼
┌───────────────┐    ┌───────────────┐
│ PARTICIPANT   │    │ EMPLOYER      │
│ DEFERRALS     │    │ CONTRIBUTIONS │
└───────┬───────┘    └───────┬───────┘
        │                    │
        ▼                    ▼
┌───────────────┐    ┌───────────────┐
│ a. Verify     │    │ a. Understand │
│    election % │    │    formula    │
│                    │    (match,    │
│ b. Trace to   │    │    profit     │
│    payroll    │    │    sharing)   │
│                    │               │
│ c. Recalculate│    │ b. Recalculate│
│    deferral   │    │    per formula│
│    amount     │    │               │
│               │    │ c. Verify     │
│ d. Verify     │    │    allocation │
│    posting    │    │    to account │
└───────┬───────┘    └───────┬───────┘
        │                    │
        └────────┬───────────┘
                 │
                 ▼
    ┌─────────────────────────┐
    │ 4. TEST TIMELINESS      │
    └───────────┬─────────────┘
                │
                ▼
    ┌─────────────────────────┐
    │ Days from pay date to   │
    │ deposit in trust?       │
    └───────────┬─────────────┘
                │
    ┌───────────┴───────────┐
    │                       │
    ▼                       ▼
┌───────────────┐    ┌───────────────┐
│ ≤ 7 business  │    │ > 7 business  │
│ days          │    │ days          │
│ (Safe Harbor) │    │               │
└───────┬───────┘    └───────┬───────┘
        │                    │
        ▼                    ▼
┌───────────────┐    ┌───────────────┐
│ TIMELY        │    │ EVALUATE      │
│ (Document)    │    │ (See Late     │
└───────────────┘    │ Contribution  │
                     │ Decision Tree)│
                     └───────────────┘
```

---

## Distribution Testing Flow

```
┌─────────────────────────────────────────────────────────────────────┐
│                     DISTRIBUTION TESTING FLOW                        │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ 1. OBTAIN POPULATION    │
                    │ All distributions for   │
                    │ the plan year           │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ 2. RECONCILE TO TRUST   │
                    │ AND FORM 5500           │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ 3. SELECT SAMPLE        │
                    └───────────┬─────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    FOR EACH DISTRIBUTION                             │
└─────────────────────────────────────────────────────────────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ A. VERIFY ELIGIBILITY   │
                    │                         │
                    │ What triggered the      │
                    │ distribution?           │
                    └───────────┬─────────────┘
                                │
    ┌───────────┬───────────────┼───────────────┬───────────────┐
    │           │               │               │               │
    ▼           ▼               ▼               ▼               ▼
┌────────┐ ┌────────┐     ┌────────┐     ┌────────┐     ┌────────┐
│TERMIN- │ │RETIRE- │     │DEATH   │     │HARDSHIP│     │IN-     │
│ATION   │ │MENT    │     │        │     │        │     │SERVICE │
└───┬────┘ └───┬────┘     └───┬────┘     └───┬────┘     └───┬────┘
    │          │              │              │              │
    ▼          ▼              ▼              ▼              ▼
┌────────┐ ┌────────┐   ┌──────────┐   ┌──────────┐   ┌──────────┐
│Verify  │ │Verify  │   │Verify    │   │Verify    │   │Verify age│
│term    │ │retire- │   │death     │   │hardship  │   │and plan  │
│date    │ │ment    │   │certif.   │   │documen-  │   │allows    │
│in HR   │ │date/age│   │& benefi- │   │tation    │   │          │
│records │ │        │   │ciary     │   │meets IRS │   │          │
└───┬────┘ └───┬────┘   └────┬─────┘   │safe      │   └────┬─────┘
    │          │             │         │harbor    │        │
    └──────────┴─────────────┴─────────┴──────────┴────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ B. VERIFY AUTHORIZATION │
                    │                         │
                    │ □ Signed distribution   │
                    │   form on file?         │
                    │ □ Spousal consent       │
                    │   (if required)?        │
                    │ □ Proper approvals?     │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ C. VERIFY VESTING       │
                    │                         │
                    │ □ Calculate YOS         │
                    │ □ Apply vesting sched   │
                    │ □ Verify vested balance │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ D. VERIFY CALCULATION   │
                    │                         │
                    │ □ Vested balance        │
                    │ □ Outstanding loans     │
                    │ □ Net distribution      │
                    │ □ Tax withholding       │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ E. VERIFY 1099-R        │
                    │                         │
                    │ □ Matches distribution  │
                    │ □ Proper code used      │
                    │ □ Withholding reported  │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────┐
                    │ F. DOCUMENT RESULTS     │
                    └─────────────────────────┘
```

---

## Compliance Testing Decision Tree

### Which Tests Are Required?

```
┌─────────────────────────────────────────────────────────────────────┐
│                 COMPLIANCE TESTING REQUIREMENTS                      │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Is the plan a SAFE      │
                    │ HARBOR 401(k)?          │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │   YES   │                     │   NO    │
           └────┬────┘                     └────┬────┘
                │                               │
                ▼                               ▼
    ┌─────────────────────┐        ┌─────────────────────┐
    │ EXEMPT FROM:        │        │ ALL TESTS REQUIRED: │
    │ □ ADP Test          │        │ □ ADP Test          │
    │ □ ACP Test          │        │ □ ACP Test          │
    │ □ Top-Heavy (if     │        │ □ Top-Heavy Test    │
    │   3% non-elective)  │        │ □ Coverage (410b)   │
    │                     │        │ □ 415 Limits        │
    │ STILL REQUIRED:     │        │ □ 401(a)(17) Limit  │
    │ □ Coverage (410b)   │        │                     │
    │ □ 415 Limits        │        │                     │
    │ □ 401(a)(17) Limit  │        │                     │
    └─────────────────────┘        └─────────────────────┘

                        ┌───────────────────────────┐
                        │     TOP-HEAVY TEST        │
                        └─────────────┬─────────────┘
                                      │
                                      ▼
                        ┌─────────────────────────────┐
                        │ Key Employee accounts       │
                        │ > 60% of total plan assets? │
                        └─────────────┬───────────────┘
                                      │
                      ┌───────────────┴───────────────┐
                      │                               │
                      ▼                               ▼
                 ┌─────────┐                     ┌─────────┐
                 │   YES   │                     │   NO    │
                 │TOP-HEAVY│                     │NOT TOP- │
                 └────┬────┘                     │HEAVY    │
                      │                          └─────────┘
                      ▼
           ┌─────────────────────────┐
           │ Minimum contribution    │
           │ required for non-key    │
           │ employees (3% of comp)  │
           └─────────────────────────┘
```

---

## ADP/ACP Test Failure Response

```
┌─────────────────────────────────────────────────────────────────────┐
│                  ADP/ACP TEST FAILURE RESPONSE                       │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Did the plan FAIL the   │
                    │ ADP or ACP test?        │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │ PASSED  │                     │ FAILED  │
           │         │                     │         │
           │Document │                     └────┬────┘
           │results  │                          │
           └─────────┘                          ▼
                              ┌──────────────────────────────┐
                              │ CORRECTION OPTIONS:          │
                              │                              │
                              │ ① Distribute excess to HCEs  │
                              │ ② Make QNEC to NHCEs         │
                              │ ③ Combination of both        │
                              │ ④ Recharacterize (if allowed)│
                              └──────────────┬───────────────┘
                                             │
                                             ▼
                    ┌─────────────────────────────────────────────┐
                    │             CORRECTION DEADLINES            │
                    └─────────────────────────────────────────────┘
                                             │
         ┌───────────────────────────────────┴───────────────────┐
         │                                                       │
         ▼                                                       ▼
┌─────────────────────────┐                     ┌─────────────────────────┐
│   CORRECTIVE            │                     │   QNEC                  │
│   DISTRIBUTION          │                     │   CONTRIBUTION          │
│                         │                     │                         │
│   Deadline:             │                     │   Deadline:             │
│   2½ months after       │                     │   12 months after       │
│   plan year end         │                     │   plan year end         │
│   (March 15 for         │                     │   (Dec 31 for           │
│   calendar year)        │                     │   calendar year)        │
│                         │                     │                         │
│   Tax consequences:     │                     │   Employer deduction:   │
│   - Taxable to HCE      │                     │   - Deductible when     │
│   - 10% excise tax      │                     │     contributed         │
│     if late             │                     │                         │
└─────────────────────────┘                     └─────────────────────────┘
                                             │
                                             ▼
                    ┌─────────────────────────────────────────────┐
                    │     WHAT IF DEADLINE IS MISSED?             │
                    │                                             │
                    │  ► File under VCP (Voluntary Correction     │
                    │    Program) with IRS                        │
                    │  ► Pay applicable user fee                  │
                    │  ► Complete correction per IRS guidance     │
                    └─────────────────────────────────────────────┘
```

---

## Audit Finding Classification

### Classifying Internal Control Deficiencies

```
┌─────────────────────────────────────────────────────────────────────┐
│              INTERNAL CONTROL DEFICIENCY EVALUATION                  │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Is there a deficiency   │
                    │ in internal control?    │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │   NO    │                     │   YES   │
           │         │                     │         │
           │(Document│                     └────┬────┘
           │  clean) │                          │
           └─────────┘                          │
                                                ▼
                              ┌────────────────────────────────────┐
                              │ Evaluate LIKELIHOOD of misstatement│
                              │                                    │
                              │ Could the deficiency result in a   │
                              │ misstatement?                      │
                              └─────────────────┬──────────────────┘
                                                │
                    ┌───────────────────────────┼───────────────────┐
                    │                           │                   │
                    ▼                           ▼                   ▼
           ┌────────────────┐        ┌────────────────┐    ┌────────────────┐
           │ Remote         │        │ Reasonably     │    │ More than      │
           │ likelihood     │        │ possible       │    │ remote         │
           └───────┬────────┘        └────────┬───────┘    └────────┬───────┘
                   │                          │                     │
                   ▼                          │                     │
           ┌────────────────┐                 │                     │
           │ Deficiency     │                 │                     │
           │ (no further    │                 │                     │
           │ classification)│                 │                     │
           └────────────────┘                 │                     │
                                              ▼                     │
                              ┌────────────────────────────────────┐│
                              │ Evaluate MAGNITUDE of potential   ││
                              │ misstatement                      ││
                              └─────────────────┬─────────────────┘│
                                                │                  │
                    ┌───────────────────────────┴─────────┐        │
                    │                                     │        │
                    ▼                                     ▼        ▼
           ┌────────────────┐                    ┌────────────────────────┐
           │ Could result   │                    │ Could result in        │
           │ in MORE than   │                    │ misstatement that is   │
           │ inconsequential│                    │ MATERIAL               │
           │ misstatement   │                    │                        │
           └───────┬────────┘                    └───────────┬────────────┘
                   │                                         │
                   ▼                                         ▼
          ┌─────────────────────┐              ┌─────────────────────────┐
          │ SIGNIFICANT         │              │ MATERIAL WEAKNESS       │
          │ DEFICIENCY          │              │                         │
          │                     │              │ Requires written        │
          │ Communicate in      │              │ communication to those  │
          │ writing to those    │              │ charged with governance │
          │ charged with        │              │                         │
          │ governance          │              │ Consider impact on      │
          └─────────────────────┘              │ audit opinion           │
                                               └─────────────────────────┘
```

---

## Opinion Modification Decisions

### Determining the Appropriate Audit Opinion

```
┌─────────────────────────────────────────────────────────────────────┐
│                    AUDIT OPINION DECISION TREE                       │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Is this a LIMITED SCOPE │
                    │ audit?                  │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │   YES   │                     │   NO    │
           └────┬────┘                     │(Full    │
                │                          │ Scope)  │
                ▼                          └────┬────┘
    ┌─────────────────────┐                     │
    │ Issue DISCLAIMER on │                     │
    │ F/S as a whole      │                     │
    │                     │                     │
    │ BUT: Report on      │                     │
    │ procedures applied  │                     │
    │ and compliance with │                     │
    │ DOL requirements    │                     │
    └──────────┬──────────┘                     │
               │                                │
               └────────────────┬───────────────┘
                                │
                                ▼
                  ┌───────────────────────────────┐
                  │ Are there MATERIAL            │
                  │ misstatements in the          │
                  │ financial statements?         │
                  └───────────────┬───────────────┘
                                  │
                  ┌───────────────┴───────────────┐
                  │                               │
                  ▼                               ▼
             ┌─────────┐                     ┌─────────┐
             │   NO    │                     │   YES   │
             └────┬────┘                     └────┬────┘
                  │                               │
                  ▼                               ▼
     ┌────────────────────────┐    ┌────────────────────────────┐
     │ Is there a SCOPE       │    │ Are the misstatements      │
     │ LIMITATION?            │    │ PERVASIVE?                 │
     └────────────┬───────────┘    └─────────────┬──────────────┘
                  │                              │
      ┌───────────┴───────────┐      ┌───────────┴───────────┐
      │                       │      │                       │
      ▼                       ▼      ▼                       ▼
 ┌─────────┐             ┌─────────┐ ┌─────────┐       ┌─────────┐
 │   NO    │             │   YES   │ │   NO    │       │   YES   │
 └────┬────┘             └────┬────┘ └────┬────┘       └────┬────┘
      │                       │           │                 │
      ▼                       ▼           ▼                 ▼
┌──────────────┐   ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│ UNMODIFIED   │   │ Is limitation│ │ QUALIFIED    │ │ ADVERSE      │
│ OPINION      │   │ pervasive?   │ │ OPINION      │ │ OPINION      │
│              │   └──────┬───────┘ │              │ │              │
│ (Clean)      │          │         │ "Except for" │ │ F/S do NOT   │
│              │    ┌─────┴─────┐   │ language     │ │ present      │
└──────────────┘    │           │   │              │ │ fairly       │
                    ▼           ▼   └──────────────┘ └──────────────┘
               ┌────────┐  ┌────────┐
               │   NO   │  │   YES  │
               └────┬───┘  └────┬───┘
                    │           │
                    ▼           ▼
             ┌──────────────┐ ┌──────────────┐
             │ QUALIFIED    │ │ DISCLAIMER   │
             │ OPINION      │ │ OF OPINION   │
             │              │ │              │
             │ "Except for" │ │ Unable to    │
             │ scope        │ │ express      │
             │ limitation   │ │ opinion      │
             └──────────────┘ └──────────────┘
```

---

## Late Contribution Evaluation

```
┌─────────────────────────────────────────────────────────────────────┐
│                 LATE CONTRIBUTION DECISION TREE                      │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Calculate days from     │
                    │ PAYDAY to DEPOSIT       │
                    │ in trust                │
                    └───────────┬─────────────┘
                                │
        ┌───────────────────────┼───────────────────────┐
        │                       │                       │
        ▼                       ▼                       ▼
   ┌─────────┐            ┌─────────┐            ┌─────────┐
   │ 1-3     │            │ 4-7     │            │ > 7     │
   │ business│            │ business│            │ business│
   │ days    │            │ days    │            │ days    │
   └────┬────┘            └────┬────┘            └────┬────┘
        │                      │                      │
        ▼                      ▼                      ▼
   ┌─────────────┐       ┌─────────────┐       ┌─────────────────┐
   │ TIMELY      │       │ EVALUATE    │       │ PRESUMED LATE   │
   │             │       │             │       │                 │
   │ Document &  │       │ Consider:   │       │ Unless client   │
   │ no further  │       │ - Plan size │       │ can demonstrate │
   │ action      │       │ - Payroll   │       │ earliest date   │
   │ required    │       │   frequency │       │ was not         │
   │             │       │ - Process   │       │ reasonably      │
   │             │       │   complexity│       │ possible        │
   └─────────────┘       └──────┬──────┘       └────────┬────────┘
                                │                       │
                    ┌───────────┴───────────┐           │
                    │                       │           │
                    ▼                       ▼           │
               ┌─────────┐            ┌─────────┐       │
               │JUSTIFIED│            │  LATE   │◄──────┘
               │         │            │         │
               └────┬────┘            └────┬────┘
                    │                      │
                    ▼                      ▼
               ┌─────────────┐    ┌─────────────────────────────┐
               │ Document    │    │ LATE CONTRIBUTION           │
               │ reasoning   │    │ CONSEQUENCES:               │
               │             │    │                             │
               │ No further  │    │ 1. Calculate lost earnings  │
               │ action      │    │    (DOL calculator)         │
               │             │    │                             │
               │             │    │ 2. Deposit lost earnings    │
               │             │    │    to affected accounts     │
               │             │    │                             │
               │             │    │ 3. Report on Schedule of    │
               │             │    │    Delinquent Contributions │
               │             │    │                             │
               │             │    │ 4. Consider VFCP filing     │
               │             │    │                             │
               │             │    │ 5. Prohibited transaction?  │
               └─────────────┘    │    (if not corrected)       │
                                  └─────────────────────────────┘
```

---

## Participant Loan Compliance

```
┌─────────────────────────────────────────────────────────────────────┐
│                    PARTICIPANT LOAN TESTING                          │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Does plan allow loans?  │
                    └───────────┬─────────────┘
                                │
                ┌───────────────┴───────────────┐
                │                               │
                ▼                               ▼
           ┌─────────┐                     ┌─────────┐
           │   NO    │                     │   YES   │
           └────┬────┘                     └────┬────┘
                │                               │
                ▼                               │
    ┌─────────────────────┐                     │
    │ N/A - Document      │                     │
    │ no loans allowed    │                     │
    └─────────────────────┘                     │
                                                ▼
                              ┌────────────────────────────────────┐
                              │        FOR EACH SAMPLED LOAN       │
                              └─────────────────┬──────────────────┘
                                                │
    ┌───────────────────────────────────────────┴───────────────────┐
    │                           │                                   │
    ▼                           ▼                                   ▼
┌─────────────┐          ┌─────────────┐                  ┌─────────────┐
│ AMOUNT TEST │          │ TERM TEST   │                  │ REPAYMENT   │
│             │          │             │                  │ TEST        │
│ Maximum =   │          │ Maximum 5   │                  │             │
│ LESSER of:  │          │ years       │                  │ Level       │
│             │          │ (or longer  │                  │ amortization│
│ • 50% of    │          │  for home   │                  │ required    │
│   vested    │          │  purchase)  │                  │ (quarterly  │
│   balance   │          │             │                  │  at minimum)│
│             │          │             │                  │             │
│ • $50,000*  │          └──────┬──────┘                  └──────┬──────┘
│             │                 │                                │
└──────┬──────┘                 │                                │
       │                        │                                │
       ▼                        ▼                                ▼
┌─────────────────┐    ┌─────────────────┐             ┌─────────────────┐
│ *$50,000 reduced│    │ Is loan term    │             │ Are payments    │
│  by highest     │    │ ≤ 5 years?      │             │ level and at    │
│  outstanding    │    │ (or proper home │             │ least quarterly?│
│  loan in past   │    │  exception)     │             │                 │
│  12 months      │    │                 │             │                 │
└────────┬────────┘    └────────┬────────┘             └────────┬────────┘
         │                      │                               │
  ┌──────┴──────┐       ┌───────┴───────┐              ┌────────┴───────┐
  │             │       │               │              │                │
  ▼             ▼       ▼               ▼              ▼                ▼
┌────┐        ┌────┐  ┌────┐          ┌────┐        ┌────┐           ┌────┐
│PASS│        │FAIL│  │PASS│          │FAIL│        │PASS│           │FAIL│
└──┬─┘        └──┬─┘  └──┬─┘          └──┬─┘        └──┬─┘           └──┬─┘
   │             │       │               │             │                │
   │             │       │               │             │                │
   └─────────────┴───────┴───────────────┴─────────────┴────────────────┘
                                         │
                                         ▼
                               ┌───────────────────┐
                               │ ANY FAILURES?     │
                               └─────────┬─────────┘
                                         │
                         ┌───────────────┴───────────────┐
                         │                               │
                         ▼                               ▼
                    ┌─────────┐                     ┌─────────┐
                    │   NO    │                     │   YES   │
                    │         │                     │         │
                    │Document │                     └────┬────┘
                    │clean    │                          │
                    └─────────┘                          ▼
                                          ┌────────────────────────────┐
                                          │ DEEMED DISTRIBUTION        │
                                          │ (Prohibited Transaction)   │
                                          │                            │
                                          │ • Taxable to participant   │
                                          │ • 10% penalty if < 59½     │
                                          │ • Report on Form 1099-R    │
                                          │ • Report on Schedule G     │
                                          └────────────────────────────┘
```

---

## Prohibited Transaction Identification

```
┌─────────────────────────────────────────────────────────────────────┐
│              PROHIBITED TRANSACTION IDENTIFICATION                   │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Is there a transaction  │
                    │ with a PARTY-IN-        │
                    │ INTEREST?               │
                    └───────────┬─────────────┘
                                │
                                ▼
                    ┌─────────────────────────────────────────────────┐
                    │ PARTIES-IN-INTEREST include:                    │
                    │                                                 │
                    │ • Fiduciaries                                   │
                    │ • Service providers                             │
                    │ • Employer (plan sponsor)                       │
                    │ • Employees organizations                       │
                    │ • 50% owners                                    │
                    │ • Relatives of above                            │
                    │ • Entities owned/controlled by above            │
                    └─────────────────────────┬───────────────────────┘
                                              │
                              ┌───────────────┴───────────────┐
                              │                               │
                              ▼                               ▼
                         ┌─────────┐                     ┌─────────┐
                         │   NO    │                     │   YES   │
                         │         │                     │         │
                         │Not PT   │                     └────┬────┘
                         └─────────┘                          │
                                                              ▼
                                            ┌────────────────────────────┐
                                            │ Is the transaction one of: │
                                            │                            │
                                            │ □ Sale/exchange of property│
                                            │ □ Loan or extension of     │
                                            │   credit                   │
                                            │ □ Furnishing goods/services│
                                            │ □ Transfer of plan assets  │
                                            │ □ Use of plan assets by/   │
                                            │   for party-in-interest    │
                                            └─────────────┬──────────────┘
                                                          │
                                          ┌───────────────┴───────────────┐
                                          │                               │
                                          ▼                               ▼
                                     ┌─────────┐                     ┌─────────┐
                                     │   NO    │                     │   YES   │
                                     │         │                     │         │
                                     │Not PT   │                     └────┬────┘
                                     └─────────┘                          │
                                                                          ▼
                                                        ┌────────────────────────────┐
                                                        │ Does an EXEMPTION apply?   │
                                                        └─────────────┬──────────────┘
                                                                      │
                                          ┌───────────────────────────┴──────────────┐
                                          │                                          │
                                          ▼                                          ▼
    ┌─────────────────────────────────────────────────────────────┐            ┌─────────┐
    │                    COMMON EXEMPTIONS                         │            │   NO    │
    │                                                              │            │EXEMPTION│
    │ □ 408(b)(1): Loans to participants (if meets requirements)   │            └────┬────┘
    │ □ 408(b)(2): Reasonable compensation for services            │                 │
    │ □ 408(b)(8): Purchase of employer securities (limitations)   │                 │
    │ □ 408(c)(2): Reasonable compensation for fiduciaries         │                 │
    │ □ 408(e):   Receipt of benefits as a participant             │                 │
    │ □ Class exemptions (e.g., PTEs for specific transactions)    │                 │
    └─────────────────────────────────┬────────────────────────────┘                 │
                                      │                                              │
                      ┌───────────────┴───────────────┐                              │
                      │                               │                              │
                      ▼                               ▼                              ▼
                 ┌─────────┐                     ┌─────────┐              ┌─────────────────┐
                 │EXEMPTION│                     │EXEMPTION│              │ PROHIBITED      │
                 │APPLIES  │                     │ DOES    │              │ TRANSACTION     │
                 │         │                     │ NOT     │              │                 │
                 │Document │                     │ APPLY   │              │ • Report on     │
                 │exemption│                     └────┬────┘              │   Schedule G    │
                 │relied on│                          │                   │ • Excise tax    │
                 └─────────┘                          │                   │   under IRC 4975│
                                                      │                   │ • Correction    │
                                                      └─────────────────► │   required      │
                                                                          └─────────────────┘
```

---

## Form 5500 Reconciliation

```
┌─────────────────────────────────────────────────────────────────────┐
│                    FORM 5500 RECONCILIATION                          │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────────────────────────────┐
                    │         COMPARE AUDITED F/S TO FORM 5500        │
                    └─────────────────────────┬───────────────────────┘
                                              │
    ┌─────────────────────────────────────────┴─────────────────────────┐
    │                             │                                     │
    ▼                             ▼                                     ▼
┌───────────────┐         ┌───────────────┐                   ┌───────────────┐
│ NET ASSETS    │         │ CONTRIBUTIONS │                   │ BENEFITS PAID │
│               │         │               │                   │               │
│ F/S Net Assets│         │ F/S Total     │                   │ F/S Benefits  │
│     vs        │         │ Contributions │                   │ Paid          │
│ 5500 Line 1   │         │     vs        │                   │     vs        │
│               │         │ 5500 Sch H    │                   │ 5500 Sch H    │
│               │         │ Line 2a + 2b  │                   │ Line 2e       │
└───────┬───────┘         └───────┬───────┘                   └───────┬───────┘
        │                         │                                   │
        ▼                         ▼                                   ▼
┌──────────────┐          ┌──────────────┐                    ┌──────────────┐
│   AGREE?     │          │   AGREE?     │                    │   AGREE?     │
└──────┬───────┘          └──────┬───────┘                    └──────┬───────┘
       │                         │                                   │
   ┌───┴───┐                 ┌───┴───┐                           ┌───┴───┐
   │       │                 │       │                           │       │
   ▼       ▼                 ▼       ▼                           ▼       ▼
 ┌───┐   ┌───┐             ┌───┐   ┌───┐                       ┌───┐   ┌───┐
 │YES│   │NO │             │YES│   │NO │                       │YES│   │NO │
 └─┬─┘   └─┬─┘             └─┬─┘   └─┬─┘                       └─┬─┘   └─┬─┘
   │       │                 │       │                           │       │
   ▼       │                 ▼       │                           ▼       │
  ┌─┐      │                ┌─┐      │                          ┌─┐      │
  │✓│      │                │✓│      │                          │✓│      │
  └─┘      │                └─┘      │                          └─┘      │
           ▼                         ▼                                   ▼
    ┌──────────────────────────────────────────────────────────────────────┐
    │                        DIFFERENCES NOTED                              │
    │                                                                       │
    │   COMMON RECONCILING ITEMS:                                           │
    │                                                                       │
    │   1. Timing differences (contributions in transit)                    │
    │   2. Classification differences (loans as investments vs receivables)│
    │   3. Benefit payments vs distributions (include corrective distrib.) │
    │   4. Transfer activity (plan-to-plan transfers)                       │
    │   5. Deemed distributions (defaulted loans)                           │
    └──────────────────────────────────┬───────────────────────────────────┘
                                       │
                                       ▼
                         ┌─────────────────────────────────┐
                         │ Can ALL differences be          │
                         │ explained and documented?       │
                         └───────────────┬─────────────────┘
                                         │
                         ┌───────────────┴───────────────┐
                         │                               │
                         ▼                               ▼
                    ┌─────────┐                     ┌─────────┐
                    │   YES   │                     │   NO    │
                    │         │                     │         │
                    │Document │                     └────┬────┘
                    │recon    │                          │
                    │note     │                          ▼
                    └─────────┘              ┌─────────────────────────┐
                                             │ INVESTIGATE             │
                                             │                         │
                                             │ • Error in F/S?         │
                                             │ • Error in Form 5500?   │
                                             │ • Request correction    │
                                             │ • Document resolution   │
                                             └─────────────────────────┘
```

---

## First-Year Audit Decision Flow

```
┌─────────────────────────────────────────────────────────────────────┐
│                     FIRST-YEAR AUDIT DECISIONS                       │
└─────────────────────────────────────────────────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │ Why is this a           │
                    │ first-year audit?       │
                    └───────────┬─────────────┘
                                │
    ┌───────────────────────────┼───────────────────────────┐
    │                           │                           │
    ▼                           ▼                           ▼
┌─────────────┐         ┌─────────────┐             ┌─────────────┐
│ NEW PLAN    │         │ FIRST AUDIT │             │ CHANGE OF   │
│             │         │ AFTER       │             │ AUDITORS    │
│ Plan was    │         │ GROWTH      │             │             │
│ established │         │             │             │ New auditor │
│ and hit     │         │ Exceeded    │             │ replacing   │
│ audit       │         │ 100         │             │ predecessor │
│ threshold   │         │ threshold   │             │             │
└──────┬──────┘         └──────┬──────┘             └──────┬──────┘
       │                       │                           │
       ▼                       ▼                           ▼
┌──────────────────┐  ┌──────────────────┐    ┌──────────────────────┐
│ UNIQUE           │  │ UNIQUE           │    │ UNIQUE               │
│ CONSIDERATIONS:  │  │ CONSIDERATIONS:  │    │ CONSIDERATIONS:      │
│                  │  │                  │    │                      │
│ □ No prior audit │  │ □ May have       │    │ □ Contact            │
│ □ No opening     │  │   unaudited      │    │   predecessor        │
│   balance audit  │  │   prior years    │    │ □ Review prior       │
│ □ Verify plan    │  │ □ Opening        │    │   workpapers         │
│   qualified      │  │   balances from  │    │ □ Understand reason  │
│ □ Test from      │  │   prior Form     │    │   for change         │
│   inception      │  │   5500           │    │ □ Prior year         │
│                  │  │ □ Consider prior │    │   workpapers         │
│                  │  │   year testing   │    │   available          │
└────────┬─────────┘  └────────┬─────────┘    └──────────┬───────────┘
         │                     │                         │
         └─────────────────────┴─────────────────────────┘
                                  │
                                  ▼
                    ┌─────────────────────────────────────┐
                    │      OPENING BALANCE PROCEDURES     │
                    └─────────────────┬───────────────────┘
                                      │
                                      ▼
                    ┌─────────────────────────────────────────────────┐
                    │ 1. Obtain prior year financial statements      │
                    │    (audited or unaudited)                      │
                    │                                                 │
                    │ 2. Reconcile opening balances to:               │
                    │    • Prior year closing balances                │
                    │    • Prior year Form 5500                       │
                    │    • Trust statements                           │
                    │                                                 │
                    │ 3. For NEW PLANS: Verify initial contributions  │
                    │    and participant accounts from inception      │
                    │                                                 │
                    │ 4. For PREDECESSOR AUDITS: Review prior year    │
                    │    workpapers if access granted                 │
                    │                                                 │
                    │ 5. Perform substantive testing on opening       │
                    │    balances sufficient to support opinion       │
                    └─────────────────────────────────────────────────┘
                                      │
                                      ▼
                    ┌─────────────────────────────────────┐
                    │ Can opening balances be verified    │
                    │ to auditor's satisfaction?          │
                    └─────────────────┬───────────────────┘
                                      │
                      ┌───────────────┴───────────────┐
                      │                               │
                      ▼                               ▼
                 ┌─────────┐                     ┌─────────┐
                 │   YES   │                     │   NO    │
                 │         │                     │         │
                 │Proceed  │                     └────┬────┘
                 │with     │                          │
                 │audit    │                          ▼
                 └─────────┘              ┌─────────────────────────┐
                                          │ Consider:               │
                                          │                         │
                                          │ • Expanded procedures   │
                                          │ • Scope limitation      │
                                          │ • Qualified opinion     │
                                          │ • Decline engagement    │
                                          └─────────────────────────┘
```

---

## Quick Reference: Decision Tree Index

| Decision Area | Key Question | See Section |
|--------------|--------------|-------------|
| Audit Required? | 100+ eligible participants? | [Audit Requirement](#audit-requirement-decision-tree) |
| Limited vs Full Scope | Valid certification available? | [Limited vs Full](#limited-scope-vs-full-scope) |
| Valid Certification | Meets all DOL requirements? | [Certification Evaluation](#certification-evaluation) |
| Late Contribution | > 7 business days from payday? | [Late Contribution](#late-contribution-evaluation) |
| Loan Compliance | Meets 72(p) requirements? | [Loan Compliance](#participant-loan-compliance) |
| Prohibited Transaction | Transaction with party-in-interest? | [PT Identification](#prohibited-transaction-identification) |
| Finding Classification | Material weakness or significant deficiency? | [Finding Classification](#audit-finding-classification) |
| Opinion Type | Any modifications needed? | [Opinion Modification](#opinion-modification-decisions) |
| First-Year Audit | What additional procedures needed? | [First-Year Audit](#first-year-audit-decision-flow) |

---

## Document History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2024 | Initial release |

---

*These flowcharts are designed as quick reference guides. Professional judgment should always be applied when making audit decisions. Consult firm guidance and professional standards for complex situations.*
