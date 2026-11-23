# Deshmukh Softwares

A responsive starter storefront for a software marketplace.

## Current state

- Static HTML/CSS/JavaScript starter in `index.html`.
- Responsive desktop/mobile layout.
- English/Hindi text toggle.
- Search and category/platform/price filters using clearly labelled sample listings.
- Free and paid listing presentation.
- Developer submission and sign-in preview dialogs.

## Important limitations

This repository currently contains a **front-end prototype only**. It does not yet include:
- Real user accounts, authentication, or owner/admin permissions.
- Database, developer profiles, upload storage, malware scanning, or moderation workflow.
- Real downloadable software packages.
- Cashfree checkout, Easy Split vendor onboarding, webhook verification, refunds, or payouts.
- Production analytics or email notifications.

Do not collect bank details or payment credentials in this static site. Do not treat sample listings, buttons, or preview forms as live functionality.

## Publish a preview with GitHub Pages

1. Open the repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then save.
4. Wait for GitHub Pages to finish deploying and open the URL shown on the Pages settings screen.

GitHub Pages serves only the static front end. A separate trusted backend (for example, Supabase plus secure server/edge functions) is required before real accounts, uploads, admin controls, and payments can go live.

## Next development stages

1. Add a database schema and secure authentication with verified owner role.
2. Add private object storage, file type/size checks, malware scanning, and owner approval.
3. Add order ledger and Cashfree payment verification on the server.
4. Integrate Cashfree Easy Split only after merchant approval, feature activation, vendor KYC, and credentials are available.
5. Test free downloads, paid checkout, refunds, failed/pending states, and settlement reconciliation before launch.
