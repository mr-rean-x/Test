# TRUSTED USDT INVEST — Final static Vercel/GitHub demo

This version is dependency-free: upload the files to GitHub and deploy as a static site on Vercel.

## Working demo features
- Register / login / logout
- User dashboard
- Plan selection
- Payment submission with screenshot preview/storage in browser
- Transaction history
- Withdrawal request
- Referral page
- Profile settings
- Admin login
- Admin dashboard
- Payment filtering
- Payment detail + screenshot preview
- Confirm / reject payment
- User suspend / unsuspend
- Responsive UI

## Admin credentials
The real password is intentionally NOT included in this ZIP, because putting a password in a public GitHub repository would expose it.

Edit `config.js` before deploying:
- `adminUser` = your admin username
- `adminPassword` = your admin password

## Vercel
No build command is needed. Import the GitHub repo into Vercel as a static project and deploy.

## Important
This is a browser-only demo. Data is stored in localStorage, so it is not a real multi-user database and does not process, custody, or transfer cryptocurrency. Do not use it to accept real funds or advertise guaranteed investment returns. A production system needs server-side authentication, a real database, private file storage, blockchain verification, audit logging and applicable legal/compliance controls.
