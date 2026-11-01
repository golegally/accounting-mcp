# GoLegally Accounting

Invoices, bills, contacts, products, payments and reports in GoLegally Accounting.

## How it works

This package connects your AI assistant to one hosted MCP server at https://golegally-accounting.mcp.pretuned.ai/mcp. It runs nothing on your computer. Your requests and the data they return go between your assistant and that server, and you sign in before it can reach your account.

## Skills

- **accounting-accounts**: Accounts: List all accounts, Create a new account, Delete multiple accounts, Retrieve account transactions (GL ledger entries)
- **accounting-audit-logs**: Audit Logs: List all audit logs (paginated), Get audit trail for a specific entity
- **accounting-banking**: Banking: List all bank accounts, Create a bank account for reconciliation, Get bank account by ID, Edit a bank account
- **accounting-banking-apply**: Banking apply: Apply the bank rules to uncategorised lines
- **accounting-banking-auto-match**: Banking auto match: Auto-match pending transactions against GL entries
- **accounting-banking-categorization**: Banking categorization suggestions: What uncategorised bank lines most likely are
- **accounting-banking-reconcile**: Banking reconcile: Reconcile selected bank transactions
- **accounting-banking-reconciliation-summary**: Banking reconciliation summary: Get reconciliation summary for a bank account
- **accounting-banking-reconciliations**: Banking reconciliations: A bank account's reconciliations, newest first, A reconciliation's report: its figures and the lines it cleared, Undo the latest reconciliation
- **accounting-banking-reorder**: Banking reorder: Put the bank rules in order
- **accounting-banking-statements**: Banking statements: Import a bank statement file, Read a bank statement file
- **accounting-banking-transactions**: Banking transactions: Get a single bank transaction, Delete a bank transaction, Categorise a bank line, Exclude a bank transaction from reconciliation
- **accounting-bill-landed-costs**: Bill Landed Costs: List landed costs for a bill, Allocate landed cost to a bill, Revert (delete) a landed cost allocation
- **accounting-bill-payments**: Bill Payments: List all bill payments, Create a new bill payment, Delete multiple bill payments, Validate which bill payments can be deleted
- **accounting-budgets**: Budgets: List budgets, Create a budget (draft), Get budget with entries, Edit budget metadata
- **accounting-bundles**: Bundles: List bundles, Create a new bundle, Get bundle by ID, Update a bundle
- **accounting-checkoutanalytics**: CheckoutAnalytics: Each brand's checkout analytics, Set the tags a brand's hosted checkout loads, and when it asks the buyer first, The analytics and advertising providers a hosted checkout can load
- **accounting-checkoutsettings**: CheckoutSettings: Each brand's checkout settings, A brand's checkout settings, Save a brand's checkout settings, Reset a brand's checkout settings
- **accounting-contacts**: Contacts: List contacts with pagination, Create a new contact (customer or vendor), Delete multiple contacts, Get a contact by the id it has in the system it came from
- **accounting-coupons**: Coupons: List coupons, Create a coupon, Apply a coupon, counting the redemption, Check whether a coupon code may be used, without redeeming it
- **accounting-credit-notes**: Credit Notes: List all credit notes, Create a new credit note, Delete multiple credit notes, Validate which credit notes can be deleted
- **accounting-currencies**: Currencies: Retrieve all currencies, Create a new currency, List exchange rates with optional filtering, Create a new exchange rate entry
- **accounting-currency-revaluation**: Currency Revaluation: List all revaluations for the organization, Preview revaluation without posting (dry run), Run currency revaluation and post GL entries, Get revaluation with entry details
- **accounting-customer-credits**: Customer Credits: Get customer credit balances, Apply customer credit balance to an invoice, Take a credit application back off its invoice, Top up customer credit balance
- **accounting-deferred-revenue**: Deferred Revenue: Revenue invoiced but not yet earned, Process pending revenue recognition entries, List deferred revenue schedules, Get deferred revenue schedule with entries
- **accounting-document-reporting**: Document Reporting: Whether a registration reports its invoices to the tax authority, Report an issued invoice to the tax authority, Cancel an invoice's report at the tax authority, voiding the invoic
- **accounting-documentnumberformats**: DocumentNumberFormats: How each document type is numbered, Set a document type's number format, Reset a document type's number format
- **accounting-entitlements**: Entitlements: Get the entitlements of a customer known by their reference, Get a customer's entitlements, List default plans, List features
- **accounting-expense-claims**: Expense Claims: List expense claims, Record an expense an employee paid for, Employee balances, List reimbursements
- **accounting-export**: Export: Export a resource as CSV or XLSX
- **accounting-fixed-assets**: Fixed Assets: List fixed assets, Register a fixed asset, Charge depreciation, Fixed asset register
- **accounting-gatewaysettlement**: GatewaySettlement: List recorded settlements, Record a settlement a payment account has paid out, Captured payments not yet settled, by payment account
- **accounting-gl-journal-audit-trail**: GL Journal (Audit Trail): Get GL audit trail for a date range (period reconstruction), Get GL audit trail for a specific entity
- **accounting-import**: Import: Upload import file, Download import sample sheet, Get import file metadata, Process and commit import
- **accounting-india-gst**: India GST: Get org GST profile, Save org GST profile, GSTR-1 return data, Prepare GSTR-1 as Excel (GSTN template)
- **accounting-inventory-adjustments**: Inventory Adjustments: List all inventory adjustments, Create an inventory adjustment, Delete multiple inventory adjustments, Validate which inventory adjustments can be deleted
- **accounting-items**: Items: Get items inventory valuation list, List inventory products with their stock, Every inventory product's stock, added up, List a product's units by serial number
- **accounting-manual-journals**: Manual Journals: Retrieves the manual journals list., Create a new manual journal., Delete multiple manual journals, Validate which manual journals can be deleted
- **accounting-metered-billing**: Metered billing: Allow one metered run and record it; idempotent by reference, Bill a customer's unbilled usage now instead of at renewal, What each metered thing costs, by product code, The run did n
- **accounting-movement-documents**: Movement Documents: The government's document a supplier generated for a bill's goods, Find at the government the document for a bill's goods, Reject the document a supplier generated for a bill's goo
- **accounting-opening-balances**: Opening balances: Get the opening balances, Set the accounts' opening balances, Carry in an open bill, Remove an opening bill
- **accounting-order-access**: Order Access: The grant a buyer holds, by checkout or by order, to extend or rotate when they have lost their link; never returns a to, Claim completed checkout for order-only buyer access; retry usin
- **accounting-order-lines**: Order Lines: Set an order line's quantity; the catalogue prices the added units
- **accounting-order-payment-schedule**: Order Payment Schedule: The order's payment schedule, in its own order, Cancel a pending scheduled row
- **accounting-ordercharges**: OrderCharges: Every invoice of the order with its open link, and the order's outstanding total
- **accounting-orders**: Orders: List orders, Create a new order, Get order by ID with entries, Update a draft order
- **accounting-payment-receives**: Payment Receives: List all payments, Create a new payment received, Delete multiple payments, Tax customers withheld from their payments
- **accounting-payment-reminders**: Payment reminders: A customer's notifications, Exclude a customer from payment reminders and invoice messages, or include them again, Exclude an invoice from payment reminders, or include it again, Wh
- **accounting-payment-terms**: Payment terms: A customer's commitments, latest first, Record a commitment and invoice the part of it already due, A customer's payment terms, and what they have paid in, owe, used and may still spend
- **accounting-paymentaccounts**: PaymentAccounts: The organization's payment accounts, without their keys, Add a payment account, The accounts each brand takes payments with, Choose the accounts a brand takes payments with
- **accounting-paymentgatewayconfig**: PaymentGatewayConfig: The payment providers this engine can take payments through
- **accounting-paymentgatewayinvoice**: PaymentGatewayInvoice: Verify a gateway payment against an invoice and record what it collected
- **accounting-paymenttransactions**: PaymentTransactions: Get one payment transaction, Close a payment attempt that will not be completed, Ask the gateway what became of this attempt, and record its answer
- **accounting-payroll-journals**: Payroll Journals: List payroll journals, Book a payroll journal, List saved payroll columns, Preview a payroll journal
- **accounting-pdf-generation**: PDF Generation: Generate a bill PDF and return a presigned S3 URL, Generate a credit note PDF and return a presigned S3 URL, Generate a payment received PDF and return a presigned S3 URL, Generate a s
- **accounting-period-close**: Period Close: The close checklist for a period
- **accounting-prepaid-expenses**: Prepaid Expenses: List prepaid expense schedules, Spread a bill line over the months it pays for, Get a prepaid expense schedule with its monthly shares, Remove a prepaid expense schedule
- **accounting-product-categories**: Product Categories: Retrieve all product categories, Create a new product category, Delete multiple product categories, Validate which product categories can be deleted
- **accounting-product-prices**: Product Prices: List all active prices (with product info) — single batch call, What rules not yet saved would charge, and how many they would allow, Get price details, Edit mutable fields of a price 
- **accounting-products**: Products: Retrieves the product list, Create a new product, Delete multiple products, Validate which products can be deleted
- **accounting-purchase-attributes**: Purchase Attributes: List the facts a purchase can declare, Define a fact price rules can read, Edit a fact's question, answers or order (its key and type are fixed), Undefine a fact no price prices b
- **accounting-purchases**: Purchases: List all bills, Create a new bill, Delete multiple bills, Retrieve due (unpaid) bills
- **accounting-recurring-invoices**: Recurring Invoices: List recurring invoice templates, Create a recurring invoice template, Get a recurring invoice template by ID, Edit a recurring invoice template
- **accounting-recurring-journals**: Recurring Journals: List recurring journal templates, Create a recurring journal template, Get a recurring journal template by ID, Edit a recurring journal template
- **accounting-reports**: Reports: Get balance sheet statement, Validate balance sheet equation — A = L + E + (I − X), Get cash flow statement, Get customer balance summary report
- **accounting-sale-estimates**: Sale Estimates: List all sale estimates, Create a new sale estimate, Delete multiple sale estimates, Validate which sale estimates can be deleted
- **accounting-sale-invoices**: Sale Invoices: List all sale invoices with pagination, Create a new sale invoice, Delete multiple sale invoices, List the invoices with money owed on them
- **accounting-sale-receipts**: Sale Receipts: List all sale receipts, Create a new sale receipt, Delete multiple sale receipts, Validate which sale receipts can be deleted
- **accounting-settings**: Settings: Get the organization's settings, Whether the organization can issue documents, Get all settings for a group, Set a setting value
- **accounting-subscription-add-ons**: Subscription Add-ons: List all add-ons for a subscription (pending + billed history), List only pending (unbilled) add-ons for a subscription (paginated), Cancel a pending add-on (only works if not ye
- **accounting-subscriptions**: Subscriptions: How long a subscription with an unpaid invoice stays past due before it is cancelled, Set how long a subscription with an unpaid invoice stays past due before it is cancelled, List subs
- **accounting-supplier-credits**: Supplier Credits: List supplier credits, Create a supplier credit, Delete multiple supplier credits, Validate which supplier credits can be deleted
- **accounting-supplier-documents**: Supplier Documents: A bill beside its supplier's document at the government, Accept, reject or keep pending a bill's supplier's document, Check the answer sent for a bill's supplier's document, Read a
- **accounting-tax-code-rates**: Tax Code Rates: The rates of the organization's tax codes, per country and period, Give a tax code a rate in a country from a day, End a tax code rate, or change its reverse-charge accounts, Delete a 
- **accounting-tax-rates**: Tax Rates: Retrieves the tax rates, Create a new tax rate, Delete multiple tax rates, Validate which tax rates can be deleted
- **accounting-tax-returns**: Tax returns: Tax returns for a month, Give an amount a return asks for, for a financial year
- **accounting-taxresolution**: TaxResolution: The tax codes a product can be classified under, Add the tax codes this organisation is missing, Resolve the tax treatment for one sale or purchase, Resolve the tax treatment for many l
- **accounting-transactions-locking**: Transactions Locking: Get all transactions locking meta, Cancel all transactions locking for a module or all modules, Cancel partial unlocking all transactions locking for a module or all modules, Loc
- **accounting-usagerecords**: UsageRecords: List the usage recorded against a subscription, Record metered usage against a subscription, Usage recorded against a subscription, totalled by metric
- **accounting-vendor-advances**: Vendor Advances: List movements of vendor advances, Get a vendor's advances, Record an advance paid to a vendor, Apply a vendor's advance to their bills
- **accounting-warehouse-transfers**: Warehouse Transfers: List warehouse transfers, Create a warehouse transfer (draft), Get warehouse transfer details, Edit a warehouse transfer (draft only)
- **accounting-warehouses**: Warehouses: List warehouses, Create a warehouse, Get warehouse details, Edit a warehouse
- **accounting-withholding-tax**: Withholding Tax: What a vendor can be paid for that tax is deducted from

## Publisher

Published by Vadavision Private Limited.

Support: https://golegally.com/contact

Privacy: https://golegally.com/privacy

Terms: https://golegally.com/terms
