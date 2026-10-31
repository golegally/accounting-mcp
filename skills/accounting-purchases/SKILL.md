---
name: accounting-purchases
description: "Purchases: List all bills, Create a new bill, Delete multiple bills, Retrieve due (unpaid) bills"
---

# Purchases

- `bills_get_bills`: List all bills
- `bills_create_bill`: Create a new bill
- `bills_bulk_delete_bills`: Delete multiple bills
- `bills_get_due_bills`: Retrieve due (unpaid) bills
- `bills_validate_bulk_delete_bills`: Validate which bills can be deleted
- `bills_get_bill`: Get bill details with entries
- `bills_edit_bill`: Edit the given bill
- `bills_delete_bill`: Delete the given bill
- `bills_open_bill`: Open the given bill
- `bills_get_bill_payment_transactions`: Retrieve bill associated payment transactions
- `expenses_get_expenses`: Retrieve all expense transactions
- `expenses_create_expense`: Create a new expense transaction
- `expenses_bulk_delete_expenses`: Delete multiple expenses
- `expenses_validate_bulk_delete_expenses`: Validate which expenses can be deleted
- `expenses_get_expense`: Get expense transaction by ID
- `expenses_edit_expense`: Edit an existing expense transaction
- `expenses_delete_expense`: Delete an expense transaction
- `expenses_publish_expense`: Publish a draft expense (writes GL entries)
