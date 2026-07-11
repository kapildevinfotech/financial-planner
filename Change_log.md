# Changelog

## Family Wealth Operating System (FWOS)

All material changes to the FWOS strategy, governance framework, architecture, and major financial assumptions are documented here.

This project follows a simplified form of Semantic Versioning:

* **Major:** Fundamental strategy or architecture change
* **Minor:** New policy, framework, or capability
* **Patch:** Correction, clarification, or non-material update

---

# [3.0.0] — July 2026

## Added

### Family Wealth Operating System

Established FWOS as the family's long-term financial governance framework.

The system is designed to integrate:

* Family goals
* Financial independence
* Children's education
* Portfolio management
* Asset allocation
* Risk management
* Business optionality
* Insurance
* Tax efficiency
* Estate planning
* Behavioural governance
* AI-assisted decision support

### Reason

The family's financial position had become sufficiently complex that isolated investment decisions were no longer an adequate planning approach.

A unified operating system was required.

---

## Added — Source-of-Truth Architecture

Established the following hierarchy:

1. `FWOS_MASTER.md`
2. `FAMILY_PROFILE.md`
3. Structured data under `/data`
4. Annual historical snapshots
5. Generated dashboards, reports, and HTML documentation

### Reason

To separate:

* Stable policy
* Changing family facts
* Machine-readable data
* Historical records
* Presentation layers

---

## Added — FWOS Master Constitution

Created `FWOS_MASTER.md`.

The document governs:

* Investment philosophy
* Strategic asset allocation
* Capital allocation
* Equity policy
* International investing
* Gold
* Debt
* Liquidity
* Business capital
* Real estate
* Insurance
* Rebalancing
* Market-crash behaviour
* AI usage
* Governance
* Change control

---

## Added — Family Profile

Created `FAMILY_PROFILE.md`.

The profile records:

* Family structure
* Income
* Expenses
* Current assets
* Real estate
* Family liquidity
* Insurance
* Education goals
* Financial independence
* Business aspirations
* Risk profile
* Known planning gaps

---

## Decision — Index-First Investment Philosophy

### New Policy

The core equity portfolio will follow an index-first philosophy.

Directional preference:

* Approximately 75–80% passive equity
* Approximately 20–25% active equity where justified

### Reason

To improve:

* Cost efficiency
* Simplicity
* Transparency
* Long-term consistency
* Behavioural discipline

Active funds remain permitted where they provide a clearly defined and justified role.

---

## Decision — Strategic Asset Allocation Framework

### Initial Strategic Target

| Asset Class                | Target |
| -------------------------- | -----: |
| Indian Equity              |    55% |
| International Equity       |    10% |
| Gold                       |     7% |
| Debt                       |    23% |
| Cash / Opportunity Capital |     5% |

### Approved Ranges

| Asset Class                | Minimum | Maximum |
| -------------------------- | ------: | ------: |
| Indian Equity              |     50% |     60% |
| International Equity       |      8% |     12% |
| Gold                       |      5% |     10% |
| Debt                       |     20% |     30% |
| Cash / Opportunity Capital |      3% |      8% |

### Status

**Provisional**

The allocation must be validated against:

* Goal corpus calculations
* Current portfolio composition
* Education requirements
* Retirement requirements
* Business optionality
* Liquidity needs

---

## Decision — Total Equity Risk Range

### Policy

Preferred total equity exposure:

**Approximately 50–65%**

Total equity must include:

* Indian equity
* International equity
* Direct stocks
* ETFs
* Mutual funds
* NPS equity allocation

### Reason

To prevent underestimating risk by viewing accounts separately.

---

## Decision — International Diversification

### Policy

International equity will form a strategic component of the portfolio.

Preferred approach:

* Broad global or developed-market exposure
* Select US exposure where appropriate

### Reason

To provide:

* Geographic diversification
* Currency diversification
* Access to businesses outside India
* Reduced single-country concentration

International investing will not automatically mean concentrated Nasdaq exposure.

---

## Decision — Gold Allocation

### Policy

Gold will be treated as a strategic diversifier.

Target:

**Approximately 7%**

Approved range:

**5–10%**

### Reason

Gold may contribute:

* Portfolio diversification
* Crisis resilience
* Partial inflation and currency protection

The user currently prefers physical gold but is open to evaluating ETFs and mutual-fund structures.

---

## Decision — Opportunity Fund

### Policy

Maintain an optional opportunity-capital reserve.

Indicative size:

**₹5–10 lakh**

Potential deployment during meaningful broad-market corrections.

### Important Separation

The opportunity fund is not the emergency fund.

### Reason

To provide deployable capital during market stress without disrupting regular SIPs or emergency liquidity.

---

## Decision — Mother's Assets Tracked Separately

### Context

Approximately ₹80 lakh is held in the mother's savings account.

Family finances are practically interconnected, and the user manages these assets.

### Policy

For FWOS purposes, the mother's assets will be tracked separately from the user's personal net worth.

### Reason

To maintain clarity regarding:

* Legal ownership
* Taxation
* Succession
* Goal attribution
* Liquidity

Family support may still be considered in resilience analysis.

