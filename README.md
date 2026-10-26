# Savings Group Manager UG

Mobile-friendly, offline-first savings ledger prototype for Uganda.

## Version 0.1
- Member registration with unique reference codes
- UGX contribution entry and member balances
- Dashboard with recent contributions
- CSV export, JSON backup and restore
- Basic offline app shell through a service worker (requires HTTPS or localhost; first visit online)

## Run
Open `index.html` in a browser for basic use. For offline installation, serve via localhost or HTTPS (e.g. VS Code Live Server or GitHub Pages).

## Important limitations
This is a **single-browser prototype**, not production financial software. Data lives only in localStorage, is not encrypted or synchronized, and can be lost when browser storage is cleared. Do not enter real member identities or sensitive financial records. No login, roles, tamper-resistant audit, loan handling, mobile money or cloud backup yet. Test with fictional data only.

## Next steps
Loans and repayments, transaction corrections, group configuration, multi-user accounts, database security and independent testing before real-world use.
