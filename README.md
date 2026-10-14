# ONYX VIP — starter project

Responsive black-and-gold Next.js starter for Safari/mobile/desktop. This package is a visual and interaction prototype only. It does not implement real-money gambling, deposits, withdrawals, production authentication, KYC, or certified RNG.

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Project files

- `app/page.tsx` — landing page, demo profile panel, demo slots and virtual coin counter.
- `app/globals.css` — responsive black/gold design.
- `app/layout.tsx` — app metadata and global stylesheet.
- `.env.example` — placeholder environment variables; no real secrets.

## Production work required before real-money launch

1. Confirm target countries and obtain specialist legal advice for each market. A foreign licence does not automatically authorize every country.
2. Incorporate the operating entity and complete the applicable licensing application.
3. Select a regulator-accepted game/RNG provider and complete required technical certification and system audit.
4. Implement secure server-side authentication, MFA/admin controls, account recovery and session management.
5. Integrate approved age/identity verification and AML/CFT screening; establish risk monitoring and reporting procedures.
6. Integrate a payment provider only after written approval for the relevant gambling business and countries. Do not store card details.
7. Design a compliant wallet/ledger with immutable transaction history, reconciliation, segregation/safeguarding of player funds, limits and dispute handling.
8. Implement responsible-gambling controls as required: deposit/wager limits, time reminders, timeouts, self-exclusion and support links.
9. Add privacy notices, terms, complaints/ADR process, tax/accounting reports, security monitoring, backups, incident response and penetration testing.
10. Complete regulator/provider approval and legal sign-off before enabling real-money functionality.

## Safety note

Do not enable deposits, withdrawals or real-money wagering in this starter. All game results and balances in the UI are intentionally for demo entertainment and are not secure or suitable for monetary value.
