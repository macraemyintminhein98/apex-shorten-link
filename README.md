# APEX Short URLs

A dead-simple, blazing-fast URL shortener. No accounts needed for the free tier. 

**Go Pro for a one-time $9.99 payment** to unlock custom domains (e.g., `brand.com/shortlink`) and basic analytics.

Built for small businesses, content creators, and anyone needing quick, professional links without monthly subscriptions or complex setups.

## Features:
*   **Free:** Instant URL shortening.
*   **Pro ($9.99 one-time):**
    *   Custom domains (e.g., yourcompany.com/my-link)
    *   Basic click analytics
    *   Instant access upon payment via Stripe.

## Getting Started (Local Development):

**Note:** This `index.html` is a frontend-only representation. A full backend (Next.js, Supabase/PlanetScale, Stripe) is required for full functionality.

To run this `index.html` locally:
1.  Save the `index.html` content to a file named `index.html`.
2.  Open the file in your web browser.

For a full build, you would implement:
*   **Frontend:** React/Next.js for the UI.
*   **Backend:** Next.js API routes or a dedicated serverless function.
*   **Database:** Supabase or PlanetScale for URL mapping and analytics.
*   **Payments:** Stripe Checkout for Pro tier purchases.