---

## Decision — Lucknow Plot Funding

### Previous Assumption

The proposed Lucknow plot was initially considered as potentially using the user's investment capital.

### Revised Decision

Approximately ₹40 lakh for the proposed Lucknow plot is expected to come from the mother's existing ₹80 lakh savings.

### Consequence

The planned plot purchase should not automatically reduce the user's core long-term investment corpus.

---

## Decision — Children's Education as Top Financial Goal

### Goals

#### Reyansh

* Graduation: approximately 12 years
* Master's / postgraduate education: approximately 15 years

#### Nikesh

* Graduation: approximately 15 years
* Master's / postgraduate education: approximately 18 years

### Planning Scope

Potentially includes:

* IIT
* NIT
* Strong government institutions
* Top private institutions
* Foreign postgraduate education

### Status

Goal corpus calculations remain pending.

---

## Decision — Financial Independence Framework

### Directional Objective

Create the option of financial independence around age 55.

### Flexibility

The user may:

* Continue working in IT
* Transition into business
* Work part-time
* Retire earlier or later

### Reason

Financial independence is treated as optionality rather than a mandatory retirement date.

---

## Decision — Business Optionality

### Objective

Potential future non-IT business.

Possible areas include healthcare-related businesses such as:

* Diagnostic services
* Ultrasound centre
* Pharmacy
* Other resilient non-IT businesses

### Indicative Capital

**₹30–50 lakh**

### Policy

Business capital should not jeopardize:

* Children's essential education
* Retirement security
* Emergency liquidity

---

## Decision — Conservative Income Growth Assumption

### Assumption

Long-term income growth for planning:

**Approximately 5% annually**

### Reason

To account conservatively for:

* AI disruption
* Technology-sector uncertainty
* Career transitions

Higher actual income growth should improve the plan rather than being required for success.

---

## Decision — Monthly Investment Capacity

### Current Capacity

Approximately:

**₹1.25 lakh per month**

### Policy

Monthly surplus will be allocated across relevant asset classes rather than automatically directed entirely to equity.

Exact SIP deployment remains pending.

---

## Decision — Family Lifestyle Planning

### Current Typical Expenditure

Approximately:

**₹75,000 per month**

### Conservative Planning Range

Approximately:

**₹1.20–1.50 lakh per month in today's purchasing power**

### Reason

To avoid designing retirement and financial-independence calculations around an unrealistically tight spending assumption.

---

## Decision — AI Governance

### Policy

AI may be used for:

* Research
* Analysis
* Scenario modelling
* Portfolio comparison
* Decision support

AI recommendations should be independently validated for material decisions.

### Clarification

Agreement among multiple LLMs is not considered proof of correctness.

Primary sources, independent calculations, and qualified professionals should be used where appropriate.

---

## Decision — Market Crash Behaviour

### Policy

During market declines:

* Continue regular investing where financially possible
* Avoid panic selling
* Consider deploying opportunity capital
* Rebalance according to policy
* Act only when structural facts or personal circumstances materially change

### Reason

Market headlines and predictions are not sufficient grounds for abandoning a long-term strategy.

---

## Decision — Insurance Review Required

### Current Position

* LIC sum insured: approximately ₹3 lakh
* LIC premium: approximately ₹17,000 annually
* Expected maturity: 2034
* Corporate health cover: approximately ₹5 lakh
* CGHS access through spouse
* No dedicated term insurance

### Action

Perform a formal term-insurance needs analysis.

### Priority

**High**

---

# [2.x] — Pre-FWOS Planning Stage

## Context

Financial planning was previously discussed primarily through:

* Individual investment decisions
* Portfolio allocation
* Fund selection
* Gold
* International investing
* Property
* Retirement
* Children's education

## Limitation Identified

The planning process lacked:

* A formal governance framework
* Goal-wise funding calculations
* A consolidated family balance sheet
* A documented investment policy
* A structured decision process
* Formal change control

This led to the creation of FWOS Version 3.0.

---

# Pending for Version 3.1

The following items remain unresolved:

* Complete consolidated portfolio inventory
* Goal-wise corpus calculations
* Education inflation assumptions
* Foreign education scenarios
* Retirement corpus calculation
* Emergency-fund target
* Term-insurance needs analysis
* Current versus target asset allocation
* Exact monthly ₹1.25 lakh deployment
* ₹1 crore investment deployment framework
* Existing portfolio transition strategy
* Direct-stock review
* CPSE ETF review
* Bharat 22 ETF review
* Gold implementation vehicle
* International investment implementation
* Tax and ownership optimization

---

# Change-Control Template

Future material entries should use:

## [Version] — Date

### Changed

**Previous Policy:**
Describe the previous position.

**New Policy:**
Describe the new decision.

**Reason:**
Explain why the change was made.

**Evidence / Trigger:**
Document the information or event supporting the change.

**Impact:**
Describe expected portfolio or planning consequences.

**Approved By:**
FWOS Owner

---

## Document Control

**Document:** `CHANGELOG.md`
**Current FWOS Version:** 3.0.0
**Established:** July 2026
**Next Planned Version:** 3.1.0
