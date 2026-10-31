---
name: accounting-sale-invoices
description: "Sale Invoices: List all sale invoices with pagination, Create a new sale invoice, Delete multiple sale invoices, List the invoices with money owed on them"
---

# Sale Invoices

- `sale_invoices_get_sale_invoices`: List all sale invoices with pagination
- `sale_invoices_create_sale_invoice`: Create a new sale invoice
- `sale_invoices_bulk_delete_sale_invoices`: Delete multiple sale invoices
- `sale_invoices_get_receivable_invoices`: List the invoices with money owed on them
- `sale_invoices_get_receivables_summary`: What customers owe on unpaid invoices, per currency
- `sale_invoices_validate_bulk_delete_sale_invoices`: Validate which sale invoices can be deleted
- `sale_invoices_get_sale_invoice`: Get sale invoice details with entries
- `sale_invoices_edit_sale_invoice`: Edit the given sale invoice
- `sale_invoices_delete_sale_invoice`: Delete the given sale invoice
- `sale_invoices_deliver_sale_invoice`: Deliver the given sale invoice
- `sale_invoices_get_invoice_payments`: Retrieve invoice associated payment transactions
- `invoice_send_send`: Send the sale invoice to its customer
- `sale_invoices_void_sale_invoice`: Void the given sale invoice
- `sale_invoices_writeoff_sale_invoice`: Write off the given sale invoice as bad debt
- `sale_invoices_cancel_writeoff_sale_invoice`: Cancel the write-off of the given sale invoice
