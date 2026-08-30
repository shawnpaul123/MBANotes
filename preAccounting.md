# Financial Accounting

Reference for Booth pre-MBA modules 1–8, then the bridge into three-statement modeling (FSM).

---

## 0. The One Idea

Accounting answers two questions:

1. **What do we own and owe right now?** → Balance Sheet (a photograph, at a point in time)
2. **How did we do over a stretch of time?** → Income Statement (a video, over a period)

The Cash Flow Statement is like a detective: it shows how money actually moved in and out of the company, explaining why the cash amount on the balance sheet changed, even when profits (net income) say something else happened.

---

**Review Questions**

1. What two fundamental questions does accounting answer for a business?
2. Why is the Cash Flow Statement important even if Net Income is positive?

---

## 1. Course Overview — Framing

**Financial accounting** = reporting to outsiders (investors, lenders, regulators). Governed by GAAP. This is the course.

**Managerial accounting** = reporting to insiders. No rules. Not this course.

**The four statements:**

| Statement                      | Question                | Time          |
|--------------------------------|-------------------------|--------------|
| Balance Sheet                  | What's our position?    | Point in time|
| Income Statement               | Were we profitable?     | Period       |
| Statement of Cash Flows        | Where did cash go?      | Period       |
| Statement of Stockholders' Equity | How did equity change? | Period    |

**Articulation** — the statements are locked together. I need to memorize these three links:

- Net income (I/S) → flows into Retained Earnings (B/S)
- Ending cash (Statement of Cash Flows) → equals the Cash line (Balance Sheet)
- Beginning RE + NI − Dividends = Ending RE

If a problem doesn't tie, the break is almost always one of these three.

