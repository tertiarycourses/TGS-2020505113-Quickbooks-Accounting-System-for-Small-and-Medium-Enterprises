# Quickbooks Accounting System for Small and Medium Enterprises — Learner Guide

**Course code:** TGS-2020505113  
**Version:** 15.0 · 15 August 2026

## How to use this guide

The slides teach concepts and controls. This guide and the individual activity folders contain the detailed procedures, evidence requirements and acceptance criteria. Record any QuickBooks UI difference in the activity exception log.

## Learning outcomes

- LO1: Configure and import relevant data to the QuickBooks accounting system.
- LO2: Input and control day-to-day sales, purchasing, banking and inventory data in QuickBooks.
- LO3: Compute and review GST for expenses and invoices using appropriate Singapore tax codes.
- LO4: Generate and interpret financial, accounting, ageing and GST reports for SME decisions.

## Source and compliance note

Tax content is educational, not tax advice. Verify time-sensitive rules with IRAS and current product behaviour with Intuit.

- [Course page](https://www.tertiarycourses.com.sg/wsq-quickbooks-accounting-system-for-small-and-medium-enterprises.html) — One-day, 8-hour beginner course; four learning outcomes and four topic areas.
- [QuickBooks Singapore](https://quickbooks.intuit.com/sg/) — Current Singapore QuickBooks positioning, features and support links; plan availability changes over time.
- [QuickBooks Learn & Support](https://quickbooks.intuit.com/learn-support/global/get-started-with-quickbooks-online/) — Current navigation and workflow reference; learners should expect UI labels to evolve.
- [IRAS current GST rates](https://www.iras.gov.sg/taxes/goods-services-tax-(gst)/basics-of-gst/current-gst-rates) — Singapore GST is 9% at the publication date; standard-rated, zero-rated, exempt and out-of-scope treatment must be distinguished.
- [IRAS GST filing](https://www.iras.gov.sg/taxes/goods-services-tax-(gst)/filing-gst) — GST return review and filing obligations; QuickBooks is a preparation and control tool, not a substitute for IRAS guidance.
- [IRAS corporate income tax](https://www.iras.gov.sg/taxes/corporate-income-tax/basics-of-corporate-income-tax/corporate-income-tax-rate-rebates-and-tax-exemption-schemes) — Corporate income tax is 17% of chargeable income; time-sensitive rebates and exemptions must be checked with IRAS.

## Topic 1: Introduction to QuickBooks Online Plus Accounting System

**Alignment:** A1 · K1 · Cloud accounting · company setup · master data · governance

### Key concepts

- Accounting-system choices and the role of cloud accounting in an SME control environment.
- Company settings, financial year, GST profile, home currency and user-access design.
- A governed migration sequence for chart of accounts, customers, suppliers and products/services.
- Opening-balance controls: cut-off, completeness, mapping, reconciliation and sign-off.

### From source document to decision

- Capture evidence
- Classify consistently
- Post to ledgers
- Review and decide

### Accounting systems an SME may encounter

- Manual records — low cost, weak control at scale
- Desktop accounting — local control, limited collaboration
- Cloud accounting — shared, current records
- ERP — integrated processes across functions

### What QuickBooks Online manages

- Sales and receivables
- Purchases and payables
- Banking and reconciliation
- Inventory, GST and reporting

### Cloud accounting control model

- Authorised users
- Structured transactions
- Automated ledger updates
- Reviewable reports

### QuickBooks ecosystem

- Core ledger and subledgers
- Bank connections and imports
- App integrations
- Accountant collaboration

### Select a plan by requirements

- Transaction volume
- Number and roles of users
- Inventory and purchase orders
- Reporting and automation needs

### Company setup decisions

- Legal and customer-facing identity
- Financial year and accounting method
- GST registration details
- Home currency and multi-currency decision

### Multi-currency is a governance decision

- Confirm business need
- Set the correct home currency first
- Understand exchange-rate effects
- Document irreversible or plan-specific settings

### User roles and segregation of duties

- Primary administrator
- Company administrator
- Standard user with scoped access
- Reports-only/accountant access where available

### Chart of Accounts is the reporting spine

- Account type drives report placement
- Detail type supports classification
- Code and name support consistency
- Inactive accounts preserve history

### Design a usable account structure

- Stable coding convention
- Right level of detail
- Avoid duplicate meaning
- Map legacy accounts before import

### Master-data quality gate

- Clean
- Standardise
- Map
- Validate
- Import
- Reconcile

### Customer and supplier records

- Unique display name and contact
- Terms and opening balance cut-off
- GST and currency attributes
- Duplicate prevention and ownership

### Products and services records

- Inventory item
- Non-inventory item
- Service item
- Bundle/category where available

### Inventory item accounting map

- Purchase cost
- Inventory asset
- Sale revenue
- Cost of goods sold

### Opening balances need evidence

- Trial balance at cut-off
- AR/AP detail matches control totals
- Bank statement agrees to cash
- Inventory quantity and value are supported

### Migration control totals

- Record count
- Debit/credit totals
- Opening balance totals
- Exception log and sign-off

### Import or enter manually?

- Use import for clean repeatable lists
- Use manual entry for low volume
- Test a small sample first
- Retain the source and import result

### Topic 1 control checkpoint

- A successful setup is not just complete; it is reconciled, access-controlled and explainable.

### Activity 01: Set Up the SME Company and Control Profile

**Level:** Foundation · **Duration:** 35 min · **Alignment:** A1 · K1

Create a controlled QuickBooks company profile for Orchid Bay Trading Pte Ltd.

#### Detailed step-by-step procedure

1. Open the activity workbook and read the Scenario and Control Matrix sheets before using QuickBooks.
2. Sign in to the training QuickBooks Online company supplied by the trainer; confirm that it is a sandbox or training file.
3. Open Account and settings and record the current company, sales, expenses and advanced settings in the Evidence Log.
4. Enter the legal name, customer-facing name, UEN, GST registration number, contact details and Singapore address from the workbook.
5. Set the first month of the financial year to January and confirm the accounting method required by the scenario.
6. Confirm SGD as home currency; do not enable multi-currency until the irreversible-setting check is signed off.
7. Review GST settings against the 9% standard rate and quarterly filing scenario; do not mark any period as filed.
8. Create the proposed user-access matrix without inviting real external users; use trainer-provided dummy addresses only if instructed.
9. Capture screenshots of the company, financial-year and GST settings, excluding personal information.
10. Complete the Control Checks sheet and record any plan/UI difference in the Exception Log.

#### Acceptance criteria

- Legal identity and financial year match the scenario
- GST profile is documented
- Home currency decision is approved
- Access roles follow least privilege

Files: `activities/activity-01-company-setup-and-controls/`


### Activity 02: Clean and Import Master Data

**Level:** Foundation · **Duration:** 45 min · **Alignment:** A1 · K1

Prepare, validate and import the chart of accounts, customers, suppliers and products/services.

#### Detailed step-by-step procedure

1. Review the supplied chart of accounts, customer, supplier and product/service files; do not import before completing validation.
2. Check required columns, unique names, data types, opening-balance dates and GST/currency attributes.
3. Use the Mapping sheet to map each legacy account to the intended QuickBooks account type and detail type.
4. Resolve duplicate customer and supplier display names using the documented naming rule.
5. Confirm that product/service income, expense/COGS and inventory-asset mappings are complete.
6. Record source row counts and control totals in the workbook before import.
7. Import the chart of accounts first; inspect the preview and correct rejected or mis-mapped rows.
8. Import customers and suppliers; compare imported counts with source counts and log exceptions.
9. Import products/services or enter the small list manually if the current plan does not support the import path.
10. Run a post-import control: sample three records from each list and reconcile totals to the workbook.

#### Acceptance criteria

- All source files pass the quality checks
- Counts reconcile before and after import
- No duplicate display names remain
- Account and item mappings are supportable

Files: `activities/activity-02-master-data-import/`


## Topic 2: Input Data to QuickBooks

**Alignment:** A2 · K2 · Banking · sales · purchases · inventory · recurring transactions

### Key concepts

- A source-document-to-ledger cycle for bank, sales, purchasing and inventory transactions.
- Accounts receivable from estimate through invoice, receipt, credit and overdue follow-up.
- Accounts payable from purchase order through bill, payment, supplier credit and recurring expense.
- Control points for duplicate prevention, approvals, audit trail, class/location and reconciliation.

### Transaction lifecycle

- Source
- Authorise
- Record
- Settle
- Reconcile
- Review

### Bank feeds and file imports

- Connection can reduce rekeying
- CSV import supports controlled batches
- Downloaded does not mean correctly posted
- Review every match, add and exclusion

### Banking rule of evidence

- The bank feed is a source; the ledger classification and reconciliation are the control.

### Add a bank account correctly

- Correct account type
- Clear account name and number
- Opening date and balance evidence
- Owner and reconciliation frequency

### Match, add or exclude

- Match an existing transaction
- Add a genuine new transaction
- Exclude non-business or duplicate feed lines
- Document exceptions before posting

### Deposit, cheque and transfer

- Deposit records money received
- Cheque/expense records money paid
- Transfer moves value between own accounts
- Each needs date, account and evidence

### Bank reconciliation equation

- Statement ending balance
- Add deposits in transit
- Less outstanding payments
- Equals ledger balance

### Reconciliation differences

- Wrong date or amount
- Duplicate or missing transaction
- Uncleared item
- Opening-balance or bank-charge issue

### Sales cycle

- Estimate
- Customer approval
- Invoice
- Receive payment
- Deposit
- Follow up

### Estimate, invoice or sales receipt?

- Estimate — non-posting offer
- Invoice — sale on credit
- Sales receipt — immediate payment
- Credit note — reduces customer balance

### Invoice quality controls

- Correct customer and date
- Accurate product, quantity and price
- Terms and tax code
- Unique document number and supporting evidence

### Custom form styles

- Brand identity and contact details
- Readable item and tax information
- Consistent payment terms
- Preview before use

### Receive and apply payment controls

- Customer identity
- Open invoice match
- Payment evidence
- Deposit destination
- Balance validation

### Manage overdue invoices

- Review ageing buckets
- Prioritise material exposures
- Document collection action
- Escalate disputes and credit risk

### Purchasing cycle

- Purchase order
- Receive
- Supplier bill
- Approve
- Pay
- Reconcile

### Expense, bill or cheque?

- Expense — paid now
- Bill — pay later
- Cheque — payment instrument
- Purchase order — commitment, not expense

### Three-way matching

- Purchase order
- Goods or service received
- Supplier invoice
- Approved bill

### Supplier credits

- Record the supplier credit
- Apply it to open bills
- Preserve original documents
- Verify AP control balance

### Recurring transactions

- Use for predictable repeated entries
- Set schedule and end condition
- Choose reminder or automatic mode
- Review templates periodically

### Inventory quantity and value

- Purchase increases quantity/value
- Sale reduces quantity and recognises COGS
- Adjustment needs reason and authorisation
- Negative stock is a control warning

### Class and location tracking

- Class answers what activity
- Location answers where
- Use a stable taxonomy
- Review unclassified transactions

### Audit log as detective control

- Who changed what
- When the change occurred
- Deleted or voided transactions
- User patterns requiring review

### Internal control pattern

- Prevent
- Detect
- Correct
- Evidence
- Monitor

### Topic 2 control checkpoint

- Fast data entry is useful only when source evidence, approval and reconciliation remain intact.

### Activity 03: Import Banking Data and Reconcile January

**Level:** Intermediate · **Duration:** 50 min · **Alignment:** A2 · K2

Set up bank accounts, import statement lines and reconcile the January statement.

#### Detailed step-by-step procedure

1. Create the DBS operating and OCBC reserve accounts using the account details in the workbook.
2. Review the bank-statement CSV and confirm opening balance, ending balance, date range and row count.
3. Import the statement file using the current bank-upload workflow and map date, description and amount fields.
4. For each line, decide whether to match, add or exclude; use the Classification sheet as the approved coding source.
5. Record the director capital injection as a bank deposit to equity and retain the supporting reference.
6. Record the consulting payment with the correct expense account and GST code.
7. Record the transfer between DBS and OCBC once; verify that it does not duplicate both sides of the imported feed.
8. Start the reconciliation using the statement ending date and balance in the workbook.
9. Investigate any difference by amount, date, duplicate, missing item or opening balance; do not force a balancing entry.
10. Save the reconciliation report and complete the workbook Evidence Log.

#### Acceptance criteria

- Imported row count matches the source
- Every line is matched, added or excluded with a reason
- Transfer is recorded once
- Reconciliation difference is zero

Files: `activities/activity-03-banking-and-reconciliation/`


### Activity 04: Process the Sales and Receivables Cycle

**Level:** Intermediate · **Duration:** 45 min · **Alignment:** A2 · K2

Process an estimate, invoice, sales receipt, payment, customer credit and overdue follow-up.

#### Detailed step-by-step procedure

1. Review the Sales Orders sheet and confirm customer, item, quantity, price, terms and GST treatment.
2. Create estimate EST-1001 for Lion City Cafe Pte Ltd and verify that it does not post to the general ledger.
3. Convert the accepted estimate to invoice INV-1001 without rekeying; confirm quantity, price and 9% GST.
4. Create a sales receipt for an immediate-payment walk-in sale and deposit it to the correct account.
5. Receive and apply the customer payment to INV-1001; verify that the unapplied amount is zero.
6. Create the approved customer credit for returned goods and apply it to the relevant open balance.
7. Preview the invoice style and verify legal identity, GST details, terms and readable line information.
8. Run the customer transaction list and compare it with the Expected Postings sheet.
9. Run AR Ageing Summary as at month-end and identify the top two overdue balances.
10. Document the collection priority, owner, promised date and escalation trigger in the Action Log.

#### Acceptance criteria

- Estimate-to-invoice chain is intact
- Payment and credit are applied correctly
- GST is consistent with source documents
- AR ageing actions are specific and evidenced

Files: `activities/activity-04-sales-and-receivables/`


### Activity 05: Process Purchasing and Payables

**Level:** Intermediate · **Duration:** 45 min · **Alignment:** A2 · K2

Process purchase orders, supplier bills, payments, supplier credits and recurring expenses.

#### Detailed step-by-step procedure

1. Review the Purchase Register and identify the approved supplier, item, quantity, price, GST and approver.
2. Create purchase order PO-2001 and confirm that it is non-posting until receipt/bill conversion.
3. Compare the purchase order, receiving evidence and supplier invoice using the three-way match sheet.
4. Convert the purchase order to bill BILL-2001; correct any variance only with an approved reason.
5. Enter the immediate-payment office expense separately and use the correct expense account and GST code.
6. Pay the approved bill from the DBS operating account and record the supplier reference.
7. Enter the supplier credit for damaged goods and apply it to the supplier balance.
8. Create a reminder-type recurring transaction for the monthly internet bill with a defined end/review date.
9. Run AP Ageing Summary and compare supplier balances with the workbook control totals.
10. Record evidence and exceptions, including any plan-specific workflow difference.

#### Acceptance criteria

- Three-way match is documented
- Bill and payment retain source references
- Supplier credit is applied
- Recurring template has an owner and review date

Files: `activities/activity-05-purchasing-and-payables/`


### Activity 06: Control Inventory, Classes, Locations and Audit Trail

**Level:** Intermediate · **Duration:** 35 min · **Alignment:** A2 · K2

Review inventory movements, classification quality and audit-log evidence.

#### Detailed step-by-step procedure

1. Review the Inventory Roll-forward sheet and confirm opening quantity and cost for each item.
2. Compare purchases, sales, returns and adjustments with the expected closing quantities.
3. Investigate negative stock, unusual adjustment dates and unsupported changes; do not post a plug adjustment.
4. Apply the approved class and location taxonomy to the sample transactions where the training plan supports it.
5. Run a transaction report filtered for blank class/location and record the exceptions.
6. Open the audit log and filter for the activity period and transaction changes.
7. Trace one created, one edited and one voided/deleted example to its user and timestamp.
8. Assess whether the user role and activity are appropriate under the access matrix.
9. Document corrective actions and training needs in the Audit Review sheet.
10. Sign off the inventory and audit controls only when supporting evidence is complete.

#### Acceptance criteria

- Inventory roll-forward reconciles
- Unclassified items are resolved or logged
- Audit samples identify user and change
- Corrective actions have owner and due date

Files: `activities/activity-06-inventory-classes-audit/`


## Topic 3: Manage Goods and Services Tax (GST)

**Alignment:** A3 · K3 · K4 · Singapore GST · tax coding · input/output tax · GST F5 review

### Key concepts

- GST-registered businesses charge output tax and may claim eligible input tax under IRAS rules.
- Use the correct current QuickBooks tax code for standard-rated, zero-rated, exempt and out-of-scope items.
- Reconcile GST detail, exception and control accounts before preparing GST F5 figures.
- Escalate uncertain treatments; accounting software supports preparation but does not replace tax advice.

### GST in the value chain

- Supplier charges input GST
- Business records purchase
- Business charges output GST
- Net amount settles with IRAS

### Current Singapore GST rate

- The standard rate is 9% at publication; always verify time-sensitive tax rates and rules with IRAS.

### Taxable and non-taxable treatment

- Standard-rated supply
- Zero-rated supply
- Exempt supply
- Out-of-scope transaction

### Output tax and input tax

- Output tax is collected on taxable sales
- Input tax may be claimable on eligible business purchases
- Net output above input generally means payable
- Net input above output may mean refundable, subject to IRAS rules

### GST control formula

- Taxable value
- Apply correct rate
- GST amount
- Gross amount
- Return box

### Tax-inclusive and tax-exclusive amounts

- Exclusive: GST = net × rate
- Inclusive: GST = gross × rate ÷ (1 + rate)
- Rounding policy must be consistent
- Source document must support treatment

### GST coding decision

- Identify supply
- Check registration/date
- Determine place/type
- Select current code
- Review exception

### GST on sales

- Correct supply category
- Valid tax invoice information
- Credit note reverses original treatment
- Foreign-currency conversion is documented

### GST on purchases

- Business purpose
- Valid supporting document
- Claim eligibility
- Correct period and tax code

### Common GST coding risks

- Using standard rate by default
- Claiming blocked/private expenses
- Mixing exempt and out-of-scope
- Back-dated changes after filing

### GST control accounts

- Output GST collected
- Input GST claimable
- GST payable/refundable
- Reconcile to GST detail and general ledger

### GST F5 preparation flow

- Lock period
- Run exception checks
- Review GST detail
- Reconcile control
- Prepare figures
- Approve and file

### Exception-report review

- Transactions without tax
- Unusual tax code by account
- Negative or duplicate amounts
- Changes to prior filed periods

### GST reconciliation

- Sales ledger
- Purchase ledger
- GST detail
- Control account
- GST return

### When errors are found

- Quantify affected periods
- Preserve an audit trail
- Correct through an approved method
- Consult current IRAS guidance

### Corporate tax context

- Accounting profit is not chargeable income
- Current corporate tax rate is 17%
- Tax adjustments and reliefs are time-sensitive
- Use IRAS guidance or a qualified adviser

### Records support compliance

- Source documents
- Ledger and reconciliations
- Approval evidence
- Filed return and payment evidence

### Topic 3 control checkpoint

- Correct GST reporting begins at transaction coding and ends with an evidenced reconciliation.

### Activity 07: Code and Validate GST Transactions

**Level:** Intermediate · **Duration:** 40 min · **Alignment:** A3 · K3 · K4

Apply and validate Singapore GST treatment across a mixed transaction set.

#### Detailed step-by-step procedure

1. Read the GST Scenario sheet and confirm the entity is GST-registered for the activity period.
2. Classify each source transaction as standard-rated, zero-rated, exempt, out-of-scope or requiring escalation.
3. Calculate expected GST for tax-exclusive and tax-inclusive examples using the workbook formulas.
4. Compare the expected treatment with the QuickBooks tax code available in the current Singapore company.
5. Enter or review the sample sales invoices and supplier bills using the approved tax codes.
6. Check that credit notes reverse the original GST treatment and period appropriately.
7. Review transactions without tax and unusual code-by-account combinations.
8. Trace a sample of input-tax claims to valid business-purpose supporting documents.
9. Record uncertain items in the Escalation Log rather than guessing a tax treatment.
10. Complete the GST Coding Review sign-off.

#### Acceptance criteria

- Every transaction has a supported classification
- Formula checks agree to system tax amounts
- Uncertain items are escalated
- Credits mirror original tax treatment

Files: `activities/activity-07-gst-coding-control/`


### Activity 08: Prepare the GST F5 Review Pack

**Level:** Advanced · **Duration:** 40 min · **Alignment:** A3 · K3 · K4

Reconcile GST ledgers and prepare a review pack for the quarterly GST return.

#### Detailed step-by-step procedure

1. Confirm the quarter, accounting basis and period lock in the GST Review workbook.
2. Run GST summary, GST detail and transactions-without-tax reports for the same period.
3. Reconcile taxable sales and purchases to the relevant P&L/ledger totals.
4. Reconcile output GST and input GST to the GST control accounts.
5. Investigate differences caused by dates, rounding, credits, journals or changes to prior periods.
6. Populate the F5 Control sheet from validated QuickBooks report totals; do not manually override formulas.
7. Trace at least three sales and three purchase items from report to source document.
8. Review the exception log and confirm that every material item is corrected or escalated.
9. Record the preparer and independent reviewer sign-off.
10. Retain the review pack; filing on myTax Portal is outside this training activity.

#### Acceptance criteria

- GST detail agrees to control accounts
- F5 control figures are formula-driven
- Sample evidence is traceable
- Preparer and reviewer sign-offs are complete

Files: `activities/activity-08-gst-f5-review/`


## Topic 4: Financial and Accounting Reports

**Alignment:** A4 · K5 · P&L · balance sheet · cash flow · ageing · GST · custom reports

### Key concepts

- Profit and Loss explains performance over a period; Balance Sheet explains position at a date.
- Cash flow, profit and working capital answer different management questions.
- AR/AP ageing turns overdue balances into collection and payment priorities.
- Report accuracy depends on reconciled source data, correct basis, period, filters and review evidence.

### Reports turn entries into decisions

- Transactions
- Ledgers
- Reconciliations
- Reports
- Management action

### Profit and Loss anatomy

- Revenue
- Less cost of sales
- Gross profit
- Less operating expenses
- Net profit

### P&L review questions

- Which revenue streams changed
- What drove gross margin
- Which expenses are unusual
- Are period and accounting basis correct

### Balance Sheet equation

- Assets = Liabilities + Owners' Equity

### Balance Sheet structure

- Current and non-current assets
- Current and non-current liabilities
- Equity and retained earnings
- Control accounts requiring reconciliation

### Balance Sheet limitations

- Snapshot at one date
- Book value may differ from market value
- Unrecorded intangibles may matter
- Classification quality affects interpretation

### P&L versus Balance Sheet

- P&L covers a period
- Balance Sheet is at a date
- Profit changes retained earnings
- Cash is not the same as profit

### Cash flow versus profit

- Profit uses accrual accounting
- Cash flow tracks cash movements
- Credit sales can raise profit before cash
- Asset purchases use cash but are not immediately expensed

### AR ageing

- Current
- 1–30 days overdue
- 31–60 days overdue
- 61+ days overdue

### Use ageing to manage credit

- Validate balances
- Segment risk
- Prioritise contact
- Record action
- Escalate dispute

### AP ageing

- Protect supplier terms
- Avoid duplicate payment
- Plan cash requirements
- Resolve disputed bills

### GST reports

- GST summary
- GST detail
- Exception report
- Return preparation view

### Report parameters matter

- Date range and as-of date
- Cash or accrual basis
- Classes, locations and filters
- Comparison period and rounding

### Custom reports

- Define decision
- Choose base report
- Set filters/columns
- Validate totals
- Save and schedule

### Scheduled reports need controls

- Review recipient access
- Use an approved cadence
- Protect confidential attachments
- Revalidate after chart/config changes

### Report validation

- Reconcile source
- Check parameters
- Scan anomalies
- Trace a sample
- Document reviewer

### SME management pack

- P&L with prior-period comparison
- Balance Sheet with key reconciliations
- AR/AP ageing and cash priorities
- GST position and exception log

### Topic 4 control checkpoint

- A report is decision-ready only when its source data, parameters and review are evidenced.

### Activity 09: Build and Interpret the SME Reporting Pack

**Level:** Advanced · **Duration:** 45 min · **Alignment:** A4 · K5

Generate, validate and interpret core financial and ageing reports.

#### Detailed step-by-step procedure

1. Confirm the reporting period, basis, comparison period, class/location filters and rounding convention.
2. Run the Profit and Loss report and compare revenue, gross margin and operating expenses with the workbook.
3. Run the Balance Sheet as at month-end and verify that Assets equal Liabilities plus Equity.
4. Reconcile cash, AR, AP, inventory and GST control accounts to their supporting schedules.
5. Run AR and AP Ageing Summary using the same as-of date.
6. Trace one material balance from each report to underlying transactions.
7. Customise and save a management report with relevant columns and comparison data.
8. Identify three business insights and distinguish an observation from a supported conclusion.
9. Assign an owner, action and due date to each material issue.
10. Complete the Report Validation checklist and reviewer sign-off.

#### Acceptance criteria

- Report parameters are consistent
- Balance Sheet equation holds
- Control accounts reconcile
- Insights link to evidence and actions

Files: `activities/activity-09-financial-reporting-pack/`


### Activity 10: Capstone: Complete the Month-End Close

**Level:** Advanced · **Duration:** 55 min · **Alignment:** A1 · A2 · A3 · A4 · K1–K5

Complete a controlled month-end close for Orchid Bay Trading Pte Ltd and present a decision-ready management brief.

#### Detailed step-by-step procedure

1. Accept the capstone handover and verify the source-file inventory against the Intake Register.
2. Import or review outstanding master-data and bank items, resolving only approved exceptions.
3. Complete the sales and purchase cut-off checks and identify missing or duplicate transactions.
4. Reconcile the operating and reserve bank accounts without forced balancing entries.
5. Reconcile AR, AP and inventory control totals to their supporting schedules.
6. Complete the GST coding scan and GST control-account reconciliation.
7. Run P&L, Balance Sheet, Cash Flow, AR/AP Ageing and GST reports using controlled parameters.
8. Investigate the seeded anomalies listed in the workbook and document each resolution.
9. Prepare a one-page management brief covering performance, cash, overdue balances, GST position and top actions.
10. Obtain peer reviewer sign-off against the acceptance criteria and preserve the final evidence set.

#### Acceptance criteria

- All five control accounts reconcile
- Seeded anomalies are found and resolved
- GST and reporting packs are supported
- Management brief contains evidence-backed actions

Files: `activities/activity-10-month-end-capstone/`
