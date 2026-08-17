# Brew & Bloom Complete Café Website

## Included
- Customer-facing café website
- Menu, contact, booking form
- Owner signup/login
- Secure password hashing with bcrypt
- JWT owner authentication
- Owner dashboard
- Reservation list per café
- Confirm/cancel reservation
- New-reservation alert in dashboard
- Café-specific owner ID for bookings
- Responsive mobile layout
- Local JSON database for demo/testing

## Run locally
Install Node.js 18+.
Then:
1. `npm install`
2. `npm start`
3. Open `http://localhost:3000`
4. Owner dashboard: `http://localhost:3000/admin`

## Test on two phones
A local computer server is not automatically reachable from the internet. For two phones, deploy this project to a Node hosting service and use a hosted database. Then both devices use the same URL and database.

## Production requirements
Before selling to a real café, use a managed database, HTTPS, strong JWT secret, rate limiting, backups, server-side validation, password reset, privacy policy, and real notification delivery (email/WhatsApp/SMS). Do not store production secrets in source code.
