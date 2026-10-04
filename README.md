# Grave Grip

Static product page for the Grave Grip skeleton-hand drink holder. Deploys to Vercel as-is (no build step).

## Turn on checkout
Open `index.html`, find `const STRIPE_LINK = "";` and paste the Stripe Payment Link URL between the quotes.
The selected color is sent to Stripe as `client_reference_id` (rainbow, bone, midnight, blood, glow, violet, pumpkin), so each order shows its color in the Stripe dashboard.

## Change the price
Search `index.html` for `$25` and update it in the page text and button, then change the price on the Stripe Payment Link to match.
