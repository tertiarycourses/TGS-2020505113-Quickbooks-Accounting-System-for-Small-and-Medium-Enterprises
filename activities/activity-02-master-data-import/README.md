# Activity 02: Clean and Import Master Data

**Scenario:** Orchid Bay Trading Pte Ltd  
**Level:** Foundation · **Duration:** 45 min · **Alignment:** A1 · K1

## Business objective

Prepare, validate and import the chart of accounts, customers, suppliers and products/services.

## Files

- `Activity-02-Control-and-Evidence.xlsx` — intake, control checks, evidence and exception log
- `Activity-02-QuickBooks-Import-Source.csv` — realistic mock source data; import only when the procedure calls for it

## Detailed step-by-step procedure

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

## Evidence to submit

- Completed control-and-evidence workbook
- Relevant QuickBooks report(s) or screenshots without personal data
- Completed exception/decision log
- Reviewer sign-off

## Acceptance criteria

- [ ] All source files pass the quality checks
- [ ] Counts reconcile before and after import
- [ ] No duplicate display names remain
- [ ] Account and item mappings are supportable

## Safety and privacy

Use only the trainer-provided training company and mock data. Do not upload real customer, supplier, employee, bank or tax data. Do not invite real external users.