**Who enforces it:** SEC (regulator), FASB (writes GAAP), auditors (opine on whether statements are fairly presented — they don't certify truth, they certify conformity with GAAP). IFRS is the international counterpart; the differences that matter to you are LIFO (banned under IFRS) and asset revaluation (allowed under IFRS, not GAAP).

---

### Check Your Understanding

1. What is the main difference between financial and managerial accounting?
2. Who are the primary users of financial accounting statements?
3. Name the four main financial statements and the core question each answers.
4. What is meant by the "articulation" of the financial statements? Can you state the three main articulation links?
5. Which organizations are responsible for writing and enforcing accounting rules in the U.S.? What are the notable differences between GAAP and IFRS?

---

## 2. Balance Sheet

### Purpose
Shows financial position at a single instant. "As of December 31, 2026."

### The Accounting Equation

```
ASSETS = LIABILITIES + STOCKHOLDERS' EQUITY
```

Left side: resources. Right side: who has a claim on them. Creditors first, owners residual. This never breaks — every transaction keeps it intact.

### Elements

**Assets** — probable future economic benefit, controlled by the firm, from a past transaction. Listed in **liquidity order**.

*Current (converts to cash < 1 year):*
- Cash and equivalents  
  Why: These are already in cash or can be accessed immediately, so they are the most liquid assets.
- Short-term investments / marketable securities  
  Why: They are expected to be sold or mature within a year, making them quickly convertible to cash.
- Accounts receivable (net of allowance)  
  Why: This is money owed by customers that is usually collected within a year.
- Inventory  
  Why: Inventory is expected to be sold within the operating cycle, typically less than a year.
- Prepaid expenses  
  Why: These represent payments for goods/services to be received within a year.

*Non-current:*
- PP&E (net of accumulated depreciation)  
  Why: Property, plant, and equipment are used in operations and are not intended for quick sale; they provide value over many years.
- Intangibles (patents, trademarks)  
  Why: These rights and assets provide economic benefits over multiple years, not within just one year.
- Goodwill  
  Why: Goodwill arises from acquisitions and represents long-term value from expected future earnings.
- Long-term investments  
  Why: These are investments the company intends to hold for over a year, so they are not quickly converted to cash.

**Liabilities** — probable future sacrifice. Listed in **maturity order**.

*Current (due < 1 year):*
- Accounts payable
- Accrued liabilities (wages payable, interest payable, taxes payable)
- Deferred/unearned revenue  
  Why: It's money you've already been paid but haven't delivered the goods or services yet, so you owe the customer. That's why it's a liability—not an asset—because you still have an obligation.
- Current portion of long-term debt

*Non-current:*
- Long-term debt / bonds payable
- Deferred tax liabilities
- Pension obligations

**Stockholders' Equity** — residual claim.
- Common stock (par value): The official value printed on the company’s stock certificates. This is the “face value” for each share, and shows how many shares were issued. (Think of it like the value printed on a ticket—it’s not always what people pay, but it’s the starting point.)
- Additional paid-in capital (APIC): Money that people paid for shares that is more than the par value. So if the par is $1/share and someone paid $10, the extra $9 goes here. (Basically, money paid “above and beyond” the face value.)
- Retained earnings: The total amount of profits the company has earned, minus what it has paid out to shareholders as dividends. (It’s like the company’s piggy bank of leftover profit.)
- Treasury stock: Shares the company bought back from investors. These reduce equity, because they’re kind of like “un-issued” shares now. (It’s a minus sign for equity.)
- Accumulated other comprehensive income (AOCI): Gains and losses from certain things that aren’t regular profits—like changes in the value of investments, or currency changes—added together here. (These are “special” profits or losses that don’t go in regular net income.)

**Contra-equity**: An equity account that reduces total stockholders’ equity, such as treasury stock. This means it has a negative balance and makes overall equity smaller.

### Recognition, Classification, Measurement

**Recognition** — does it go on the balance sheet at all? Needs to be (a) probable future benefit/sacrifice, (b) measurable reliably. This is why your brand, your employees, and your internally-developed software mostly *don't* appear as assets, but a purchased patent does. Big conceptual point: the balance sheet systematically understates the value of successful companies.

**Classification** — current vs. non-current. Drives liquidity ratios, so it matters.

**Measurement** — mostly **historical cost**, not market value. Land bought in 1970 sits at 1970 price. Exceptions: marketable securities (fair value), inventory (lower of cost or net realizable value), impaired assets (written down, never up under GAAP).

### Mechanics: Debits and Credits

**The one rule:** every transaction has a source of value and a use of value, equal in size.
- **Credit** = where value came from
- **Debit** = where value went

*** The above is super important !!! Where the value came from (similar to giving credit to someone) ***

Debits always equal credits. Always.

**Normal balances:**

| Account type | Increases with | Normal balance |
|---|---|---|
| Assets | Debit | Debit |
| Expenses | Debit | Debit |
| Liabilities | Credit | Credit |
| Equity | Credit | Credit |
| Revenue | Credit | Credit |

Mnemonic: **DEA-LER**. **D**ebits: **E**xpenses, **A**ssets. **C**redits: **L**iabilities, **E**quity, **R**evenue.

Why revenue is a credit: it's not a thing you hold, it's the *origin* of the cash or receivable you now hold. The customer is the source.

**T-account:** left side debit, right side credit. Beginning balance on the normal-balance side, entries below, ending balance ruled off at the bottom.

```
        Cash (asset)
   Debit    |   Credit
  (increase)| (decrease)
   Beg 100  |
       50   |   30
  ----------|--------
   End 120  |
```

**Journal entry format** — debits first, credits indented:

```
Dr. Equipment        10,000
    Cr. Cash                  10,000
```

### Core Balance Sheet Journal Entries

| Transaction | Debit | Credit |
|---|---|---|
| Issue stock for cash | Cash | Common Stock + APIC |
| Borrow from bank | Cash | Notes Payable |
| Buy equipment with cash | Equipment | Cash |
| Buy inventory on credit | Inventory | Accounts Payable |
| Pay a supplier | Accounts Payable | Cash |
| Collect a receivable | Cash | Accounts Receivable |
| Customer prepays | Cash | Deferred Revenue |
| Prepay rent | Prepaid Rent | Cash |
| Pay dividend | Retained Earnings (or Dividends) | Cash |
| Buy back own shares | Treasury Stock | Cash |

Note: collecting a receivable has **no** income effect — revenue was already recognized at sale. This trips people constantly.

### Preparing the Balance Sheet
1. Journalize every transaction
2. Post to T-accounts
3. Take ending balances
4. Sort into current/non-current, assets/liabilities/equity
5. Check A = L + E

---

**Review Questions**

1. What is the accounting equation and why must it always balance?
2. Name two non-current assets and explain why they're classified that way.

---

## 3. Income Statement

### Purpose
Performance over a period. "For the year ended December 31, 2026."

### Structure

```
Revenue (Sales)
− Cost of Goods Sold
= GROSS PROFIT
− Operating Expenses (SG&A, R&D, Depreciation)
= OPERATING INCOME (EBIT)
± Non-operating items (interest expense, interest income, gains/losses)
= PRETAX INCOME (EBT)
− Income Tax Expense
= NET INCOME
```

Know each subtotal and what sits above/below it. Exams love "does X hit gross profit or operating income?"

**Gross margin** = Gross profit ÷ Revenue. **Operating margin** = EBIT ÷ Revenue. **Net margin** = NI ÷ Revenue.

### Link to Balance Sheet

Revenue and expense accounts are **temporary** — they accumulate during the year and get zeroed out at year-end into Retained Earnings. That closing entry is the bridge between the two statements.

```
Ending RE = Beginning RE + Net Income − Dividends
```

**Closing entries:**
```
Dr. Revenue                XX
    Cr. Retained Earnings       XX

Dr. Retained Earnings      XX
    Cr. Expenses                XX
```

Balance sheet accounts are **permanent** — they carry forward.

### Recognition and Measurement

**Revenue recognition:** recognize when the performance obligation is satisfied — when control transfers to the customer — *not* when cash arrives.

The 5-step model (ASC 606):
1. Identify the contract
2. Identify the performance obligation(s)
3. Determine the transaction price
4. Allocate the price to the obligations
5. Recognize revenue as each obligation is satisfied

**Matching principle:** expenses are recognized in the same period as the revenue they helped generate. COGS hits when the sale happens, not when inventory was bought.

### Cash vs. Accrual — The Central Distinction

Accrual accounting decouples **cash timing** from **economic timing**. Four cases:

| | Cash BEFORE the event | Cash AFTER the event |
|---|---|---|
| **Revenue** | Deferred revenue (liability) | Accrued revenue → A/R (asset) |
| **Expense** | Prepaid expense (asset) | Accrued expense → payable (liability) |

Every one of these creates a balance sheet account that exists purely to hold the timing difference. That's what those weird accounts *are*.

### Adjusting Entries

Made at period end, before statements. **Every adjusting entry hits one income statement account and one balance sheet account.** Never two of the same. Never cash.

**1. Deferred expense** (prepaid asset gets used up)
```
Paid $12,000 for 12 months rent upfront:
Dr. Prepaid Rent      12,000
    Cr. Cash                  12,000     ← no I/S effect

One month later:
Dr. Rent Expense       1,000              ← I/S
    Cr. Prepaid Rent          1,000       ← B/S
```

**2. Deferred revenue** (liability earned off)
```
Received $6,000 for a 6-month subscription:
Dr. Cash               6,000
    Cr. Deferred Revenue      6,000       ← liability, no revenue yet

One month later:
Dr. Deferred Revenue   1,000              ← B/S
    Cr. Revenue               1,000       ← I/S
```

**3. Accrued expense** (incurred, not yet paid)
```
Wages earned but unpaid at year-end:
Dr. Wage Expense       5,000              ← I/S
    Cr. Wages Payable         5,000       ← B/S
```

**4. Accrued revenue** (earned, not yet billed/collected)
```
Services delivered, not yet invoiced:
Dr. Accounts Receivable 3,000             ← B/S
    Cr. Revenue                3,000      ← I/S
```

**5. Depreciation** (the special one)
```
Dr. Depreciation Expense      2,000       ← I/S
    Cr. Accumulated Depreciation  2,000   ← contra-asset, B/S
```
Accumulated Depreciation is a **contra-asset**: it has a credit balance and reduces the asset. Never credit the asset directly — you'd lose the original cost.

### Common Income Statement Entries

| Transaction | Debit | Credit |
|---|---|---|
| Cash sale | Cash | Revenue |
| Credit sale | Accounts Receivable | Revenue |
| Record COGS on that sale | COGS | Inventory |
| Pay wages | Wage Expense | Cash |
| Accrue interest owed | Interest Expense | Interest Payable |
| Record bad debt | Bad Debt Expense | Allowance for Doubtful Accounts |
| Write off a specific bad account | Allowance for Doubtful Accounts | Accounts Receivable |

Note the last two: the write-off has **no income statement effect**. The expense was already taken when the allowance was set up. Classic exam question.

---

**Review Questions**

1. List the main sections of the income statement in order and give an example for each.
2. What is the purpose of a closing entry, and which two statements does it connect?

---

## 4. Statement of Cash Flows

### Purpose
Reconciles net income (accrual) to the actual change in cash. A profitable company can die of cash starvation; this statement is where you see it coming.

### Three Sections

**Operating (CFO)** — core business. Sales collections, supplier payments, wages, interest paid, taxes.

**Investing (CFI)** — long-term assets. CapEx (buying PP&E), proceeds from asset sales, buying/selling securities.

**Financing (CFF)** — capital structure. Issuing/repaying debt, issuing stock, buying back stock, paying dividends.

```
CFO + CFI + CFF = Change in Cash
Beginning Cash + Change in Cash = Ending Cash   ← must tie to B/S
```

### Indirect Method (this is what you'll be tested on)

Start with net income, strip out everything non-cash and everything that isn't operating.

```
Net Income
+ Depreciation & Amortization            (non-cash expense, add back)
+ Stock-based compensation               (non-cash)
+ Loss on asset sale / − Gain on sale    (reverse it — it belongs in investing)
+ Bad debt expense                       (non-cash)
± Changes in working capital:
    − Increase in Accounts Receivable
    − Increase in Inventory
    − Increase in Prepaid Expenses
    + Increase in Accounts Payable
    + Increase in Accrued Liabilities
    + Increase in Deferred Revenue
= CASH FROM OPERATIONS
```

**The sign rule — memorize it as one sentence:**

> Asset up → cash down. Liability up → cash up.

Intuition: an increase in AR means you booked revenue but didn't collect. An increase in AP means you booked an expense but didn't pay. Both are cash you still have (or don't have) relative to what income says.

**Why gains get subtracted:** you sold equipment with book value 80 for 100. Net income includes a +20 gain. But the full 100 belongs in investing. So subtract the 20 from CFO and put the whole 100 in CFI. Otherwise you'd count 20 twice.

### Direct Method
Lists actual cash receipts and payments (cash collected from customers, cash paid to suppliers). Rarely used in practice. CFI and CFF sections are identical under both methods; only CFO presentation differs.

### Reading It
- CFO > Net income consistently → good earnings quality
- CFO < Net income consistently → dig into working capital, possible aggressive revenue recognition
- CFO positive, CFI negative, CFF negative → a healthy mature business funding its own growth and returning capital
- CFO negative, CFF positive → burning cash, funded by outsiders. Fine for a startup, alarming for a mature firm

---

**Review Questions**

1. What is the difference between operating, investing, and financing cash flows? Give an example for each.
2. Why might a company have positive net income but negative operating cash flow?

---

## 5. Preparing Financial Statements — The Full Cycle

The whole loop, in order:

1. **Analyze** each transaction (source/use)
2. **Journalize** — record the entry
3. **Post** to T-accounts / ledger
4. **Unadjusted trial balance** — list all accounts, verify debits = credits
5. **Adjusting entries** — the four accruals/deferrals plus depreciation
6. **Adjusted trial balance**
7. **Prepare statements** — Income Statement first, then Statement of Stockholders' Equity, then Balance Sheet, then Cash Flow Statement
8. **Closing entries** — zero out temporary accounts into Retained Earnings
9. **Post-closing trial balance** — only permanent accounts remain

**Order matters in step 7.** You need net income before you can compute ending retained earnings, and you need ending retained earnings before the balance sheet balances.

### Working Backward ("Unwinding")

Booth problems frequently give you the statements and ask what transactions produced them. The tool is a T-account with the plug:

```
Beginning balance + Increases − Decreases = Ending balance
```

Solve for the unknown. Common versions:

- **Cash collected from customers** = Beginning AR + Revenue − Ending AR
- **Cash paid to suppliers** = Beginning AP + Purchases − Ending AP, where Purchases = COGS + Ending Inv − Beginning Inv
- **CapEx** = Ending PP&E(gross) − Beginning PP&E(gross) + cost of assets disposed
- **Dividends** = Beginning RE + Net Income − Ending RE

Practice these four until they're automatic. They're the highest-yield mechanic in the course and they're also exactly what FSM requires.

### Where Balances Break
If the balance sheet doesn't balance, check in this order:
1. Net income didn't flow to retained earnings
2. Dividends not deducted from RE
3. A sign error on one leg of a two-sided entry
4. Accumulated depreciation added instead of subtracted
5. Ending cash from SCF doesn't match B/S cash

That list covers ~95% of failures.

---

**Review Questions**

1. Why does the preparation order of statements matter?
2. If a balance sheet does not balance, what three things should you check first?

---

## 6. Additional Topics (Master in Finance / deeper mechanics)

### Accounts Receivable & Allowance

AR is reported **net of allowance for doubtful accounts** (a contra-asset). Net AR = Net realizable value.

Two ways to estimate the expense:
- **Percentage of sales** (income statement approach) — bad debt expense = % × credit sales. Simple, focuses on matching.
- **Aging of receivables** (balance sheet approach) — estimate the *ending allowance balance* needed, then plug the expense. More accurate.

Critical distinction with aging: you're solving for the *ending balance*, so the expense is the plug:
```
Required ending allowance − existing allowance balance = bad debt expense
```

---

**Example Questions**

1. Why is AR presented net of allowance for doubtful accounts?
2. What is the difference between the income statement and balance sheet approaches to estimating bad debt expense?

---

### Inventory

**Cost flow assumptions:**
- **FIFO** — oldest costs to COGS. In rising prices: lower COGS, higher income, higher taxes, inventory on B/S near current cost.
- **LIFO** — newest costs to COGS. In rising prices: higher COGS, lower income, lower taxes, inventory on B/S badly stale. US-only (banned under IFRS).
- **Weighted average** — splits the difference.

**LIFO reserve** (the conversion you need):
```
FIFO Inventory = LIFO Inventory + LIFO Reserve
FIFO COGS = LIFO COGS − Change in LIFO Reserve
```

**Lower of cost or net realizable value** — write inventory down if NRV falls below cost. Write-downs are permanent under GAAP (no reversals).

**Ratios:** Inventory turnover = COGS ÷ average inventory. Days inventory = 365 ÷ turnover.

---

**Example Questions**

1. Why does the use of LIFO versus FIFO matter in periods of rising prices?
2. What is the purpose of the LIFO reserve?

---

### PP&E and Depreciation

**Capitalize vs. expense:** if the expenditure creates future benefit beyond this period, capitalize it (asset). Otherwise expense it. Capitalizing shifts cost out of this year's income statement into future depreciation — a classic earnings-management lever.

**Methods:**
- Straight-line: `(Cost − Salvage) ÷ Useful life`
- Double-declining balance: `2 × (1/Useful life) × Beginning book value` — ignore salvage until the floor
- Units of production: `(Cost − Salvage) × (Units this period ÷ Total units)`

**Book value** = Cost − Accumulated depreciation

**Disposal:**
```
Gain/Loss = Proceeds − Book value

Dr. Cash                        proceeds
Dr. Accumulated Depreciation    accumulated
    Cr. Equipment                       original cost
    Cr. Gain on Sale                    plug (or Dr. Loss)
```

**Impairment** — write down when carrying value isn't recoverable. Downward only under GAAP.

**Intangibles:** finite life → amortize. Indefinite life and goodwill → don't amortize, test annually for impairment.

---

**Example Questions**

1. When should a company capitalize versus expense a purchase?
2. How does straight-line depreciation differ from double-declining balance?

---

### Bonds and Long-Term Debt

**Pricing:** Issue price = PV(coupon payments, an annuity) + PV(face value, a lump sum), discounted at the **market rate**.

| Relationship | Result |
|---|---|
| Coupon rate > Market rate | Issued at a **premium** (above face) |
| Coupon rate = Market rate | Issued at **par** |
| Coupon rate < Market rate | Issued at a **discount** (below face) |

**Effective interest method:**
```
Interest expense = Beginning carrying value × Market rate (at issuance)
Cash coupon      = Face value × Coupon rate
Amortization     = Interest expense − Cash coupon
```
Carrying value marches toward face value, hitting it exactly at maturity. For a discount, carrying value rises and interest expense > cash paid. For a premium, the reverse.

---

**Example Questions**

1. What happens to the carrying value of a bond issued at a discount over time?
2. How does the market rate at issuance affect a bond's price?

---

### Investments in Securities

| Type | Balance sheet | Gains/losses go to |
|---|---|---|
| Trading | Fair value | Net income |
| Available-for-sale | Fair value | OCI (equity, bypasses I/S) |
| Held-to-maturity | Amortized cost | Nothing until sold |
| Equity method (20–50%, significant influence) | Cost + %NI − %dividends | Net income (share of investee's) |
| Consolidation (>50%, control) | Full consolidation + non-controlling interest | — |

---

**Example Questions**

1. Where do unrealized gains and losses on available-for-sale securities appear on the financial statements?
2. What is the difference between the equity method and consolidation accounting for investments?

---

### Deferred Taxes
Book income ≠ taxable income because GAAP and the tax code have different timing rules. The difference creates a deferred tax asset or liability. Most common source: depreciation (accelerated for tax, straight-line for books) → deferred tax liability.

---

**Example Questions**

1. Why do deferred tax liabilities commonly arise from differences in depreciation methods?
2. How can timing differences between book and tax income create deferred tax assets?

---

## 7. Time Value of Money

A dollar today is worth more than a dollar tomorrow. Everything in valuation rests on this.

### The Four Formulas

**Future value, lump sum:**
```
FV = PV × (1 + r)^n
```

**Present value, lump sum:**
```
PV = FV ÷ (1 + r)^n
```

**Present value, ordinary annuity** (equal payments at the *end* of each period):
```
PV = PMT × [1 − (1 + r)^−n] ÷ r
```

**Future value, ordinary annuity:**
```
FV = PMT × [(1 + r)^n − 1] ÷ r
```

**Perpetuity** (payments forever):
```
PV = PMT ÷ r
```

**Growing perpetuity** (the terminal value formula in every DCF):
```
PV = PMT₁ ÷ (r − g)
```

### Mechanics That Trip People
- **Annuity due** (payments at the *beginning* of each period): multiply the ordinary annuity result by (1 + r)
- **Non-annual compounding:** divide the rate by periods per year, multiply n by periods per year. Semiannual bond at 8% for 5 years → r = 4%, n = 10
- **Discount rate and value move opposite.** Higher r → lower PV. Always
- Match your rate period to your cash flow period. Every time

### Where It Shows Up
Bond pricing, lease capitalization, pension obligations, impairment testing, and every DCF you'll build.

---

**Review Questions**

1. Which time value formulas would you use to value a pension with constant payments?
2. Why does the present value decrease when the discount rate increases?

---

## 8. Applications — Reading Statements Like an Analyst

### Profitability
```
Gross margin      = Gross profit ÷ Revenue
Operating margin  = EBIT ÷ Revenue
Net margin        = Net income ÷ Revenue
ROA               = Net income ÷ Average total assets
ROE               = Net income ÷ Average shareholders' equity
```

### DuPont Decomposition
```
ROE = Net margin × Asset turnover × Financial leverage
    = (NI/Sales) × (Sales/Avg Assets) × (Avg Assets/Avg Equity)
```
This tells you *why* ROE is what it is: pricing power, asset efficiency, or leverage. Two firms with identical ROE can be completely different businesses. Know how to say which.

### Efficiency
```
Inventory turnover  = COGS ÷ Average inventory
DIO                 = 365 ÷ Inventory turnover
AR turnover         = Revenue ÷ Average AR
DSO                 = 365 ÷ AR turnover
DPO                 = 365 ÷ (COGS ÷ Average AP)

Cash conversion cycle = DIO + DSO − DPO
```
Negative CCC (Dell, Amazon) means suppliers finance your growth. Worth understanding deeply.

### Liquidity & Solvency
```
Current ratio    = Current assets ÷ Current liabilities
Quick ratio      = (Cash + ST investments + AR) ÷ Current liabilities
Debt-to-equity   = Total debt ÷ Total equity
Interest coverage = EBIT ÷ Interest expense
```

### Earnings Quality — What to Actually Look For
- CFO diverging below net income over multiple periods
- AR or inventory growing much faster than revenue
- Frequent "one-time" charges that recur every year
- Capitalizing costs peers expense
- Useful lives or salvage values drifting upward
- Allowance for doubtful accounts shrinking as a % of gross AR while sales grow

---

**Review Questions**

1. If a company has negative cash conversion cycle, what does it tell you about their suppliers and customers?
2. What might it indicate if a company’s AR grows much faster than revenue over several periods?

---

## 9. Setup for FSM (Three-Statement Modeling)

Everything above was to get you here. FSM builds a linked model where the balance sheet must balance and every line traces to a driver.

### Model Architecture

```
Historical financials (3 years) → Ratio analysis → Assumptions → Projections → Linked statements
```

**Build order matters and is non-negotiable:**

1. **Income statement down to EBIT** — revenue driven by growth assumption; COGS as % of revenue; opex as % of revenue
2. **Supporting schedules:**
   - Depreciation schedule (feeds D&A into I/S, accumulated depreciation into B/S)
   - Working capital schedule (AR from DSO, inventory from DIO, AP from DPO)
   - Debt schedule (feeds interest expense into I/S, debt balance into B/S)
3. **Complete the income statement** — interest expense from the debt schedule, then taxes, then net income
4. **Balance sheet** — everything except cash
5. **Cash flow statement** — start from net income, pull working capital changes from the schedule, CapEx from the depreciation schedule, financing from the debt schedule
6. **Cash flows back** — ending cash from the SCF becomes the cash line on the balance sheet
7. **Check that it balances**

Step 6 is the whole trick. Cash is the plug, and it's the *only* plug.

### The Circularity

Interest expense depends on the debt balance → debt balance depends on cash available to repay → cash depends on net income → net income depends on interest expense. This is a genuine circular reference. Solutions: enable iterative calculation in Excel, or use average debt balances, or add a circuit breaker toggle. Every FSM course covers this; know it's coming.

### Common Drivers

| Line item | Driven by |
|---|---|
| Revenue | Growth % or units × price |
| COGS | % of revenue (or gross margin %) |
| SG&A | % of revenue |
| D&A | Depreciation schedule (% of gross PP&E, or from CapEx and useful life) |
| CapEx | % of revenue |
| AR | DSO × (Revenue ÷ 365) |
| Inventory | DIO × (COGS ÷ 365) |
| AP | DPO × (COGS ÷ 365) |
| Interest expense | Average debt balance × interest rate |
| Taxes | Effective tax rate × pretax income |

### Which Concepts Above Map to Which FSM Task

| Accounting concept | FSM use |
|---|---|
| Articulation (NI → RE, SCF cash → B/S cash) | The two links that make the model balance |
| Adjusting entries / accruals | Why working capital changes exist at all |
| Indirect-method cash flow | The entire CFO build |
| Depreciation methods | Depreciation schedule |
| Bond amortization, effective interest | Debt schedule, especially in LBO |
| DSO / DIO / DPO | Working capital schedule |
| T-account unwinding (`Beg + Δ = End`) | Every roll-forward schedule in the model |

That last row is the single most transferable skill. A roll-forward schedule *is* a T-account laid out horizontally:

```
Beginning PP&E + CapEx − Depreciation − Disposals = Ending PP&E
Beginning Debt + Issuance − Repayment = Ending Debt
Beginning RE + Net Income − Dividends = Ending RE
```

If you can do those cold, FSM is mechanical.

### Before You Start FSM — Self-Check

You should be able to do all six without notes:

1. State what happens to all three statements when depreciation increases by 100
2. Build CFO from net income and a working capital schedule
3. Explain why a profitable company runs out of cash, with a specific example
4. Compute cash collected from customers given revenue and AR balances
5. Construct a balance sheet from a transaction list and have it balance
6. Build a three-period bond amortization table under the effective interest method

If any fail, go back to that section before opening Excel.

**Answer to #1** (the canonical interview question): Depreciation +100. Income statement: EBIT −100, and with a 25% tax rate, net income −75. Cash flow statement: net income −75, add back depreciation +100, so cash +25. Balance sheet: cash +25, PP&E −100 (via accumulated depreciation), so assets −75; retained earnings −75, so equity −75. Balances.

---

**Review Questions**

1. What is the primary purpose of linking the three financial statements in FSM?
2. Give an example of a circularity found in a three-statement model.

---

## Quick Reference Card

**Equations**
```
Assets = Liabilities + Equity
Ending RE = Beginning RE + Net Income − Dividends
CFO + CFI + CFF = Δ Cash
Beg + Additions − Subtractions = End        ← every roll-forward
```

**Debits/Credits**
```
Debit ↑: Assets, Expenses
Credit ↑: Liabilities, Equity, Revenue
Debit = where value went; Credit = where it came from
```

**Cash flow signs**
```
Asset ↑ → Cash ↓
Liability ↑ → Cash ↑
Non-cash expense → add back
Gain → subtract from CFO (belongs in CFI)
```

**Four adjusting entries**
```
Prepaid expense:   Dr. Expense    / Cr. Prepaid asset
Deferred revenue:  Dr. Deferred rev / Cr. Revenue
Accrued expense:   Dr. Expense    / Cr. Payable
Accrued revenue:   Dr. Receivable / Cr. Revenue
```

**TVM**
```
PV = FV ÷ (1+r)^n
PV annuity = PMT × [1 − (1+r)^−n] ÷ r
PV perpetuity = PMT ÷ r
PV growing perpetuity = PMT₁ ÷ (r − g)
```

---

**Quick Practice**

1. Which formula from the card would you use to unwind an inventory balance?
2. If a company’s liability increases, what will generally happen to its cash under indirect method cash flows?
