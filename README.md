# UAE POS Tax & Currency Utility

A mobile-first Progressive Web App (PWA) for UAE point-of-sale workflows:
- **Tax Refund (Planet Tax Free)**: Calculates net price excluding 5% VAT, VAT paid, AED 4.80/tag fee adjustment, 85% tourist refund estimate, AED 250 eligibility threshold, and converted refund amount.
- **Live Currencies**: Tracks 13+ currencies against AED with auto-refreshing rates, manual rate overrides, and searchable world country additions.
- **Installments (EPP)**: Calculates monthly payments across 3, 4, 6, 8, 9, and 12 months with configurable monthly fee tiers.

## Deploy on GitHub Pages
1. Create a new GitHub repository (for example, `uae-pos-utility`).
2. Upload `index.html`, `manifest.json`, `icon.svg`, and `sw.js` to the root of the repository (or push via Git).
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**, choose **`main`** and **`/(root)`**, then click **Save**.
5. Open your live URL (`https://<your-username>.github.io/<repo-name>/`) on mobile or desktop and tap **Add to Home Screen** / **Install App**.
