---
name: accounting-subscriptions
description: "Subscriptions: How long a subscription with an unpaid invoice stays past due before it is cancelled, Set how long a subscription with an unpaid invoice stays past due before it is cancelled, List subs"
---

# Subscriptions

- `subscription_settings_read`: How long a subscription with an unpaid invoice stays past due before it is cancelled
- `subscription_settings_save`: Set how long a subscription with an unpaid invoice stays past due before it is cancelled
- `subscriptions_get_subscriptions`: List subscriptions
- `subscriptions_create_subscription`: Create a new subscription
- `subscriptions_get_subscription`: Get subscription by ID
- `subscriptions_edit_subscription`: Update a subscription
- `subscriptions_delete_subscription`: Delete a subscription
- `subscriptions_bill_subscription`: Immediately bill a subscription
- `subscriptions_cancel_subscription`: Cancel a subscription (immediate or at period end)
- `subscriptions_change_plan`: Change subscription bundle (upgrade/downgrade)
- `subscriptions_apply_coupon`: Apply a coupon to a subscription
- `subscriptions_remove_coupon`: Remove a subscription's coupon
- `subscriptions_get_subscription_history`: Get subscription lifecycle history
- `subscriptions_pause_subscription`: Pause a subscription
- `subscriptions_renew_subscription`: Renew a subscription now
- `subscriptions_resume_subscription`: Resume a paused subscription
