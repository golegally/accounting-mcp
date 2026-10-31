---
name: accounting-product-prices
description: "Product Prices: List all active prices (with product info) — single batch call, What rules not yet saved would charge, and how many they would allow, Get price details, Edit mutable fields of a price "
---

# Product Prices

- `product_prices_list_all`: List all active prices (with product info) — single batch call
- `product_prices_preview_rules`: What rules not yet saved would charge, and how many they would allow
- `product_prices_get_price`: Get price details
- `product_prices_edit_price`: Edit mutable fields of a price (nickname, description, active, metadata)
- `product_prices_archive_price`: Archive a price (soft delete)
- `product_prices_preview`: What this price would charge for a purchase like this, and how many may be bought
- `product_prices_get_rules`: List the rules of a price that works out its own amount
- `product_prices_set_rules`: Replace a price's rules (idempotent; order is the order invoiced)
- `product_prices_get_tiers`: List pricing tiers for a price
- `product_prices_set_tiers`: Replace all pricing tiers for a price (idempotent)
