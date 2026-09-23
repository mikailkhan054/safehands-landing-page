# safehands-landing-pag
# SafeHands Insurance Booking Platform — Task 1

Responsive landing page for **SafeHands Insurance Brokers**, featuring a services overview and a client-side validated booking form.

## Folder Structure

```
safehands-booking/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Features

- Responsive layout built with **Flexbox** and **CSS Grid**
- Semantic HTML (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Booking form collecting Name, Email, Phone, and Preferred Date/Time
- Real-time client-side validation (on blur and on submit)
- Form submission via `fetch()` as a `POST` request to `/api/bookings`
- Success/error status message shown to the user
- Accessible markup: labels linked to inputs, `aria-live` status region

## How to Run

Simply open `index.html` in a browser, or serve the folder with any static server (e.g. VS Code Live Server).

## What I Did

Built a fully responsive landing page for SafeHands with a services section, an FAQ section, and a booking form that validates name, email, phone, and date/time on the client side before submitting via fetch to `/api/bookings`.

## What Was Hard

Getting the phone number and datetime validation regex/logic right without being overly strict was tricky, along with making the form status message accessible using `aria-live` so screen readers announce it.

## What I Left Out

The `/api/bookings` endpoint itself is not built yet — per the task, that's for a later step — so submitting the form currently shows an error message since there is no backend to respond yet. Login/authentication and the admin dashboard are also out of scope for this task.
