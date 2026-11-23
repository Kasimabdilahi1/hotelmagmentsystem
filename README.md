# Maison Hotel Management System

A responsive hotel management UI prototype for hotel administrators, front desk cashiers, and guests. It pairs a navy-and-gold hotel operations dashboard with a guest booking experience inspired by the supplied visual reference.

## Preview

Open `index.html` in a modern browser. No build step or package installation is required.

Use the role selector in the top bar to switch between:

- **Administrator** — hotel overview, room inventory, reservations, customers, staff, financial summaries, reports, and settings.
- **Cashier** — front desk dashboard, reservations, guest check-in and check-out, and payment processing.
- **Customer** — hotel landing page, room browsing, availability search, and room details.

## Prototype interactions

- Create reservation and room dialogs
- Check-in room assignment flow
- Check-out folio review and invoice action
- Payment collection and receipt confirmation
- Responsive layouts for desktop, tablet, and mobile widths
- Dashboard charts, room summaries, and sample reservation data

## Technology

- HTML, CSS, and vanilla JavaScript
- Font Awesome icons
- Google Fonts (DM Sans and Playfair Display)
- Hotel photography loaded from Unsplash

The prototype is self-contained in `index.html`; fonts, icons, and photography require an internet connection.

## Scope

This is a front-end prototype with illustrative sample data. It does not include authentication, a database, persistent booking records, real payment processing, or server-side authorization. Form actions demonstrate interface flows and show confirmation messages; they do not submit transactions.

## Project structure

```text
hotel-system/
├── index.html
└── README.md
```

## Future work

- Connect role-based authentication and server-side permissions.
- Add persistent room, customer, reservation, and payment records.
- Integrate a payment provider and transactional booking confirmation.
- Add invoice and report export generation.
- Complete dedicated account, login, and booking checkout screens.

