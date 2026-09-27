# NHRP Operations Hub — Add-Ins + Coin Collection Update

## Changes in this build

- Payment Logs are no longer a separate user-facing tab.
- **Add-Ins** is the single place for:
  - Discord Name
  - Discord ID
  - Type
  - Spawn Code
  - Date
  - Payment Method
  - Amount
  - Activity Check Date
  - Status
  - Notes
  - Screenshot
  - 30-Day Activity Check + History
- Added **Coin Collection** tab with:
  - Username
  - Total Coins
  - Collected checkbox
  - Outstanding / Collected / All filters
  - Search
  - Import / Export
  - Summary totals
- Loaded 837 usernames from the supplied coin list.
- Reports remain removed.
- The NHRP logo remains embedded directly in `index.html` so it does not depend on a file path.
- Existing `payments` table is left in Supabase so no historical data is deleted. It is simply no longer shown in the main UI.

## Deploy

1. In the SAME Supabase project used by the Operations Hub, run:
   `supabase/NHRP_FINAL_DEPLOY_UPDATE_2026-09-26_V2.sql`
2. Upload the contents of this folder to the root of the existing GitHub repo.
3. Keep the existing working `config.js`; this ZIP does not include it.
4. Let Cloudflare Pages redeploy.
5. Use Ctrl+F5 on the live site.
