---
name: accounting-orders
description: "Orders: List orders, Create a new order, Get order by ID with entries, Update a draft order"
---

# Orders

- `orders_get_orders`: List orders
- `orders_create_order`: Create a new order
- `orders_get_order`: Get order by ID with entries
- `orders_edit_order`: Update a draft order
- `orders_delete_order`: Delete a draft order
- `orders_cancel_order`: Cancel an order
- `orders_confirm_order`: Confirm an order (triggers invoice generation)
- `orders_fulfill_order`: Deliver every line of the order left
- `orders_fulfill_lines`: Deliver some lines of the order
- `orders_get_order_invoice`: Get the linked invoice for an order
- `orders_get_refund_options`: What the order can still be refunded, and how
- `orders_list_refunds`: The order's refunds
