<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@stripe/firestore-stripe-payments](./firestore-stripe-payments.md) &gt; [Subscription](./firestore-stripe-payments.subscription.md) &gt; [canceled\_at](./firestore-stripe-payments.subscription.canceled_at.md)

## Subscription.canceled\_at property

If the subscription has been canceled, the date of that cancellation as a UTC timestamp. If the subscription was canceled with [Subscription.cancel\_at\_period\_end](./firestore-stripe-payments.subscription.cancel_at_period_end.md)<!-- -->, this field will still reflect the date of the initial cancellation request, not the end of the subscription period when the subscription is automatically moved to a canceled state.

<b>Signature:</b>

```typescript
readonly canceled_at: string | null;
```