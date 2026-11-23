# Deshmukh Softwares

A responsive software-discovery marketplace front-end.

## Current published front-end

- Premium, responsive marketplace layout for desktop and mobile.
- English/Hindi language toggle.
- Search plus category, platform and price filters.
- Clearly labelled sample software cards.
- Developer submission and sign-in preview dialogs.
- PWA manifest, install prompt support and service worker for an app-like website install.

## Important: prototype vs production

This GitHub Pages project is a **front-end preview**, not yet a production marketplace. Sample listings are not real downloadable software. Sign-in and submission dialogs are previews only.

Not connected yet:
- Real user accounts, secure authentication, database, owner/admin roles.
- Developer profiles, private file uploads, malware scanning, moderation and real download hosting.
- Cashfree checkout, Easy Split vendor onboarding, signed webhook verification, refunds, commission ledger or payouts.
- Production visitor analytics, sales dashboard or notifications.

Never place Cashfree secret keys, passwords, bank details, or private API credentials in this public repository. Never collect bank details in a static HTML form.

## Cashfree marketplace payment design

Cashfree Easy Split is the intended marketplace flow: customer checkout, commission calculation, vendor share, settlement, refund adjustments and reconciliation. It requires server-side integration, merchant approval/feature activation, vendor onboarding/KYC and secure credentials. The website must verify payment status from the backend/webhook before releasing paid downloads. See Cashfree's official [Easy Split documentation](https://www.cashfree.com/docs/api-reference/payments/latest/split/easy-split-overview).

## Production work still required

1. Choose and configure a trusted backend/database and private object storage.
2. Implement verified login, developer roles, owner-only admin access and audit logs.
3. Add software upload validation, malware scanning, owner approval and signed download links.
4. Integrate Cashfree order creation and payment verification on the server, plus verified webhooks.
5. Enable Easy Split only after Cashfree approves the merchant and vendor setup; implement commission, refunds, settlement and reconciliation.
6. Test successful, failed, pending, refunded and disputed payments before accepting real orders.

GitHub Pages serves the static front-end only; it cannot safely store Cashfree secrets or run the required private payment backend.
