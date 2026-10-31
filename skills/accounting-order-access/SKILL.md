---
name: accounting-order-access
description: "Order Access: The grant a buyer holds, by checkout or by order, to extend or rotate when they have lost their link; never returns a to, Claim completed checkout for order-only buyer access; retry usin"
---

# Order Access

- `order_access_find`: The grant a buyer holds, by checkout or by order, to extend or rotate when they have lost their link; never returns a to
- `order_access_exchange`: Claim completed checkout for order-only buyer access; retry using the same merchant-generated token.
- `order_access_invoice_document`: Expiring link to the tax invoice document for an invoice of the grant's own order.
- `order_access_resolve`: Validate buyer grant and read only its order, invoice and allocated payments.
- `order_access_revoke`: Revoke buyer order access; checkout exchange cannot undo revocation.
- `order_access_extend`: Keep the buyer's existing link working for longer; the token is unchanged, and a revoked grant stays revoked.
- `order_access_rotate`: Merchant-only recovery with a fresh token; invalidates the previous token and grant id.
