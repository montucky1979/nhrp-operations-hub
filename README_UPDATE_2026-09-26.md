# NHRP Operations Hub Update — 2026-09-26

## Added / changed
- Screenshot fields now support direct clipboard paste with Ctrl+V.
- Payment Logs now use the same screenshot paste/upload control.
- New T/Codes page: Code, Description, Category, one-click Copy.
- Categories/types/ranks can be managed from each applicable tab without changing website code.
- Spawn Code categories are now a dropdown instead of permanent tabs.
- Owner and Executive are the delete roles across record tables.
- Reports removed from navigation for now.

## IMPORTANT — run SQL first
In Supabase > SQL Editor > New Query, run:
`supabase/NHRP_FEATURES_2026-09-26.sql`

## GitHub upload
Upload/replace the contents of this folder in your existing `nhrp-server-management` repo.
Keep your current working `config.js`; this package does not include it.

Cloudflare should redeploy automatically after the GitHub commit. Then press Ctrl+F5.
